# API Rest completa

Ruby on Rails 6 course as API showing authentication via [devise_token_auth](https://github.com/lynndylanhurley/devise_token_auth).

<table>
  <tr>
    <td>Ruby version</td>
    <td>
      3.0.3
    </td>
  </tr>
  <tr>
    <td>Rails version</td>
    <td>
      6.1.5
    </td>
  </tr>
  <tr>
    <td>Database</td>
    <td>
      PostgreSQL
    </td>
  </tr>
</table>

## Configuration

```bash
# installation of dependencies
bundle install

# creation of database and tables
rails db:create
rails db:migrate
rails db:migrate RAILS_ENV=test

# run the project
rails s
```
## Tests

![Tests](https://github.com/peimelo/blog_api/actions/workflows/ruby.yml/badge.svg)

To run the tests:

```bash
bundle exec rspec
```
## Documentation

Para usar com exito, faz parte voce criar uma nova master key.
apague o arquivo credentials.yml.enc em config
abra o terminal e digite, caso esteja usando vs code
EDITOR="code --wait" rails credentials:edit

