In order to run this app:
 
- Install [node.js](https://nodejs.org/en/).
- Clone the repository.
- Install dependencies using `npm install`.
- Make a new app at Heroku, and add the Heroku Redis add-on (free plan) and note the app URL.
- Add a config var APP_URL (usually {app_name}.herokuapp.com)
- Make a Discord webhook for a and note the URL, add it as a config var named WEBHOOK_URL.
- Deploy to Heroku.
- Have anyone who wants to contribute add the webhook on https://app.plex.tv/web/app#!/account/webhooks

Alternatively, deploy straight to Heroku now:

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

You'll be asked to complete these config vars
```
WEBHOOK_URL      # your webhook URL
APP_URL        # the App URL ({app_name}.herokuapp.com)
```
