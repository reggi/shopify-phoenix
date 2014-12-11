Here's a proof of concept for getting a [phoenix release](https://github.com/csaunders/phoenix/releases) running and installing globally with NPM.

```
thomas@workstation:shopify-phoenix$ npm i -g /Users/thomas/Desktop/shopify-phoenix 
npm info it worked if it ends with ok
npm info using npm@1.4.28
npm info using node@v0.10.32
npm info prepublish shopify-phoenix@0.0.3
npm info install shopify-phoenix@0.0.3 into /Users/thomas/.nvm/v0.10.32/lib
npm info installOne shopify-phoenix@0.0.3
npm info preinstall shopify-phoenix@0.0.3
npm info build /Users/thomas/.nvm/v0.10.32/lib/node_modules/shopify-phoenix
npm info linkStuff shopify-phoenix@0.0.3
/Users/thomas/.nvm/v0.10.32/bin/theme-configure -> /Users/thomas/.nvm/v0.10.32/lib/node_modules/shopify-phoenix/theme-configure
/Users/thomas/.nvm/v0.10.32/bin/theme-manipulate -> /Users/thomas/.nvm/v0.10.32/lib/node_modules/shopify-phoenix/theme-manipulate
/Users/thomas/.nvm/v0.10.32/bin/theme-watch -> /Users/thomas/.nvm/v0.10.32/lib/node_modules/shopify-phoenix/theme-watch
npm info install shopify-phoenix@0.0.3
npm info postinstall shopify-phoenix@0.0.3
shopify-phoenix@0.0.3 /Users/thomas/.nvm/v0.10.32/lib/node_modules/shopify-phoenix
npm info ok 
thomas@workstation:shopify-phoenix$ theme-watch
Waiting for local changes
^Cthomas@workstation:shopify-phoenix$ which theme-watch
/Users/thomas/.nvm/v0.10.32/bin/theme-watch
```