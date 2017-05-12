# Simple LOGIN with Facebook Graph API

I did this with the oficial documentation from [Facebook Developers's Documentation](https://developers.facebook.com/docs/javascript) and with their [Graph API Explorer](https://developers.facebook.com/tools/explorer/).

If you want to try it you just have to configure your Developer Account, create a new app and get its App ID then paste it on the init function:

```javascript
  FB.init({
        appId      : 'YOURAPPID', /* <---- PASTE YOUR APPID HERE */ 
        xfbml      : true,
        version    : 'v2.9'
      });
```

You have to check its permissions too.

Have fun!