# Dawn Validator Bot ReferralCode: 3zqi1daw
Automation farming Script for Dawn Validator using proxies. This bot support multi accounts.
### Tools and components required
1. Dawn Validator Account | Download [Dawn Validator Extension](https://chromewebstore.google.com/detail/dawn-validator-chrome-ext/fpdkjdnhkakefebpekbdhillbhonfjjp)
2. Open ``chrome-extension://fpdkjdnhkakefebpekbdhillbhonfjjp/signup.html``, insert Referral code ``rj6ektjg`` and Register
3. Python version 3.10
## Getting Token
- Open ``chrome-extension://fpdkjdnhkakefebpekbdhillbhonfjjp/dashboard.html`` in your browser and login
- Press F12 or CTRL+SHIFT+I and Select Network
- Look for ``getpoint?appid=``
- Open request headers and copy the token. Bearer ``a1b2c3d4ef5g`` < your token
![image](https://github.com/user-attachments/assets/2cf7d088-8ecb-4925-a470-5b398cb88e1f)
- Insert your account details in ``accounts.txt``, with each line in the format ``email:token`` for each account, like:
```bash
email:token
email:token
email:token
```
# Installation
- For Unix: ``apt install python3 python3-pip -y``
- Unix:
```bash
pip3 install -r requirements.txt
```
### Run the Bot
- Replace the proxies example in ```proxies.txt``` to your own proxies

#### Run  accounts default  
！！！！！！attention please
!!!!!!!!!!Single account, single program, multiple proxies, with proper isolation of proxy IPs and accounts from each other

- Unix
```bash
python3 main.py
```
# Notes
- Run this bot, and it will update your referrer code to my invite code if you don't have one.
- This bot have delay every 5 minutes. 
- You can just run this bot at your own risk, I'm not responsible for any loss or damage caused by this bot. This bot is for educational purposes only.
