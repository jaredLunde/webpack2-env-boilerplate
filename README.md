# webpack2-env-boilerplate
## A boilerplate for creating applications with Webpack 2.2 and Babel w/ babel-preset-env.

This package includes everything you need to start building a package with
Webpack 2.


### package.json
Here you'll find a list of devDependencies for creating this type of
application, however, they are listed under 'dependencies' since I use this
project as a grouped devDependency in my personal projects.


### package.json.tpl
Here is an example of what your package.json might look like, were you to
use this package as a devDependency. Should you choose to do so, you can
install this package with the command:

`npm install --save-dev webpack2-env-boilerplate`


### webpack.config.dev.js
This is an example of a basic development webpack configuration file for this
type of package.


### webpack.config.js
This is an example of a basic distribution webpack configuration file for this
type of package. Commented out are examples of implementing http2
aggressive code splitting.


### .babelrc
This is an example of a basic Babel 6 configuration utilizing babel-preset-env.


### /src
This is where an example index file is located and where your package source
code would be placed.
