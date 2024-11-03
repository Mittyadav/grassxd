# GrassXD

A useful program to help you collect grass points

README in Indonesia language in [here](README_ID.md)

# Table of Contents

- [GrassXD](#grassxd)
- [Table of Contents](#table-of-contents)
- [Registration](#registration)
- [Warnings and Notes](#warnings-and-notes)
- [About Proxy](#about-proxy)
- [How to Use](#how-to-use)
- [JavaScript Code to Get Data](#javascript-code-to-get-data)
  - [Code to get userid](#code-to-get-userid)
  - [Code to get token](#code-to-get-token)
- [Discussion Forum](#discussion-forum)
- [Support](#support)
- [Thank You](#thank-you)

# Registration

If you haven't registered for grass yet, please use the following URL: [Click here](https://app.getgrass.io/register/?referralCode=9hUjGgcGTPW5Aqn)

# Warnings and Notes

All risks are borne by the user!

This program only supports one account.

# About Proxy

For proxy services, I am currently experimenting with the following sites:

[First Site](https://app.nstproxy.com/register?i=YhCRDQ)

The format used follows these examples:

Example formats:
```
http://host:port
socks5://host:port
http://user:password@host:port
socks5://user:password@host:port
```

# How to Use

1. Make sure your computer has Python and Git installed
   
2. Open terminal on your device (CMD/Powershell/Terminal)

3. Clone this repository. You can use the command below:
   ```shell
   git clone https://github.com/akasakaid/grassxd.git
   ```

4. Enter the grassxd folder:
   ```shell
   cd grassxd
   ```

5. Then install the required libraries:
   ```shell
   python -m pip install -r requirements.txt
   ```

6. Fill in your proxies in the proxies.txt file according to the examples I provided in [About Proxy](#about-proxy). If you don't fill in the `proxies.txt` file, it will automatically use your public IP.

7. Run the `setup.py` file first. You will be prompted to enter your grass account email and password to get authentication (id and token). If you encounter any errors or other issues, please obtain your userid and token manually. See [JavaScript Code to Get Data](#javascript-code-to-get-data)

8. Run the `main.py` file

# JavaScript Code to Get Data

## Code to get userid

Make sure you are logged into the grass website.

You can use the JavaScript code below by pasting it in the console menu in the dev tools / dev options of your browser.

Here's the JavaScript code to get userid:
```javascript
copy(JSON.parse(localStorage.getItem("userId")))
```

The code above automatically copies the userid to your clipboard, so you just need to paste it into the `userid.txt` file

## Code to get token

Here's the JavaScript code to get token:
```javascript
copy(JSON.parse(localStorage.getItem("accessToken")))
```

The code above automatically copies the token to your clipboard, so you just need to paste it into the `token.txt` file

# Discussion Forum

If you have any questions, please ask [here](https://t.me/sdsproject_chat)

# Support

If you like my project, you can buy me a coffee through the websites below:

- Indonesian [Trakteer.id](https://trakteer.id/fawwazthoerif/tip)
  
- Ton Address: `UQBDK-6ed0f2kX63hX4LB1rsLcnhx--zthwT_6g25a0Qakvb`

# Thank You