# Tailwind config for Tuple

## Client config

Check out the `update-tw-and-customize-for-tuple` branch.

## Backend config

Check out the `master` branch. I copied over the generated css into the Rails app to avoid doing Webpacker shenanigans in the Rails app for now.


## Setup

This is an example of a super simple Webpack setup for using [Tailwind CSS](https://tailwindcss.com).

To get started, clone the project and install the dependencies:

```
# Using npm
npm install

# Using Yarn
yarn
```

After that, start up Webpack Development Server:

```
npm run dev
```

Webpack Development Server will watch `/src/styles.css` and `/tailwind.js` and rebuild your stylesheet on every change.

You can play around with `/index.html` to see the effects of your changes.

To build a production bundle run:

```
npm run prod
```

After that you will have a ready to deploy bundle at `/dist`
