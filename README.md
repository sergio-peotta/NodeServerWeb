# NodeServerWeb

git push heroku

heroku [open](https://limitless-hamlet-92464.herokuapp.com/)

# per aggiungere il remote a git
```git remote add heroku https://git.heroku.com/[appmane].git```

# per rimuovere un remote da git
```git remote rm heroku```

# per la lista
```git remote -v```

Update: If you don’t have your heroku remote created, do this:
```
heroku create
git remote set-url heroku git@heroku.com:[appname].git
```

``` git push heroku master ```
