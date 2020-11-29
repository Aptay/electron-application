# electron-base-application

## To Use

You will need [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/ddubrava/electron-application
# Go into the repository
cd electron-application
# Install dependencies
npm install
# Run the app
npm start
```

## Make distributables

```bash
npm run make
```

Will make distributables for your application based on your Forge config and the parameters you pass in.

[Further information](https://www.electronforge.io/cli#make)

## Package application

```bash
npm run package
```

Will package your application into a platform specific format and put the result in a folder. Please note that this does not make a distributable format. To make proper distributables, please use the make command.

[Further information](https://www.electronforge.io/cli#make)
