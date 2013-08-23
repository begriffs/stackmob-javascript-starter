## Using the Starter Project

1. [Download](https://github.com/stackmob/stackmob-javascript-starter/archive/master.zip) this code (or clone with git)
2. Edit app.js and add your public key to the `StackMob.init(..)` block:

    ```js
    StackMob.init({
      publicKey: "69dc7bbb-d143-427f-84a4-4e0b2f63c72d",
      apiVersion: 0
    });
    ```

3. Open `index.html`jjj in a web browser. (It works fine even when
   served as `file://`)
4. After creating a few objects in the app, view the data in StackMob's
[Object Browser](https://dashboard.stackmob.com/data/browser).

For more help getting started, see the
[Start](https://developer.stackmob.com/start)
page, or ask for help in the [JS SDK
forum](http://support.stackmob.com/forums/22281771-JavaScript-Questions).
