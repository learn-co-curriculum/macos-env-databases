# Installing Databases on macOS

## Install SQLite

You’ll be using a couple of different databases as you move through the web
development track. The default database that Ruby on Rails uses is SQLite.

### Action Item

1. Open the "Terminal" application using "Spotlight Search"
2. Type `brew install sqlite` and press `<Enter>`

### Check Your Work

If you were able to run those commands without any issues, continue below.

## Install Postgres

We also frequently see that students want to deploy their apps to the hosting
service Heroku. To do this, though, you will need a different relational
database management system called PostgreSQL.

### Action Item

1. Open the "Terminal" application using "Spotlight Search"
2. Type `brew install postgres` and press `<Enter>`
3. Type `brew services start postgresql` and press `<Enter>`
4. Type `gem install pg` and press `<Enter>`

### Check Your Work

<iframe width="560" height="315" src="https://www.youtube.com/embed/Hv3CYjbNVmI" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

If you were able to run those commands without any issues, continue to the next
lesson, **Configuring GitHub and Flatiron Student Portal on macOS**.
