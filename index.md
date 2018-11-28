---
id: get-started-google-cloud-shell
summary: In this how-to we'll find out how to set up a development environment for our LoopStore purely in the cloud. You can then follow the tutorial from with the Cloud Shell.
status: [draft]
author: LoopStore
categories: LoopBack,Google Cloud Shell
tags: cloudant,google cloud shell,graphql,ibm cloud,loopback,loopstore,node,openapi,rest
feedback link: https://github.com/loopstore/loopstore-tutorial-v4/issues

---

# Get Started using Google Cloud Shell

[Codelab Feedback](https://github.com/loopstore/loopstore-tutorial-v4/issues)


## Introduction
Duration: 02:00


### The first subheader

    adb shell am start -a android.intent.action.VIEW \
    -d "http://recipe-app.com/recipe/pierogi-poutine" com.recipe_app

Install the cli

    npm i -g @loopback/cli

#### Start the app generator  [see all CLI options](https://github.com/strongloop/loopback-next/blob/master/packages/cli/README.md)

    lb4 app

#### Start the app generator  [see all CLI options](https://github.com/strongloop/loopback-next/blob/master/packages/cli/README.md)

    lb4 app

`Name of your application`

```
Name of your application
```

    loopstore

```
Enter a description
```

    Build a store with loopback 4

```
directory
```

    package

#### Change into the package directory

    cd package

#### Start the app 

#### Using npm start

    npm start

### What you'll learn

* How to write a Dockerfile
* How to build a container
* How to run a container
* How to use the GCP Container Registry Service
* How Containers differ from Virtual machines

### What you'll learn

* One
* Two

### What we've covered

* One
* Two

In this HOW-TO sWhatection we'll be creating a free tier IBM Cloud account and setting up Cloud Foundry app instance for deploying our LoopStore.

We'll install and configure the IBM Cloud CLI for deploying our app..

We'll also set up a Cloudant database service and update the code so we can use it to persist data for our  [Models](https://loopback.io/doc/en/lb4/Model.html). 

#### Frequently Asked Questions

*  [How do I install Android Studio?](https://developer.android.com/sdk/installing/studio.html)
*  [How do I enable USB debugging?](http://developer.android.com/tools/device.html)
*  [Why doesn't Android Studio see my device?](http://stackoverflow.com/a/16598454)
*  [Android error: Failed to install *.apk on device *: timeout?](http://stackoverflow.com/a/4786299)

    shoulbe like -code withcopy 

#### index.html

```
<activity android:name="com.recipe_app.client.RecipeActivity"
         android:label="@string/title_gizmos" >
   <intent-filter android:label="@string/filter_title_viewrecipe">
       <action android:name="android.intent.action.VIEW" />
       <!-- URIs that begin with "http://recipe-app.com/recipe" -->
       <data android:scheme="http"
             android:host="recipe-app.com"
             android:pathPrefix="/recipe" />
       <category android:name="android.intent.category.DEFAULT" />
       <category android:name="android.intent.category.BROWSABLE" />
   </intent-filter>
</activity>
```

<walkthrough-editor-open-file  filePath="test-cloudshell-tutorial/test.md" text="Open test.md"></walkthrough-editor-open-file>

<walkthrough-spotlight-pointer spotlightId="devshell-web-preview-button" text="Spotlight web preview"></walkthrough-spotlight-pointer>

<walkthrough-editor-spotlight spotlightId="navigator" filePath="hello.md" text="My file"></walkthrough-editor-spotlight>

For additional information that you would like to specially call-out in your codelab, there are two styles of info boxes:

Positive information like best practices and time saving tips should be formatted as a **single-cell table** with a **light green 3** background. For example:

<aside class="special">

**Best Practices**

Only call the `AppIndexApi.view()` method once each time the user explicitly chooses to view some content.

There should be an existing  [deep link](http://localhost:11080/app-indexing/webmasters/app) in the app for each API call.

Use an accurate and descriptive title in your `AppIndexApi.view()` call. The text defined in this title may be used in the Google app query autocompletions.

We recommend that you inform your users that links visited in the app may be shared with Google to improve the search experience.
</aside>

Negative information like warnings and API usage restrictions should be formatted as a **single-cell table** with a **light orange 3** background. For example:

<aside class="warning">

**Important**: When opening an app via a deep link, the app should provide users with a  [First Click Free](http://googlewebmastercentral.blogspot.com/2008/10/first-click-free-for-web-search.html) experience. This means that on the first visit to your app, a user should go directly to the relevant content, not interrupted with any interstitial content like prompts or login screens. You may prompt the user for an action after the first click. The First Click Free experience must be provided even if the app has never been launched or a user logged in.
</aside>


## Why use IBM Cloud?



LoopBack apps can be hosted in any  [Node.js](https://nodejs.org/) environment and connect to a wide variety of data  sources. 

[IBM Cloud](https://www.ibm.com/cloud/) is a convenient option for getting our LoopStore up and running on the web. It offers full-stack cloud platform with over 170 products and services. It also offers a useful free tier to give developers a chance to explore, with no need to enter credit card details.

All you really need is an email address to confirm your registration, a first and last name and your region to create an IBM id.

That'll get us 256MB of memory on IBM's  [Cloud Foundry](https://www.cloudfoundry.org/the-foundry/ibm-cloud-foundry/) platform, where we'll set up a vanilla  [Node.js](https://nodejs.org/) instance for deploying our LoopStore app to the cloud.

As a big bonus, our IBM id gives us access to the  [Cloudant](https://www.ibm.com/cloud/cloudant) database service. We can connect to all sorts of backend data services through LoopBack's  [DataSources](https://loopback.io/doc/en/lb4/DataSources.html). Cloudant is a distributed, non-relational document database (a bit like  [MongoDB](https://www.mongodb.com/)), which suits storing data for our LoopBack  [Models](https://loopback.io/doc/en/lb4/Model.html) well. 

