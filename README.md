#Asana#

We found it tedious to use multiple web apps to manage our social media campaigns -- and the best ones charge money. Asana is a free, easy way to schedule our updates, get feedback, and keep track of our Klout analytics. Feel free to join in on the action!

**We plan to use:** 

* Facebook and Twitter Api
* Klout Api

## Installation

To use Asana in a Rails 3 application:

1. Require it in the Gemfile: `gem 'asana'`

2. Install it by running `bundle`.

3. Run `rails g asana` to copy an initializer, database migration and some CSS and image assets into your base application directory.

4. Edit `config/initializers/asana.rb` and include your application's Twitter and Facebook OAuth configuration.

5. Run `rake db:migrate` to create the user and login_account tables.


Some more detailed installation instructions can be found at [socialasana.com](http://socialasana.com)

## Contributors

* [Andrew Reedy](http://github.com/andrewreedy)
* [Jon James](http://github.com/jonjamz)
* You

#License#

Social Asana is released under the MIT License. See the LICENSE file for details.