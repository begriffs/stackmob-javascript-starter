## Using the Starter Project

1. [Download](https://github.com/stackmob/stackmob-javascript-starter/archive/master.zip) this code (or clone with git)
2. Edit app.js and add your public key to the `StackMob.init(..)` block:

    ```js
    StackMob.init({
      publicKey: "your-key-goes-here",
      apiVersion: 0
    });
    ```

3. Open `index.html` in a web browser. (It works fine even when
   served as `file://`)
4. After creating a few objects in the app, view the data in StackMob's
[Object Browser](https://dashboard.stackmob.com/data/browser).

For more help getting started see these resources

* [StackMob Getting Started](https://developer.stackmob.com/start)
* [Developer Center](https://developer.stackmob.com/js-sdk)
* [Developer Guide](https://developer.stackmob.com/js-sdk/developer-guide)
* [JavaScript SDK forum](http://support.stackmob.com/forums/22281771-JavaScript-Questions)
