# Went to Bali, Mhahaha

#### Rails E-Commerce and AJAX Independent Project 7/14/2017

#### By Monique St. Laurent

This is a ecommerce website, in which AJAX has been added to allow users to:
  * Add products to their shopping cart from the index page, and see the number of items updated in the navbar.
  * To click on a product and show/hide the product details.
  * To remove items from the shopping cart without a page reload, and see the updated item total and total price.

It has also been refactored in the following ways:
  * Ensure that users can't order a negative number of items.
  * Add flash messages for signing up, signing in and signing out.
  * Add product update and delete functionality for admins.
  * Add admin flash messages for adding, updating and deleting products.
  * Allow other than whole dollar amounts for admin product creation (for instance, 3.99).
  * Add product validations.
  * Add admin links to navbar, and on the product detail page so admins can easily add, update, and delete products.
  * Add a thorough README.

## Installation and Setup

1. Run:
*  `$ git clone https://github.com/moinstla/went-to-bali-mwahaha`
* `$ cd went-to-bali-mwahaha`
* `$ bundle install`
* `$ bundle exec rails db:setup`
* `$ bundle exec rails server`

2. Navigate to http://localhost:3000

* Provided admin credentials are: admin@admin.com, 123456

## Technologies Used
Ruby
Rails
Bundler
Postgres
RSpec
Javascript (ES6)
Jquery 3
HTML5
SASS
Bcrypt
AJAX

## License Information

MIT License

Copyright (c) 2017

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
