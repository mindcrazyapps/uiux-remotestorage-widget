<br/>

<h5 align="right">rockapps.github.io</h5>

<p align="center">
 <img src="https://cdn-icons-png.flaticon.com/512/1600/1600856.png" alt="image" width="70px">
</p>


<h4 align="center"> Please see this live demo <a href="https://tiddlywiki-store.netlify.app/"> here </a>  and the documentation <a href="https://mindcrazyapps.github.io/tiddlywiki-store/#/"> here </a> here </h3>


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
