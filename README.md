# Manual deployment with Heroku:

1. Select the project you want to deploy manually in heroku.
2. Install the dependencies and build for production.
3. Create a new repository with a simple web server listening on a port and serving a public folder.
4. Copy in the public folder the frontend application you want to serve (frontend bundle of step 2).
5. Intialize the repository with ```git init```.
6. Install globally the heroku CLI.
7. Go to your Heroku profile and create a new app.
8. Select the Heroku buildpack of your preference.
9. In the project, run the command ```heroku login```.
10. Execute the command ```heroku git:remote -a <project-name-heroku-repo>```.
11. Commit the changes with the web server and push it with git -> ```git push heroku master```.
12. It will automatically deploy the app and provide you the corresponding URL.

Cloud laboratory with manual deployment in Heroku URL -> https://cloud-laboratory-manual-heroku.herokuapp.com/
