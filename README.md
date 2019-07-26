# README

# Project: Bare Metal Forms and Helpers.

  A simple app that displays a user form, witch can save and edit a user with a `username` ,`email` and `password` attributes.

  It can also display errors if user information are not valid, this app created by ruby on rails using the `#form_for` method. 

## prerequisite
1. Git.
2. Code editor.
3. Code linter.
4. Rails.
5. Browser. 

## How to run the program
1. Open the terminal.

2. Enter `git clone https://github.com/othman-19/re-former`.

3. Navigate to the cloned repository.

4. In the terminal cd into re-former.

5. Run the rails server by typing `rails server` in the terminal.

6. Open a browser page and type this url `http://localhost:3000/users/new`.

7. If you get an error message on the browser like this: "Migrations are pending. To resolve this issue, run: bin/rails db:migrate RAILS_ENV=development", just got to the terminal and run: `bin/rails db:migrate RAILS_ENV=development` then refresh your page.

7. Enter a valid information and submit to create a new user.

8. Open a new browser tab (or page) and type this url `http://localhost:3000/users/1/edit` to edit the user with id = 1.

9. You can change the `id` number in `http://localhost:3000/users/id/edit` to edit another user witch have that `id` number.

## Contributor(s)
1. [Othamane Naamani](https://github.com/othman-19/).
2. [Molnar Emese](https://github.com/Mesi21).