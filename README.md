# electron-quick-start with electron-builder

This is a minimal Electron application based on the [Quick Start Guide](https://electronjs.org/docs/tutorial/quick-start) within the Electron documentation. It has built in electron-builder support so you don't have to worry about setting it all up.

**Use this app along with the [Electron API Demos](https://electronjs.org/#get-started) app for API code examples to help you get started.**

A basic Electron application needs just these files:

- `package.json` - Points to the app's main file and lists its details and dependencies.
- `main.js` - Starts the app and creates a browser window to render HTML. This is the app's **main process**.
- `index.html` - A web page to render. This is the app's **renderer process**.

You can learn more about each of these components within the [Quick Start Guide](https://electronjs.org/docs/tutorial/quick-start).

## To Use

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/sethvandebrooke/electron-quick-start
# Go into the repository
cd electron-quick-start
# Install dependencies
npm install
# Run the app
npm start

# package the app for building
npm run pack
# build the app and installer (default platform is windows, change default in package.json)
npm run build-mac

# build the app and installer for windows
npm run build-win
# build the app and installer for mac
npm run build-mac
# build the app and installer for linux
npm run build-lin

# clean node modules (does not work on windows)
npm run clean
# clean and reinstall node modules
npm run reinstall
# reinstall node modules and build app
npm run rebuild
```

## Application configurations
- Update your icon by replacing icon.ico in the build dir (note: the icon should be icon.icns for mac)
- Update your application information by changing the appId, productName, and general package information (name, version, description etc...) in the package.json file.

Note: If you're using Linux Bash for Windows, [see this guide](https://www.howtogeek.com/261575/how-to-run-graphical-linux-desktop-applications-from-windows-10s-bash-shell/) or use `node` from the command prompt.

## Resources for Learning Electron

- [electronjs.org/docs](https://electronjs.org/docs) - all of Electron's documentation
- [electronjs.org/community#boilerplates](https://electronjs.org/community#boilerplates) - sample starter apps created by the community
- [electron/electron-quick-start](https://github.com/electron/electron-quick-start) - a very basic starter Electron app
- [electron/simple-samples](https://github.com/electron/simple-samples) - small applications with ideas for taking them further
- [electron/electron-api-demos](https://github.com/electron/electron-api-demos) - an Electron app that teaches you how to use Electron
- [hokein/electron-sample-apps](https://github.com/hokein/electron-sample-apps) - small demo apps for the various Electron APIs

## Resources for Learning Electron-Builder
- [electron-builder](https://github.com/electron-userland/electron-builder)

## License

[CC0 1.0 (Public Domain)](LICENSE.md)
