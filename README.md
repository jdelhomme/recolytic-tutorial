## INTRODUCTION
The goal of this tutorial is to experiment <a href="http://www.recolytic.com">recolytic</a> recommendation engine in order to get familiar with its api and administration console.
## REQUIREMENT
<a href="http://curl.haxx.se/">curl</a>
## HAND ON LAB
### 1- CREATE A SUBSCRIPTION
First create a recolytic account if you don’t have already one.

Having a valid account, sign in to recolytic administration console. Click, **"Create new subscription"**, or from left menu **"Subscriptions / New Subscription"**. On subscription creation page, change the type of the subscription target from **"WebSite"** to **"Application"**. 
As Application name type **"Tutorial"** and application name **"Tutorial"**. Accept the **"Terms of service"** and click **"Create"**. 
*As you can see, you can also set some recommendation preferences for your subscription. Keep the defaults for the moment, we will come back to that later.*

<img src="http://assets.recolytic.com/www/media/tuto_create.png">

You are now on your subsciptions list and you should be able to see your new subcription. Click on the name of your subscription (Tutorial) to display its control panel.

### 2- UPLOAD YOUR DATA FEED
You are now going to upload a data feed for your subscription. Remember, this data feed is a description of the resources (products, movies, ...) recolytic is going to work on. By default, your subscription uses the **automatic mode**, that means that your resources will be created in recolytic in the same time the user behavior will be collected. Alternatively, you can choose to use the **manual mode** and upload your inventory.

In the Data feeds section of the control panel, click **Change mode**, select **Manual** and save. Download and open the file data-feed.csv from recolytic-tutorial github. This is the data we are going to upload. Now, click **declare** and upload data-feed.csv.

### 3- COLLECT: SIMULATE USERS ACTIONS


### 4- REOMMEND: ISSUE RECOMMENDATIONS


#### 4.1- NON PERSONAL RECOMMENDATION: 

#### 4.2- PERSONAL RECOMMENDATION: 

### 5- MESURE: SIMULATE UPTAKES

### 6- REPORTING: 
#### 6.1- STRATEGY PERFORMANCE
#### 6.2- RESOURCE PERFORMANCE
### 7- MORE OPTIONS
