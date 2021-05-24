# Readme

Firebase official samples: https://firebase.google.com/docs/samples

## samples cloned

https://github.com/firebase/quickstart-js

https://github.com/firebase/friendlyeats-web

## Firestore

Firestore: Use our flexible, scalable NoSQL cloud database to store and sync data for client- and server-side development.

https://firebase.google.com/docs/firestore

Cloud Firestore is a flexible, scalable database for mobile, web, and server development from Firebase and Google Cloud. Like Firebase Realtime Database, it keeps your data in sync across client apps through realtime listeners and offers offline support for mobile and web so you can build responsive apps that work regardless of network latency or Internet connectivity. Cloud Firestore also offers seamless integration with other Firebase and Google Cloud products, including Cloud Functions.

Amazing tutorial🐥︎🐥︎. For cloud firesotre web codelab - Browse this official tutorial: https://firebase.google.com/codelabs/firestore-web#2

## Installed firebase-tools globally in npm:

sudo npm -g install firebase-tools
firebase --version
firebase login

## Associating my app with a firebase project by 

firebase use --add

## Good link

https://firebase.google.com/docs/web/setup (All web and node docs here for firebase 🔥︎🔥︎!!)

## Manage you firebase projects by firebase console

https://console.firebase.google.com/u/0/

## Fireship.io

Watch everything from fireship.io's content for firebase, and then rest only!!!

Firebase is BaaS: Backend-as-a-Service

The best code is no code at all. Jeff Atwood

Firebase is an extension of "Google Cloud Platform" (GCP).

Firebase is SDK for frontend app.

A firebase project(i.e, cool-proj1) can have multiple web apps.

Firebase cdn links source: (🤠︎the link is there in the generated script tags too)
https://firebase.google.com/docs/web/learn-more?authuser=0#add-sdks-cdn

You need to run below command to configure firebase in a project

firebase init

Choose feautres: Hosting and Emulators (from the list: Database, Firestore, Functions, Hosting, Storag, Emulators, Remote Config).

WATCH VIDEO FROM FIRESHIP.IO for EMULATOR(emulators is just simulation of firebase services locally on our system, and that means we can run database records and cloud functions on our system without connecting to google cloud ). ADVANCE EMULATOR TECHNIQUES.

Firebase init adds secret to your github repo if you select autmatic deployment:
FIREBASE_SERVICE_ACCOUNT_COOL_PROJ1.

For emulator setup: Choose the ``hosting`` option.

I choose emulator port to be 5005(default is use any available) and to install the emulator now(default is no).

### Rewriting routes in firebase.json file

Use rewrites property inside the hosting key in ``firebase.json`` to configure any redirects you want!!

e.g., 

```
"rewrites": [
	{
		"source": "**",
		"destination": "/index.html"
	}
]
```

### Starting the app

`firebase server` or `firebase emulators:start`

### Deployment

Use `firebase deploy` to deploy your app but IMO the app will be automatically deployed when you push a commit to github as I configured the ci with firebase as well.

## Learn about web and firebase

https://firebase.google.com/docs/web/learn-more?authuser=0#modular-version


### Adding firebase to your js project official guide

https://firebase.google.com/docs/web/setup

### Firebase JavaScript SDK Reference

https://firebase.google.com/docs/reference/js/?authuser=0
