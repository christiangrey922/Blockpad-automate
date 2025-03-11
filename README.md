# Blockpad-automate
Tool for auto running Blockpad

## Tools and components required
1. Blockpad Account, Register here: [https://testnet.blockpad.fun/register](https://testnet.blockpad.fun/register?ref=GISNLM).
2. Blockpad Account Bearer Token
3. Buying proxy at [here](https://app.proxies.fo/ref/2fe2c521-8a31-47f2-5f90-776f2627dd01).
4. Laptop or PC for running
5. 
## How to get Bearer Token
1. Open your browser console, here's the tutorial [YouTube](https://www.youtube.com/watch?v=Vmi-mVcn1uQ&ab_channel=SpeedyTutorials)
2. Paste this script to browser console:
  ```bash
  try {
  const token = localStorage.getItem('token');
  if (token) {
    console.log('Token found:', token);
  } else {
    console.log('No token found in localStorage, Please login blockpad first: https://testnet.blockpad.fun/register?ref=TZSXOS');
  }
} catch (error) {
  console.error('Error accessing localStorage:', error);
}
  ```
3. The token must be like: `eyJhbGciXXXXXX.XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX`
## Installation
- Download file. You can choose the tool run with proxy or no proxy. It's up to you.
- Password for unzip:
```bash
@christiangrey922
```
## Stay Connected

- Telegram : [Telegram](https://t.me/xamdepin)

## Donation

If you would like to support the development of this project, you can make a donation using the following addresses:

- Solana: `Gz7QxSUXXYH6pZQQPGxj7nU3AFUxZgMCB112AVVzaZSE`
- BNB: `0xf61dbe74a5e0e197e1c92c316ed1dd1c88db6bc6`

# Notes
- Run this bot, use my referral code if you don't have one.
- You can just run this bot at your own risk, I'm not responsible for any loss or damage caused by this bot.
- This bot is for educational purposes only.
