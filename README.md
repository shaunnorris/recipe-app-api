# recipe-app-api
Recipe app api source code

## securing env variables for passwords etc.
create a .env file in the root of your project as follows:
.env is ignored in .gitignore by default so you won't upload to github
## .env sample
```
SECRET_KEY=[some random secure 50 char string]
DB_NAME=[yours goes here]
DB_USER=[yours goes here]
DB_PASS=[yours goes here]
DB_SERVICE=[yours goes here]
DB_PORT=5432
```

#Github actions

Setup GH actions to run python tests - look in .github/workflows/django.yml
in order to pass in env variables, using GH secrets
