# Learning Rails

This is a simple Rails application which provides a tiny blog - CRUD with articles and comments.

- Follow this [instructions](http://guides.rubyonrails.org/getting_started.html#installing-rails) to install and configure Ruby, Rails and SQLite.

- Download this repo and navigate into it's main directory. On the command line, start the internal web server:
`$ bin/rails server`

- Run the migrations:
`$ bin/rails db:migrate`

- Application will be available at: 
`http://localhost:3000`

- This application uses HTTP Basic authentication, so you will be asked for credentials when you try to create/update/delete an article. Provide following credentials:
```
user: admin  
password: secret
```