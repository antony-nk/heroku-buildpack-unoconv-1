# heroku-buildpack-unoconv-1

Add the `heroku-buildpack-apt` buildpack to your project:
```
heroku buildpacks:add --index 1 https://github.com/heroku/heroku-buildpack-apt.git
```

Add this buildpack to your project:
```
heroku buildpacks:add --index 2 https://github.com/esperienzia/heroku-buildpack-unoconv-1.git
```

Create an `Aptfile` file in your project root with the following content only:
```
unoconv
```

Redeploy your project after committing the above file.
