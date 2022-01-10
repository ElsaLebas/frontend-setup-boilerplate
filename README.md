First clone this repository to your laptop. 
You must have [yarn](https://yarnpkg.com/lang/en/docs/install/) installed.

Make sure you have Node installed and you are using >=14.17.0

```bash
node -v
nvm install ^14.17
nvm use ^14.17
```

Then run 

```bash
rm -rf .git
yarn install
```

Make sure you have `./node_modules/.bin` in your `$PATH`! 
```bash
echo $PATH
```

This way you can run this:

```bash
eslint src
webpack-dev-server
```

Once a file has been updated in your text editor, you can run it with:

```bash
node src/index.js
```
