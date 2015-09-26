# Ngrok

[Ngrok](https://ngrok.com/) allows you to tunnel your `localhost` server to a public URL, for beta testing, etc...

### How to use

Login to your Ngrok account [here](https://dashboard.ngrok.com/user/login)

`cd` to ngrok location on your computer

`cd /Applications`

Add ngrok auth token

`./ngrok authtoken my-auth-token`

Expose localhost as a public url

`./ngrok http 8000`