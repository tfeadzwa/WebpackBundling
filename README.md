# WebpackBundling
Webpack Vanilla JS Starter: A webpack template for vanilla JavaScript projects. Learn how to bundle, optimize, and hot reload your code

Here is a possible readme of the recommendations of what to include in the project when bundling with webpack:

# Webpack Project Template

This is a simple and easy-to-use template for building and bundling web projects with webpack. Webpack is a module bundler that can transform, bundle, or package just about any resource or asset. This template follows some of the best practices for optimizing webpack builds, such as:

- Minification: This technique removes unnecessary elements such as white spaces, comments, and line breaks from code without affecting its functionality. This reduces the size of the output files and improves the performance of the web application. This template uses the [TerserWebpackPlugin](^1^) to minify JavaScript files and the [CssMinimizerWebpackPlugin](^2^) to minify CSS files.
- Compression: This technique compresses the output files to reduce their size even further. This reduces the bandwidth usage and improves the loading speed of the web application. This template uses the [CompressionWebpackPlugin](^3^) to compress the output files using gzip or brotli algorithms.
- Code splitting: This technique splits the code into smaller chunks that can be loaded on demand or in parallel. This improves the initial loading time and the user experience of the web application. This template uses the [SplitChunksPlugin](^4^) to split the code into common chunks and the [HtmlWebpackPlugin](^5^) to inject the chunks into the HTML file.
- Tree shaking: This technique eliminates unused or unreachable code from the output files. This reduces the size of the output files and avoids loading unnecessary code. This template uses the [ModuleConcatenationPlugin] to enable tree shaking for ES6 modules.

## How to use this template

To use this template, you need to have Node.js and npm installed on your system. You can download them from [here]. Then, follow these steps:

- Clone or download this repository to your local machine.
- Navigate to the project folder and run `npm install` to install the dependencies.
- Run `npm run dev` to start the development server and open the web application in your browser.
- Run `npm run build` to build the production version of the web application and output the files to the `dist` folder.

## How to customize this template

You can customize this template by modifying the `webpack.config.js` file in the project folder. This file contains the configuration options for webpack. You can change the entry points, output options, loaders, plugins, and other settings according to your needs. You can also add new loaders and plugins to support different types of resources or assets. For more information, please refer to the [webpack documentation].

Source: Conversation with Bing, 11/14/2023
(1) Build Performance | webpack. https://webpack.js.org/guides/build-performance/.
(2) Production | webpack. https://webpack.js.org/guides/production/.
(3) Optimizing the build process using Webpack - OpenReplay. https://blog.openreplay.com/optimizing-the-build-process-with-webpack/.
(4) GitHub - xiaoyann/webpack-best-practice: Webpack 最佳实践，理解每个关键点 .... https://github.com/xiaoyann/webpack-best-practice.
(5) Introduction to webpack: Entry, Output, Loaders, and Plugins - Medium. https://medium.com/swlh/how-make-better-optimization-with-webpack-and-splitchunk-in-the-production-96bd273c56ca.
