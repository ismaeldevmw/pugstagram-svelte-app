
![pugstagram-screenshot](https://user-images.githubusercontent.com/13697123/83602170-a8ae4900-a537-11ea-9cfc-3bb6773d8af3.PNG)

# Pugstagram app 

This is a simple project of a social network app where you can see how "__Svelte__" framework work. This project is part of the Platzi platform course entitled "Curso de Svelte & Curso de Sapper"

## Get started

Install the dependencies...

```bash
cd pugstagram-svelte-app
npm install
```

...then start [Webpack](https://webpack.js.org/):

```bash
npm run dev
```

Navigate to [localhost:3000](http://localhost:3000). You should see your app running. Edit a component file in `src`, save it, and reload the page to see your changes.

## Building and running in production mode on Netlify
Add into section Build & deploy -> Continues Deployment.

Build command:
```bash
npm run export
```
Public directory:
`__sapper__/export`

## Building and running in production mode on Heroku
Build app:
```bash
npm run build
```
Public directory generated:
`__sapper__/build`

Run the app:
```bash
node __sapper__/build
```

You can see the result of our app in this url.
[https://pugstagram-svelte.herokuapp.com](https://pugstagram-svelte.herokuapp.com)

## New libraries installed
```bash
npm install sapper --save-dev
npm install polka compression sirv
```