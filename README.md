# Ring


This fork, created by [TrinityHades](https://github.com/TrinityHades), adds **HomeKit Secure Video (HKSV)** support to Ring cameras, allowing users to store camera recordings securely in iCloud and view them through the Apple Home app. This provides many of the benefits of Ring's premium subscription without the cost, along with deeper integration into the Apple ecosystem.

> [!WARNING]
> **Please be aware of the following before using this plugin:**
> - Using this plugin may violate Ring's Terms of Service — use it at your own risk.
> - Some features may not work as expected due to limitations in Ring's API or future changes made by Ring.
> - Even though HomeKit Secure Video is end-to-end encrypted, your video data is still transmitted through Ring's servers. Be sure to understand the privacy implications before using this plugin.

## Troubleshooting Issues

If you are having issues, please look for related articles in the [wiki](https://github.com/dgreif/ring/wiki) and search existing [Issues](https://github.com/dgreif/ring/issues) before opening a new Issue/Discussion

## `ring-client-api`

The [ring-client-api](./packages/ring-client-api/) is a TypeScript package designed to be used by developers to create your own apps/programs which interact with Rings api

## `homebridge-ring`

[homebridge-ring](./packages/homebridge-ring/) allows users to easily integrate Ring products into Apple HomeKit via [homebridge](https://homebridge.io/).


## Examples

See the [examples directory](./packages/examples/) for examples using the `ring-client-api`. For a full project example, see https://github.com/dgreif/ring-client-example

## Credits

I'd like to give a big thanks to a number developers who have put a lot of hard work into analyzing the
Ring api and building similar libraries which were extremely valuable in my creation of this project. Thank you all
for your hard work!

- @davglass - https://github.com/davglass/doorbot - The original node project that proved we can interact with Ring's api
- @jimhigson - https://github.com/jimhigson/ring-api - A promisified api for Ring's original line of products
- @tchellomello - https://github.com/tchellomello/python-ring-doorbell - A python api which is widely used for Ring integrations
- @mrose17 - https://github.com/homespun/homebridge-platform-ring-video-doorbell - The original Ring camera homebridge plugin
- @codahq - Thanks for all your help debugging the Ring api
- @joeyberkovitz - Great discovery work on the Ring Alarm websockets api
