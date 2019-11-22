# Setup
1. Run `npm install` to install webpack from `package.json`. Since locally installing webpack saves executables into `node_modules/.bin`, you'll need to run webpack using the npm script `npm run build`. Some useful flags to consider adding to this invocation:
   * `-d`: runs Webpack in debug mode, which provides useful error messages to help you understand why Webpack isn't able to bundle your files.
   * `-w`: this is the 'watch' flag, and sets webpack to rerun its bundling process every time it detects changes in the source files.
2. Run `npm install -g live-server` to use the [Live Server](https://github.com/tapio/live-server) package to launch a simple development server that automatically refreshes when you make changes to a file.
3. Create your YouTube API and paste it in the `youtube.js` file under `config` folder. There's a `youtube.example.js` file there for reference.
4. 