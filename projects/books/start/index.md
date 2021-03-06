# Books: Getting Started

## GitHub Classroom

We'll again use GitHub Classroom to distribute files and collect submissions. To begin this project:

1. [Click here](https://classroom.github.com/a/gj0uwP51) to go to the GitHub Classroom page for starting the assignment.
2. Click the green "Accept this assignment" button. This will create a GitHub repository for your project. Recall that a git repository is just a location where your code will be stored and which can be used to keep track of changes you make to your code over time.
3. Click on the link that follows "Your assignment has been created here", which will direct you to the GitHub repository page for your project. It may take a few seconds for GitHub to finish creating your repository.
4. Now, you should be looking at a GitHub repository titled uva-webapps/books-username, where username is your GitHub username. This will be the repository to which you will push all of your code while working on your project.
5. Submit the link to your project's GitHub repository below.

> This time, your git repository doesn't have a `gh-pages` branch, but a default `main` branch instead. This is because GitHub can't host websites created with Flask. For now, you'll just run your website locally, on your own computer. Later, you might choose to host your website online, for other people to see!

## PostgreSQL

For this project, you'll need to set up a PostgreSQL database to use with our
application. It's possible to set up PostgreSQL locally on your own computer,
but for this project, we'll use a database hosted by
[Heroku](https://www.heroku.com/), an online web hosting service.

1. Navigate to [https://www.heroku.com/](https://www.heroku.com/), and create
   an account if you don't already have one.
2. On Heroku's Dashboard, click "New" and choose "Create new app."
3. Give your app a name, and click "Create app."
4. On your app's "Overview" page, click the "Configure Add-ons" button.
5. In the "Add-ons" section of the page, type in and select "Heroku Postgres."
6. Choose the "Hobby Dev - Free" plan, which will give you access to a free
   PostgreSQL database that will support up to 10,000 rows of data. Click
   "Provision."
7. Now, click the "Heroku Postgres :: Database" link.
8. You should now be on your database's overview page. Click on "Settings", and
   then "View Credentials." This is the information you'll need to log into your
   database. You can access the database via
   [Adminer](https://adminer.cs50.net/), filling in the server (the "Host" in
   the credentials list), your username (the "User"), your password, and the
   name of the database, all of which you can find on the Heroku credentials
   page.
   At Adminer you can use "SQL opdracht"/"SQL command" to try out a query.

Alternatively, if you install
[PostgreSQL](https://www.postgresql.org/download/) on your own computer, you
should be able to run `psql URI` on the command line, where the `URI` is
the link provided in the Heroku credentials list.
