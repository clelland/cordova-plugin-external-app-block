net.iclelland.external-app-block
================================

Simple Cordova plugin to stop Android Cordova apps from launching other applications through URL navigation.

## Use

Just install it; the plugin will intercept and block navigation to URLs which are not covered by the Cordova Whitelist. This blocks the default Cordova behaviour, which is to launch external applications for links to sms:, tel:, geo:, mailto:, market:, and intent: URLs, among others.

This plugin only affects Android Cordova applications. It does nothing when installed in other platforms.

## Installation

### Through the Cordova plugin registry

    cordova plugin add net.iclelland.external-app-block

### Through GitHub

    cordova plugin add https://github.com/clelland/cordova-plugin-external-app-block.git

### From local source

    git clone https://github.com/clelland/cordova-plugin-external-app-block.git
    cd <path to cordova project>
    cordova plugin add <path to plugin>

## Removal

    cordova plugin rm net.iclelland.external-app-block

## License

[Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0.html)
