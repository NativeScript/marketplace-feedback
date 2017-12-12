## How to Show Your App Template to Marketplace?

* Do publish your app template to npm (https://www.npmjs.com/) using **tns-template-[custom-template-name-goes-here]** format for the npm package name.

* Do provide a screenshot preview to be used in a future NativeScript Marketplace integration under **tools/assets/marketplace.png** in your app template folder structure.  
> NOTE: Check [tools/postinstall.js](https://github.com/NativeScript/template-master-detail/blob/master/tools/postinstall.js) that implements a mechanism for removing the "tools" infrastructure folder from the generated app.

* Do provide correct `repository` property value in the root package.json file of your app template (see the "Package.json guidelines" section in our [App Template Style Guide](https://github.com/NativeScript/nativescript-starter-kits-utils/blob/master/docs/style-guide-app-template-ng.md#packagejson-guidelines)).

* Make sure your template comply with the [App Template Style Guide](https://github.com/NativeScript/nativescript-starter-kits-utils/blob/master/docs/style-guide-app-template-ng.md)

* Apply by sending an email with link to your template's repository to nativescriptplugins@progress.com!