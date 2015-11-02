# Rails React

The purpose of this project is to find a way to load a [React](https://github.com/facebook/react) application in an existing [Rails](https://github.com/rails/rails) application with as little code as possible.

Inspired by [Kevin Old](https://github.com/kevinold)'s [configure webpack-dev-server and react-hot-loader with Ruby on Rails](http://kevinold.com/2015/02/04/configure-webpack-dev-server-and-react-hot-loader-with-ruby-on-rails.html) post.

## Usage

Install packages:

    $ bundle && npm install

Create Rails database:

    $ rake db:setup
    
Start server:

    $ foreman start -f Procfile.dev
    
Open [http://localhost:3000]().