# React-Native demo app
This is a toy app to try out react-native

## Preliminary
### node.js & npm
If you don't have node, and npm installed, follow these steps.

- NVM
use cURL: `curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.31.0/install.sh | bash`
or use Wget: `wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.31.0/install.sh | bash`

- node.js
Install node.js: `nvm install v5.7.0`

- watchman
`brew install watchman`

- Xcode
Go to app store and download Xcode, the full version.

- React-native
Install the react-native cli tool: `npm install -g react-native-cli`

Now you are good to go.

## To try this app
Clone this app to your local machine, go to the root directory of the repo, then:
- run `react-native run-ios`.
- Or you can open up xcode, and navigate to the `./ios` directory under root dir of this repo, and open the `.xcodeproj` file.

## A side note
React-native compiles to native codes. Here's a good read about it from FB

https://code.facebook.com/posts/1014532261909640/react-native-bringing-modern-web-techniques-to-mobile/

To further prove you that, you can
- open this project in xcode
- click the triangle to run it.
- from xcode (not the simulator), select `Debug\View Debugging\Capture View Hierachy`

Your will be able to see the native views that get compiles into.

## To test its API interactions
- This uses API to a UK database. So searc London, you will get result.
- To try the geolocation, from the simulator menu, select `Debug\Location\Custom Location`, and enter lat: 55.02, long: -1.42.

## A few tutorials to get started
- https://facebook.github.io/react-native/docs/tutorial.html
- https://www.raywenderlich.com/99473/introducing-react-native-building-apps-javascript (The one I follow for this project)
- https://www.toptal.com/ios/cold-dive-into-react-native-a-beginners-tutorial
