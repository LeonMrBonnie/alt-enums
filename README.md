# alt:V Enums
**This is not an official package by the altMP team, this is made by the community!**

This package contains a few useful enums to be used with TypeScript in alt:V.

## How To Use

Firstly, install the package as a dev dependency by running:
```
npm install -D alt-enums
```
Next make sure to add this package to your `types` or `typeRoots` in your `tsconfig.json`.
Now you can just import the package and use the enums:
```ts
import * as AltEnums from "alt-enums";
console.log(AltEnums.WeaponModel.APPistol);
```
This gets transpiled to:
```js
"use strict";
exports.__esModule = true;
console.log(584646201 /* APPistol */);
```

## Contributing

If there are any helpful enums that could be added feel free to create an issue or even make a pull request.

## Credits

Thanks to all Wiki contributors for the enums.<br>
Thanks to Lhoerion for helping me with TypeScript stuff and letting me yoink his TSConfig.