# Industry news

## September 2018

### Web

- [The BA data breach - hack][ba news]
- Chrome 69

  - **Controversy**: `www` is now considered a _trivial_ subdomain. [Source][google www].

  - Web Locks API

  ```javascript
  navigator.locks.request('network_sync_lock', async lock => {
    // The lock has been acquired.
    await do_something();
    await do_something_else();
    // Now the lock will be released.
  });
  ```

  - Pure [CSS Scroll snap][scroll snap]
  - Display cutouts

  ![Display cutouts][display cutouts]

### Mobile

- New iPhones! Without [3.5mm dongle][no dongles] included! (extra $9)
  - XR ($749)
  - XS Max ($1,099)
    > Shouldn't this named S?
  - XS ($999)

![iPhone XS][iphone xs]

### IoT

- Apple Watch 4 with FDA clearance

![my heart rate][heart rate warning]

- Raspberry Pi pocket projector. Around $120 to build. More info on the project [here][rpi pocket projector project].

![rpi pocket projector demo][rpi pocket projector demo]

### Others

- FramerX: we've been given Beta access!
  - Store
    ![Framer X Store][framer x store]
  - React
    ![Framer X React][framer x react]

[no dongles]: https://www.theverge.com/2018/9/13/17852184/iphone-xs-headphone-jack-adapter-apple-event-2018
[ba news]: https://www.ft.com/content/e72a67c0-b5a8-11e8-b3ef-799c8613f4a1
[heart rate warning]: https://i.imgur.com/GUXUSZY.png
[iphone xs]: https://cdn.vox-cdn.com/thumbor/m6G38PgoX2sC5CRfsvKD7URLQVk=/0x0:2040x1360/1820x1213/filters:focal(913x439:1239x765):format(webp)/cdn.vox-cdn.com/uploads/chorus_image/image/61387055/Image_from_iOS__2_.0.jpg
[scroll snap]: https://developers.google.com/web/updates/2018/09/nic69#scroll-snap
[display cutouts]: https://developers.google.com/web/updates/images/2018/09/notch-extra-margin.png
[framer x react]: https://i.imgur.com/b4AVqC2.jpg
[framer x store]: https://i.imgur.com/UYIr7pU.png
[rpi pocket projector project]: https://www.mickmake.com/products/piprojector-1-x-series-documentation
[rpi pocket projector demo]: https://img.youtube.com/vi/RxQ4GFfPJFo/maxresdefault.jpg
[google www]: https://bugs.chromium.org/p/chromium/issues/detail?id=881410
