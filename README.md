
```
    <link rel="icon" href="//favicon.CostGuard.io/favicon.ico" sizes="32x32">
    <meta name="apple-mobile-web-app-title" content="CostGuard">
    <meta name="apple-mobile-web-app-capable" content="yes">
    <link rel="apple-touch-icon" href="//favicon.CostGuard.io/apple-touch-icon.png" sizes="180x180">
    <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent" />
    <link rel="manifest" href="//favicon.CostGuard.io/manifest.webmanifest">
    <meta name="theme-color" content="#36A2EB">
    <meta name="msapplication-TileColor" content="#36A2EB">
```

```
document.addEventListener('DOMContentLoaded', () => {
    // Select all manage buttons and their corresponding dropdown menus

    if ('serviceWorker' in navigator) {
        navigator.serviceWorker.register('/js/service-worker.js');
    }

});
```
