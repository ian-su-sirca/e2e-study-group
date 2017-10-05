# Redux TodoMVC Example - adapted for End-to-end testing study group

See the [original README](https://github.com/ian-su-sirca/redux/tree/master/examples/todomvc) for documentation of the example app.

## Running the application locally

### `npm install`

Installs project dependancies

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

## End-to-end testing

### Local testing

To run end-to-end testing locally, first run the app in development mode (see above), then execute the following:

```
cd tests
npm install
npm run test
```

### Testing on Browserstack

First, obtain your browserstack username and access key from [browserstack settings](https://www.browserstack.com/accounts/settings), and replace the values in `tests/browserstack_profile`.

```
cd tests
. browserstack_profile
CONFIGURATION=browserstack npm run test
```
