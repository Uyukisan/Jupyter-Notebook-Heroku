# Jupyter-Notebook-Heroku

1. Generate a password.(password:hello,123)

  ```
ipython -c 'from notebook.auth import passwd; passwd()'
  ```

  <img width="572" alt="Generate a password" src="https://user-images.githubusercontent.com/93468245/178713003-7d8dbab6-c5d0-4210-8d83-1d2d472436d1.png">

2. Copy the generated password.

  ```
argon2:$argon2id$v=19$m=10240,t=10,p=8$qgz+iCO2d+VH294etutvkQ$22TmcJL1NMtieNlOs12PzQT/BsQr4sXpmI0oseTpZIQ
  ```

3. Click the button to deploy to heroku.

   [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new?template=https://github.com/Uyukisan/Jupyter-Notebook-Heroku)

4. Enter the new app name and the generated password.

  <img width="646" alt="Enter the new app name and the generated password" src="https://user-images.githubusercontent.com/93468245/178729558-11e8e457-6af7-4d9f-b828-c7ff3c7780a0.png">

5. Deploy app.

     Demo：[Jupyter-Notebook-Heroku](https://jnotedemo.stackblog.eu.org)

     Password：hello,123

# Screenshots

<img width="733" alt="Screenshot 1" src="https://user-images.githubusercontent.com/93468245/178716787-b3485298-4700-4aef-8993-0d35758d998b.png">
<img width="955" alt="Screenshot 2" src="https://user-images.githubusercontent.com/93468245/178716803-aa349ec9-d47d-4779-8a3f-146dfa36a182.png">
<img width="947" alt="Screenshot 3" src="https://user-images.githubusercontent.com/93468245/178716830-2755424a-1349-4ee7-932b-d4f6eb7cf41a.png">

# Thanks.
[Jupyter-Notebook-Server-Heroku](https://github.com/developeranaz/Jupyter-Notebook-Server-Heroku)
