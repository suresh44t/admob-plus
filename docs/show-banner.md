---
id: show-banner
title: Showing Banner Ad
sidebar_label: Banner Ad
---

Banner ads are rectangular image or text ads that occupy a spot within an app's layout. They stay on screen while users are interacting with the app, and can refresh automatically after a certain period of time.

## Usage

```js
document.addEventListener('deviceready', () => {
  admob.banner.load({
    id: {
      // replace with your ad unit IDs
      android: 'ca-app-pub-xxx/yyy',
      ios: 'ca-app-pub-xxx/zzz',
    },
  }).then(() => admob.banner.show())
}, false)
```

## Events

### Load Event

Called when banner ad is loaded.

```js
document.addEventListener('admob.banner.load', () => {
  // handle event
})
```

### Load Fail Event

Called when banner ad request failed.

```js
document.addEventListener('admob.banner.load_fail', () => {
  // handle event
})
```

### Open Event

Called when user tap on the banner ad.

```js
document.addEventListener('admob.banner.open', () => {
  // handle event
})
```

### Exit Application Event

Called after Open Event, when a user click opens another app (such as the Google Play), backgrounding the current app.

```js
document.addEventListener('admob.banner.exit_app', () => {
  // handle event
})
```

### Close Event

When a user returns to the app after viewing an ad's destination URL, this method is invoked. Your app can use it to resume suspended activities or perform any other work necessary to make itself ready for interaction.

```js
document.addEventListener('admob.banner.close', () => {
  // handle event
})
```
