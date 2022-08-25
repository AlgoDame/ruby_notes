#### Scaffold Rails API
- `rails new project-name --api`

#### Starting the development server
- `rails server`

#### Generating a model
- `rails g model Book title:string author:string`

#### Create database
- `rails db:create`

#### Run the migrations
- `rails db:migrate`

#### GraphQL endpoint
For crafting our GraphQL API, we will use the graphql-ruby gem. Open Gemfile and add the following dependency to it:
- `gem 'graphql', '1.11.6'` OR
- add gem via bundle in terminal `bundle add graphql --version="~> 1.9"` 

Then run the generator:
- `rails generate graphql:install`

#### Define a type using GraphQL
- `rails g graphql:object type-name`

**Note: `type-name` should match model name**


