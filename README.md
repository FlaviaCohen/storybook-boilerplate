# Storybook boilerplate

´´´
npx create-react-app name
´´´
´´´
npm uninstall —save react-scripts
´´´

Delete public folder

Delete logo from /App

Replace the content of index.js with ‘export * from “./App”’

´´´
npm install —save prop-types
´´´
´´´
npm install --save-dev storybook-css-modules-preset
´´´
´´´
npm install --save @storybook/addon-postcss
´´´
´´´
npx sb init
´´´

Replace "start" and "build" commands from package.json with "storybook" and "build-storybook" commands.
Delete "test" and "eject" commands from package.json.

´´´
npm start
´´´
