## Tech Stack

- Ruby 3.x
- Ruby on Rails 7.x
- PostgreSQL 9.5
- Esbuild
- Twitter Bootstrap 5
- Stripe
- Gem: 
    -  [devise](https://github.com/plataformatec/devise) | Authentication
    -  [pg](https://github.com/ged/ruby-pg) | PostgreSQL library for Ruby

## Installation

### Requirements

Before you get started, the following needs to be installed:
  * **Ruby**. Version 3.1.0 is currently used and we don't guarantee everything works with other versions. If you need multiple versions of Ruby, [rbenv](https://rbenv.org) is recommended.
  * [**RubyGems**](http://rubygems.org/)
  * **Bundler**: `gem install bundler`
  * [**Git**](http://help.github.com/git-installation-redirect)
  * **A database**. Only PostgreSQL 9.5 has been tested, so we give no guarantees that other databases (e.g. MySQL) work. If you're using OS X and have Homebrew installed, install it with `brew install postgresql`
  
### Setting up the development environment

1. Get the code. Clone this git repository:

  ```bash
  git clone git://github.com/wd1/waro_shop.git
  cd waro_shop
  ```

2. Install the required gems by running the following command in the project root directory:

  ```bash
  bundle install
  ```

3. Setup the database:

  ```bash
  bundle exec rails db:setup
  ```

4. Start the development server:

  ```bash
  bin/dev
  ```
