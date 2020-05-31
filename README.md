# social-simple-jwt-authentication
This is a customized jwt authentication WP plugin based on [Jonathan Dejong's simple-jwt-authentication](https://github.com/jonathan-dejong/simple-jwt-authentication).

## What's added?
- Added `apply_filters` on validate token
- Added `param['strategy']` check on token creation to detect `local` or `social` login

## Jonathan Dejong's simple-jwt-authentication
Extends the WP REST API using JSON Web Tokens Authentication as an authentication method.
[Documentation](https://github.com/jonathan-dejong/simple-jwt-authentication/wiki/Documentation)
