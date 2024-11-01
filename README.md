
## The Dawn Validator Bot

![Dawn Validator Bot Screenshot](https://i.ibb.co.com/gzQP3LS/3.png)



## Features

- **Supports Multiple Accounts**: Manage multiple user accounts simultaneously for efficiency.
- **Proxy Binding for Each Account**: Automatically assign a unique proxy to each account.
- **One Proxy per Account**: Each account gets its own proxy to reduce IP bans.
- **Multithreading**: Handle multiple accounts concurrently for better performance.
- **Colored Output**: Log messages are color-coded for easy reading.
- **Retry on Connection Failures**: Automatically retry operations if a connection fails.
- **Error Handling**: Manage exceptions and provide meaningful feedback.
- **Bugs for Future Fixes**: I’ve added some bugs to fix them later.


## Installation

Install Python 3.10+ 

```bash
  pip install -r requirements.txt
  configure accounts.json 
  configure proxy.json

```
**Note**: Config.json file does not work yet. I will complete the code in my free time. And for proxy, you need to strictly follow this pattern: 
```bash
  "socks5://ip:port:username:password"

```
And make sure to add more proxy than your total number of accounts.



    
## Getting Berear Token: 
- Install extension from here : https://chromewebstore.google.com/detail/dawn-validator-chrome-ext/fpdkjdnhkakefebpekbdhillbhonfjjp?hl=en
- Sign up with your email and you can use my ref code too **ricsbym0** :) 
![point](https://github.com/MrTimonM/dawn-validator-bot/blob/main/1.png)
- Click on the refresh arrow beside Total Earning 
- Right Click on mouse and click "Inspect" then go to Network Tab 
![auth](https://github.com/MrTimonM/dawn-validator-bot/blob/main/2.png)
- Click on point refresh button again 
- In the network section, look for **getpoint** and Copy Berear token

## Support 
- If you find any error, please submit an issue :) 


## Conclusion 
- I don't know how long session token stays alive, maybe we will find out it together hehe :) 

