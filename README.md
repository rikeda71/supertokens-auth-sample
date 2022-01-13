# supertokens-auth-sample

sample project for supertokens

## supertokens ?

[supertokens](https://github.com/supertokens) is open source authorization/authentication api instead of Firebase Auth, AWS Cognito or Auth0.

## usage

```shell
$ docker-compose up -d  # wait a minite
# signup with email and password
$ curl -XPOST 'localhost:3567/recipe/signup' -H  -H 'rid:emailpassword' -H 'cdi-version: 2.10' -H 'api-key: Akjnv3iunvsoi8=-sackjij3ncisds' -d '{"email":"hoge@email.com","password":"poge"}'
# signin with email and password
$ curl -XPOST 'localhost:3567/recipe/signin' -H  -H 'rid:emailpassword' -H 'cdi-version: 2.10' -H 'api-key: Akjnv3iunvsoi8=-sackjij3ncisds' -d '{"email":"hoge@email.com","password":"poge"}'
```
