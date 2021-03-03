# curso-webpack-react

Install react: npm i react react-dom -S

Install Webpack: npm i webpack webpack-cli webpack-dev-server -D

Execute Webpack: npx webpack

Activate development mode Webpack: npx webpack --mode development

Activate production mode Webpack: npx webpack --mode production

Activate production mode Webpack and configuration file: npx webpack --mode production --config webpack.config.js

Install Babel: npm i @babel/core @babel/preset-env @babel/preset-react babel-loader -D

Plug HTML Webpack: npm i html-loader html-webpack-plugin -D

Plug CSS Webpack: npm i mini-css-extract-plugin css-loader css-loader style-loader sass sass-loader -D

Plug CSS Stylus Webpack: npm i stylus-loader -D

Get font from Google fonts: http://google-webfonts-helper.herokuapp.com/fonts/ubuntu?subsets=cyrillic,latin

Move files to dist file: npm i url-loader file-loader -D

Copy Webpack Plugin: npm i copy-webpack-plugin -D

Minimizer CSS Webpack: npm i css-minimizer-webpack-plugin terser-webpack-plugin clean-webpack-plugin -D

Variables de entorno: npm i dotenv-webpack -D

Stylus: npm i stylus -D

Webpack Bundle Analyzer: npm i webpack-bundle-analyzer -D

Analyzer:

- npx webpack --profile --json > stats.json
- npx webpack-bundle-analyzer stats.json
