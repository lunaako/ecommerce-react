# CrystalLuna | E-commerce React App for Crystals
A specialized e-commerce React JS app focused on selling high-quality crystals, integrated with Firebase [TypeScript].
![Firebase Deploy](https://github.com/jgudo/ecommerce-react/workflows/Firebase%20Deploy/badge.svg)

### [Live demo](https://ecommerce-react-luna.web.app/)
![CrystalLuna screenshot](https://raw.githubusercontent.com/lunaako/ecommerce-react/master/static/crystal-screenshot-1.png)
![CrystalLuna screenshot](https://raw.githubusercontent.com/lunaako/ecommerce-react/master/static/crystal-screenshot-2.png)

## About CrystalLuna
CrystalLuna is an online platform dedicated to offering a wide variety of crystals, from healing stones to decorative pieces. Our mission is to provide customers with authentic, high-energy crystals to enhance their spiritual and aesthetic experiences. Explore our collection to find the perfect crystal for your needs.

## Run Locally
### 1. Install Dependencies
```sh
$ yarn install
```

### 2. Create a new Firebase project
Login to your Google account and create a new Firebase project [here](https://console.firebase.google.com/u/0/)

Create an `.env` file and add the following variables.

```
// SAMPLE CONFIG .env, you should put the actual config details found on your project settings

VITE_FIREBASE_API_KEY=AIzaKJgkjhSdfSgkjhdkKJdkjowf
VITE_FIREBASE_AUTH_DOMAIN=yourauthdomin.firebaseapp.com
VITE_FIREBASE_DB_URL=https://yourdburl.firebaseio.com
VITE_FIREBASE_PROJECT_ID=yourproject-id
VITE_FIREBASE_STORAGE_BUCKET=yourstoragebucket.appspot.com
VITE_FIREBASE_MSG_SENDER_ID=43597918523958
VITE_FIREBASE_APP_ID=234598789798798fg3-034

``` 

After setting up necessary configuration,
create a **Database** and choose **Cloud Firestore** and start in test mode

### 3. Run development server
```sh 
$ yarn dev
```

---

## Build the project
```sh
$ yarn build
```

## How to add products or perform CRUD operations for Admin
1. Navigate to your site to `/signup`
2. Create an account for yourself
3. Go to your Firestore collection `users collection` and edit the account you've just created. Change the role from `USER` to `ADMIN`.
4. Reload or sign in again to see the changes. 

**Firebase Admin to be integrated soon**

## Features

* Admin CRUD operations for managing crystal inventory
* Firebase authentication for secure user access
* Firebase auth provider authentication
* Account creation and edit for personalized shopping experiences
