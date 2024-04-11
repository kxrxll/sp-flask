# This is a Synergy practical project

The goal is to creeate a server side application replying to client with autorisation. The project use official Flask tutorial: https://flask.palletsprojects.com/en/3.0.x/tutorial/

The application is made to create and store blog post for each authorised user.
Posts will be shown to any user.

## Instructions

1. Fork the project to your local machine.

2. Create and activate virtual envirenment from the project folder.

   ```bash
   $ python -m venv .venv
   ```

   ```bash
   $ .venv/bin/activate
   ```

3. Install Flask.

   ```bash
   $ pip install Flask
   ```

4. Initilize the Flask database.

   ```bash
   $ flask --app flaskr init-db
   ```

5. Run Flask production server.

   ```bash
   $ pip install waitress
   ```

   ```bash
   $ waitress-serve --call 'flaskr:create_app'
   ```

6. Run the application: http://0.0.0.0:8080
