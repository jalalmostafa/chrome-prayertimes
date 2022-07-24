# Prayer Times

<span>

<img src="https://raw.githubusercontent.com/jalalmostafa/chrome-prayertimes/master/web_store/small-mosque.png" />

<a href="https://chrome.google.com/webstore/detail/prayer-times/ipkhkglhpmngdkgclngmlpkekkpplbgm">
<img alt="badge-chrome" src="https://storage.googleapis.com/web-dev-uploads/image/WlD8wC6g8khYWPJUsQceQkhXSlv1/UV4C4ybeBTsZt43U4xis.png" />
</a>
<a href="https://microsoftedge.microsoft.com/addons/detail/jdnolinjgdhocachcbfcalljgfmceapb">
<img alt="badge-edge" src="https://winaero.com/blog/wp-content/uploads/2019/11/Edge-Stable-Fluent-Big-256-Icon.png" width="64" height="64"/>
</a>

</span>

In-Browser Prayer Times and Notifications for [Google Chrome](https://chrome.google.com/webstore/detail/prayer-times/ipkhkglhpmngdkgclngmlpkekkpplbgm) and [Microsoft Edge Chromium](https://microsoftedge.microsoft.com/addons/detail/jdnolinjgdhocachcbfcalljgfmceapb)

Features:

- In-Browser Notifications
- Choose what you want to get notified for
- Choose your location manually
- A.M./P.M. and 24Hours format

By using this extension, you agree to the [Privacy Policy](https://jalalmostafa.github.io/prayertimes/PrivacyPolicy.html)

Support Prayer Times by buying me a coffee!

<a href="https://www.buymeacoffee.com/jalalmostafa"><img src="https://img.buymeacoffee.com/button-api/?text=Buy me a coffee&emoji=&slug=jalalmostafa&button_colour=FFDD00&font_colour=000000&font_family=Cookie&outline_colour=000000&coffee_colour=ffffff" /></a>

## How to Build

Technology stack: React - TypeScript - Webpack

- Create `.env` file in root directory and set the following properties:

```bash
# Google Geolocation and Maps APIs
GMAPS_API_KEY=<your_google_maps_api_key_here>
```

- `yarn install`
- `yarn start`

## Credits

- [`app/src/common/prayer-times.ts`](https://github.com/jalalmostafa/chrome-prayertimes/blob/master/app/src/common/prayer-times.ts) is a a fork of Hamid Zarrabi-Zadeh's [`prayertimes.js`](http://praytimes.org/code/v2/js/PrayTimes.js) license under GNU LGPL v3.0
- Icons made by [Freepik](https://www.flaticon.com/authors/freepik) from [www.flaticon.com](www.flaticon.com)
