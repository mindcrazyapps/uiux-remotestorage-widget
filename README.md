<br/>

<h5 align="right">rockapps.github.io</h5>

<p align="center">
 <img src="https://cdn-icons-png.flaticon.com/512/1600/1600856.png" alt="image" width="70px">
</p>

<h4 align="center"> Please see this live demo <a href="https://tiddlywiki-store.netlify.app/"> here </a>  and the documentation <a href="https://mindcrazyapps.github.io/tiddlywiki-store/#/"> here </a> here </h3>

<p align="center">
 <img src="https://user-images.githubusercontent.com/123137817/214212215-a0b1c3eb-664d-442f-b235-17f531874de3.png" alt="image">
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/123137817/214212225-2e8193cd-d4f0-4a24-aee1-ff31b33fdf2a.png" alt="image">
</p>

# remotestorage-widget [WORK IN PROGRESS]

Provides a connect-widget as add-on library for remoteStorage.js.

## Usage

This example is from an Ember.js app, using ember-browserify, but other than
the imports, the usage is the same in all scenarios:

```js
import RemoteStorage from 'npm:remotestoragejs';
import Widget from 'npm:remotestorage-widget';

// ...

let remoteStorage = new RemoteStorage(/* options */);

remoteStorage.access.claim('bookmarks', 'rw');

new Widget(remoteStorage);

// ...
```

## Development / Customization

Install deps:

    npm install

Build, run, watch and open test app:

    npm run dev
