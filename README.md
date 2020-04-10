# IOSInappPurchases

## There are 4 types of purchase available in Apple inapp purchase API.
1. Consumable
  * For comumable items like , currency in a game.
2. Non-Consumable
  * Purchase once and keep forever, eg : remove add from a free game
3. Auto-Renewable Subscription
  * Monthly subscription based service.
4. Non-Renewing Subscriptions
  * Service not possible to renew, like season pass for some app.
  
  
## To develop this app
Following items are necessary
1. Real device to test
2. Paid developer account

* Define purchase in iTunes
* Load all the reference name from purchanseble items in application
* Fetch product info for all of those items
* User buys product
* Process transection response
* Validate the receipt
* Uplock the content
* Finish the trancsection

## Necessary steps 
* Login to your paid developer account from Apple (https://developer.apple.com/)
* Create a new appID (Certificates, Identifiers & Profiles > Identifiers > App IDs)
* Now login to (https://appstoreconnect.apple.com/)
* Create an app (My App > + > new app)

## Now create your inapp purchases using following steps
* Now login to (https://appstoreconnect.apple.com/)
* Go to myapp and select your app
* Click Feature > In-App Purchases > Click + sign > Any of the subscriptions type
Note : Product ID have to be unique (Eg: Bundle ID + Extra)
## Create Sandbox account to test the purchage
* Now login to (https://appstoreconnect.apple.com/)
* Go to *Users and Access* tab
* Click *Testers* under *Sandbox* group
* Create a sandbox account with necessary informations (the email address should be and paid/unpaid apple id)
* Check your email to verify the id

# Configuration
* Configure the bundle identifier
* Enable in app purchases in the capabilities tab

