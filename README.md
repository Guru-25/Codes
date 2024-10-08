# Useful Codes
![Codes](https://i.imgur.com/LEe0slG.jpg)

This codes help to generate 👇

#### String Session:

- [Pyrogram](https://github.com/Guru-25/Codes#pyrogram)

- [Telethon](https://github.com/Guru-25/Codes#telethon-user-only) (only user session)

- [Pyrogram-And-Telethon](https://github.com/Guru-25/Codes#pyrogram-and-telethon-user-only) (only user session)

#### Google Drive Rclone:

- [Full-Access](https://github.com/Guru-25/Codes#full-access)

- [Specific-Folder](https://github.com/Guru-25/Codes#specific-folder)

- [Token-Pickle](https://github.com/Guru-25/Codes#token-pickle)

#### Telegra.ph

- [Token](https://github.com/Guru-25/Codes#token)

-----

# String Session:

### Pyrogram
Pyrogram String Session can be generated by https://replit.com/@DaxDuck/GenerateStringSession or by running the following commands
```
pkg install python wget
wget https://raw.githubusercontent.com/guru-25/codes/master/generate_string_session.py
pip install pyrogram tgcrypto
python3 generate_string_session.py
```
(Use `python` if `python3` doesn't work) and then, paste your API KEY and API HASH there, and use the bot token/phone number and copy the token.

-----

### Telethon (user only)
Telethon User String Session can be generated by running the following command, _(Just copy + paste in termux and follow the instructions)_

`pkg install git && pkg install python && pkg install openssl && pip3 install telethon && git clone https://github.com/Guru-25/Codes && cd Codes && bash genString`

-----

### Pyrogram And Telethon (user only)
Pyrogram or Telethon User String Session can be generated by https://replit.com/@DaxDuck/StringSessionGenerator

-----

# Google-Drive-Rclone:

### Full Access
Google Drive Rclone can be generated by https://replit.com/@DaxDuck/GenerateDriveToken or by running the following commands
```
pkg install python wget
wget https://raw.githubusercontent.com/guru-25/codes/master/generate_drive_token.py
pip install oauth2client
python3 generate_drive_token.py
```
(Use `python` if `python3` doesn't work) and enter your client id, client secret, open the generated link, give authorize and paste the refresh token. Finally copy the generated token.

-----

### Specific Folder
Rclone for Google Drive Specific Folder can be generated by running the following commands
```
pkg install rclone
rclone config
n
<any name>
13
<client id>
<client secret>
1
<folder id>
(skip)
n
y
<token>
y/n (y=TeamDrive, n=Drive)
<TeamDrive/Drive name/number>
y
q
```
(You have to give your own details for `name`, `client id`, `client secret` and `folder id` so that only I have used `< >`.
For `(skip)` just press the enter key.) and copy the token.

-----

### Token Pickle
Download `credentials.json` from https://console.developers.google.com and rename as `credentials.json` and move to Download directory. Also download [generate_token_pickle.py](https://raw.githubusercontent.com/Guru-25/Codes/master/generate_token_pickle.py) and move to `credentials.json` directory and run the following commands 
```
termux-setup-storage
cd /storage/emulated/0/Download
pkg install python
pip install google-api-python-client google-auth-httplib2 google-auth-oauthlib
python3 generate_token_pickle.py
```
(Use `python` if `python3` doesn't work) Visit the url and give authorization and enter the authorization code. After that check your Download location, `token.pickle` will be created.

-----

# Telegra.ph:

### Token
Telegra.ph token can be generated by https://replit.com/@DaxDuck/GenerateTelegraphToken or by running the following commands
```
pkg install python wget
wget https://raw.githubusercontent.com/guru-25/codes/master/generate_telegraph_token.py
pip install telegraph
python3 generate_telegraph_token.py
```
(Use `python` if `python3` doesn't work) and give any name and copy the token.

-----

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for review - see the [CONTRIBUTING.md](CONTRIBUTING.md) file for details. 

## Support the project

Development is financed by individual user contributions, i.e. you becoming a sponsor or donating ❤️.

- [Become a sponsor](https://github.com/sponsors/Guru-25) on GitHub

  or

  <a href="https://gururaja.in/donate">
      <img src="https://github.com/TakiShiwa/donate-with-upi/blob/main/Button/SVG/UPI-teal-01.svg" alt="UPI Pay" height="40">
  </a>
  
> [!NOTE]  
> UPI is only available for Indian users.

## Get help

* [Mail](mailto:mail@gururaja.in)
* [Github Discussions](https://github.com/Guru-25/Codes/discussions)

## License

This code is available under a GPL v3 license - see the [LICENSE](LICENSE) file for details.
