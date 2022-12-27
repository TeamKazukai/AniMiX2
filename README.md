<p align="center"><img src="https://i.ibb.co/9Yj3DC4/logo-long.png" width="250"/></p>
<h3 align="center" > AniMiX Ad-free Anime<h3/>

<p align="center">  AniMiX is an Ad free responsive web application built with the intention of providing a pleasent anime experience. <p/>

<p align="center"> Don't forget to 🌟 this repo for updates! <p/>

<img width="1440" alt="image" src="https://i.ibb.co/wzChz3Q/Screenshot-15.png">

<h2>Responsive to most devices </h2>
<div class="flex" align="center"> 
  <img width="313" alt="image" src="")>
  <img width="313" alt="image" src="">
  <img width="313" alt="image" src="">
  <img width="313" alt="image" src="">


  </div>

<h2> App Features </h2>

### Popular, trending, and recently released Animes

Stay up to date with the latest anime trends and be informed about what to watch next with what's trending and popular!

### Top Anime List

Ever thought to yourself "I can't find any good anime's to watch. If only I can ask someone". Well! Worry no more! The top anime list will put you right on track and enlighten you with the knowledge of what your fellow anime enjoyers are busy having a blast watching! If you still can't find something that sratches that itch, the next feature below will be just what you need.

### Advanced search and filter with genres

Use the advanced search and genre combo selector to filter away all the the animes you're not interested in and hone down on the exact niche you're looking for. Don't feel like watching comedy animes that are still airing and instead want to watch a quick 24 epsisode dramatic action anime in one spiffing sitting? No problem. Just select the drama and action genres, select the "complete" status filter, sort the list in anyway you like, and explore the glorious works of renowned anime studios.

### Watch-based recommended Animes

Finished a splendiferous anime and now you're sad that there are no more episodes and wish that you could find a similar anime? No worries! Right under the Synopsis beneath the video player, a beautiful recommended list of animes awaits you.

### Watch list (bookmarking animes)

Have a long list of animes that you wish to watch? Awesome! Once you click on anime of interest, just press the "Add to Watchlist" button and your anime will be stored in your personal watchlist. Access the watchlist via the top navigation bar.

### User account synchronization

Here at Ashanime, we use firebase to sync your information to the cloud. Log in from anywhere and find your watchlist, shows watched and last episodes watched all available to you via the cloud.

### PWA compliant

Tired of repeatedly opening the browser and searching for Ashanime every single time you feel like Bing Chilling? No worries fam. Be it on Android, iOS, MacOS, or PC, simply download the PWA from your chrome browser and install Ashanime right on your device! You'll receieve updates automatically whenever you open your app.

## Local Deployment

### Firebase Installation

To use Ashanime with firebase, create a firebaseConfig.js file in Ashanime-Web-App/src/firebase and insert your firebase config details therein.
Be sure to create an export const with the name "firebaseConfig".
See example below:

```ts
export const firebaseConfig = {
	apiKey: "sjhHDJsh82hJHdh3jHJDHJQk4398",
	authDomain: "yourdomain.firebaseapp.com",
	databaseURL: "https://jgjfhg453EHQHT.asia-east1.firebasedatabase.app",
	projectId: "your project id",
	storageBucket: "projectid.appspot.com",
	messagingSenderId: "333747474747477",
	appId: "yourappid",
	measurementId: "R-FKJHSJW",
};
```

### Firebase rules configuration

To secure your firebase app and allow it to correctly work with Ashanime, please access your realtime database rules:

<img width="602" alt="image" src="https://user-images.githubusercontent.com/96653465/205239377-ec33c27c-e629-474c-ac9c-27fd9ca30c7f.png">

Then, insert the following code into your rules:

<img width="702" alt="image" src="https://user-images.githubusercontent.com/96653465/205239495-428c7bd3-631f-4a40-9992-b24433d170dd.png">


You need to have `nodejs` and `git` installed on your pc for the upcoming steps.

First download the repository using

```
git clone https://github.com/Ashanime/Ashanime-Web-App
```

This should download this repository to your computer. Next, to download the dependencies run

```
npm install
```

Now start the production build of the site using

```
npm start
```

This will start the app on http://localhost:3000

## Aknowledgements

 <a href="https://github.com/consumet/consumet.ts/">
    <img src="https://img.shields.io/badge/consumet/consumet.ts-333.svg?style=flat-square">
  </a>
  
This app would not have been possible without the kind and rapid support of the experts over at [Consumet](https://github.com/consumet).
Ashanime was built using the Consumet API to supply 95% of the data.


## License

Licensed under [AG](./LICENSE).

