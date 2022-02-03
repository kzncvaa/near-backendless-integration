# Authorization  

### Here is the login method

**method** - `POST`   
**body**:  
```JSON
{
	"account_id": "account.testnet",
	"receiver_id": "inotel.pool.f863973.m0",
	"method": "ping",
	"params": {},
	"deposit": 0,
	"gas": 30000000000000,	
	"meta": "",
	"callback_url": "",
	"network": "testnet"
}
```  

| Param                            | Description                                                                                                             |
| -------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| `account_id`                     | _Signer Account_                                                                                                        |
| `receiver_id`                    | _Recipient contract account, may be dApp contract or personal account_                                                  |
| `method`                         | _Contract method to call. Use `!transfer` to transfer NEAR tokens_                                                      |
| `params`                         | _Transaction arguments_                                                                                                 |
| `deposit`                        | _Attached deposit in NEAR_                                                                                              |
| `gas`                            | _Attached gas in yoctoNEAR_                                                                                             |
| `meta`                           | _Transaction meta. May be empty_                                                                                        |
| `callback_url`                   | _URL to redirect user after the transaction. May be empty_                                                              |
| `network`                        | _Your network: mainnet/testnet_                                                                                         |


<img src="../img/method_login.png" height="500px">
