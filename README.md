# Firebase Intro Workshop

This repo contains the code used for the introduction to Firebase Workshop for [DSC AE-FUNAI](https://dsc.community.dev/federal-university-ndufu-alike-ikwo-funai/) that held on Friday, 18th September, 2020.

The slide that made use of the code in this repo are at https://docs.google.com/presentation/d/1ud6o3QpegtLgsoq8kRVGs2cmpwd9mpwD8HLK50Z6WdU/edit?usp=sharing

## How it Works
Aside the main branch, there are four other branches: hosting, auth, firestore and storage. The idea is to showcase each of the above four Firebase features, one after the other, in real time, as they are being discussed, and to checkout to each branch and deploy during the course of the overview.

In the first place, the speaker gives an introduction or overview of Firebase. Then the speaker creates a Firebase project and gives out the deployment link to the attendees. They check it and the site is not found. Then, the speaker checkouts to the hosting branch in which the website contains a simple logo and description of DSC AE-FUNAI. The speaker then deploys and asks the attendees to refresh the page, and they will notice the immediate change from `firebase deploy`.

Then he explains authentication, checks out to the auth branch, deploys and ask them to refresh the link. The attendees then get to appreciate the immediate difference and sign in with their Google accounts. 

Then the speaker explains Firestore, checks out to the firestore branch, deploys and asks the attendees to chat on the deployed website. The speaker could also show their Firestore data section in the Firebase console of the project being used to the attendees, such that they could see as changes reflect in real time as they are chatting in the FriendlyChat website.

Finally, the speaker enables the storage, checks out to the storage branch, deploys and asks the members to share pictures too. He also shares his screen on storage section of the Firebase console, and the attendees see how the images get to reflect immediately there in the console.

## Attribution 
Majority of the code is from the **Firebase Friendly Chat App** built in the [Firebase: Build a Real Time Web Chat App Codelab](https://codelabs.developers.google.com/codelabs/firebase-web/) with code at https://github.com/firebase/codelab-friendlychat-web/tree/master/web

