# Nuxt SPA Firebase

## Setup Firebase Hosting
1. Go to https://console.firebase.google.com/
2. Create new project
3. Go to Project Settings -> Your Apps -> Web App
4. Name your app, check `Also set Firebase Hosting`
5. Follow steps to finish settings eg: `npm install -g firebase-tools` if you don't have it installed
6. Click `Continue to console`

## Setup Deployment
1. Install dependencies `yarn`
2. Run command `firebase login`
3. Init deployment`firebase init`
4. Are you ready to proceed? (Y/n) `Y`
5. Check only `Hosting` option
6. `Use existing Project` and select previously created project
7. What do you want to use as your public directory? `dist`
8. Configure as a single-page app `N`

## Deploy 
1. `yarn deploy`
2. Check `Hosting` section in Firebase console to see deployment log
3. Create beauty
 
