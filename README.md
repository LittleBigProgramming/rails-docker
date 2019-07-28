## Docker Rails Template

### In order to generate the Rails skeleton

Run the following command to generate the Rails skeleton using postgresql without dependencies.
`docker-compose run web rails new . --force --no-deps --database=postgresql`

Once this has been ran and the Gemfile has been run `docker-compose build
` to build the image again. 
