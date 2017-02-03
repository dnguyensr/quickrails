# quickrails

This repo is meant for the quick deployment of a rails 5 app for the purposes of learning, testing, and trying out different gems.

## Getting started
* Clone repo
* Pull desired branches (List in current branches section)
* Bundle
* Update remote git url with:
    git remote seturl https://github.com/USERNAME/OTHERREPOSITORY.git
* Create .env file in the root directory and populate with any required environment variables

## General Configuration
    * The dotenv-rails gem is included in all branches which loads environment variables from the .env files in the root directory of the project. As mentioned in the getting started section, a .env file needs to be created in the root directory and populated with any required environment variables.
    * A default home controller and home view are included as well as routing root to home#index.

## Current branches
### Devise

## Future branches
  * User model with Devise gem
  * Post MVC
  * Testing with RSpec
  * Coverage with Coveralls
  * CI/CD with Travis-CI to Heroku/AWS
  * Facebook, Twitter login with Devise/oauth

# Other plans
  * Quick deploy of Rails API-only app
