# acme_photography

CSS3 playground

## Instructions

```bash
yarn install
yarn dev
```

## Production build

```bash
yarn build
firebase login
firebase deploy
```

More info about firebase deploy in: <https://medium.com/google-developer-experts/deploy-your-app-to-firebase-in-seconds-b3a9a37dff47>

## Firebase URL

<https://acme-photography.firebaseapp.com/>

## UA google code

```javascript
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-138415594-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-138415594-1');
</script>
```

## Universal Analytics GA3 migration to GA4

<https://www.optimizesmart.com/how-to-upgrade-to-google-analytics-4-ga4/#3-1-upgrade-to-ga4-if-you-currently-use-ga3>

<https://www.optimizesmart.com/introduction-to-google-analytics-apps-and-web-property/>