# friendlyeats-firebase-images

# 🚀 FriendlyEats is a restaurant recommendation app built on Cloud Firestore 🚀

https://github.com/coding-to-music/friendlyeats-firebase-images

https://friendlyeats-firebase-images.vercel.app

From / By https://github.com/firebase/friendlyeats-web

## Environment variables:

```java
serviceAccount = JSON.parse(process.env.FIREBASE_SERVICE_ACCOUNT_KEY as string)

const firebaseConfig = {
  apiKey: process.env.NEXT_PUBLIC_FIREBASE_API_KEY,
  authDomain: process.env.NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN,
  projectId: process.env.NEXT_PUBLIC_FIREBASE_PROJECT_ID,
  storageBucket: process.env.NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET,
  messagingSenderId: process.env.NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID,
  appId: process.env.NEXT_PUBLIC_FIREBASE_APP_ID,
  measurementId: process.env.NEXT_PUBLIC_FIREBASE_MEASUREMENT_ID,
}
```

## GitHub

```java
git init
git add .
git remote remove origin
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:coding-to-music/friendlyeats-firebase-images.git
git push -u origin main
```

# FriendlyEats (Web)

## Introduction

FriendlyEats is a restaurant recommendation app built on Cloud Firestore.
For more information about Firestore visit [the docs][firestore-docs].

This project is the starting point for the [Cloud Firestore Web Codelab][codelab],
which will show you how to build the applications step-by-step. If you'd like to
simply run the finished result, see the [quickstart app][quickstart].

<img src="docs/finished_image.png" />

## Setup

Follow the [Cloud Firestore Web Codelab][codelab] to set up this sample.

## License

© Google, 2018. Licensed under an [Apache-2](./LICENSE) license.

## Build Status

[![Build Status](https://travis-ci.org/firebase/friendlyeats-web.svg?branch=master)](https://travis-ci.org/firebase/friendlyeats-web)

[codelab]: https://codelabs.developers.google.com/codelabs/firestore-web
[quickstart]: https://github.com/firebase/quickstart-js/tree/master/firestore
[firestore-docs]: https://firebase.google.com/docs/firestore/