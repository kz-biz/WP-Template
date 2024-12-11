# WordPress Template


<!-- Image -->
<!-- ![](./screenshot.png) -->
[Website](https://google.com)

# Local Development URL 
 - localhost:8888 (MAMP)

 - phpmyadmin: localhost:8888/phpmyadmin


# Installation
```
npm install
```

# How to run the project
```
npm run format
npm run watch
npm run build (Minify CSS & JS)
```

# create file 
### postcss.config.js
```
module.exports = {
  plugins: [
    require('cssnano')({
      preset: 'default',
    }),
  ],
};
```

# Installation Details
```
// 以下コマンド実行しなくてOK
npm init 
npm install sass 
npm install postcss postcss-cli cssnano --save-dev // css minify
npm install terser --save-dev // js minify
npm install chokidar-cli --save-dev // watch files for JS (terser doesn't have watch functionality)
npm install concurrently --save-dev // run multiple commands
```