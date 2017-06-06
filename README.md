### Selychanske Tov website
The website is a Single page application which contains info about Selychanske company address is 23316,Vinniytsya disctrict, Shevchenka str. 135b.
Made with JS and Boostrap and hoated with Cosmic JS.
#### Start app
```
yarn start
```
#### Start app connected to your Cosmic JS Bucket
```
COSMIC_BUCKET=your-bucket-slug yarn start
```
Open [http://localhost:3000](http://localhost:3000).
### Setting up MailGun to send emails from the contact form
Because Node.js doesn't have a mail server, the contact form uses MailGun to send emails.

1. Go to MailGun and login to your account or setup a new account.
2. Get your api key and domain.
3. To configure your deployed application, add your domain and api key to your environment variables (MAILGUN_DOMAIN, MAILGUN_KEY) located in Your Bucket > Web Hosting > Environment Variables, or hard code them into `app.js` (not advised).
