# Thunder CMS
Thunder in recipes

## Installation
1. Install [Docker](https://docs.docker.com/get-docker/)
2. Install ddev `brew install ddev/ddev/ddev`
3. Clone the repository `git clone git@github.com:thunder/thunder-cms.git`
4. Go to the project directory `cd thunder-cms`
5. Start the project `ddev start`
6. Install dependencies `ddev composer install`
7. Install the project `ddev drush site:install recipes/thunder_cms`
8. Open the project in the browser `ddev drush uli`

## Update repositories in composer.json
When adding new recipes or modules, the composer.json has to be updated:

    ddev setup-repositories
