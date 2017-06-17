# nextcloud-token-auth

=======

features including:

+ nextcloud integrated with [redis jwt token based authentication backend](https://github.com/yrong/redis-jwt-token-auth)


### Usage

* reference auth register api and add some test user in auth
* sync user from auth to nextcloud and will add public share
* get token by login in auth
* use this token as query parameter($url?fs_auth_token=$token) to access nextcloud api

### [owncloud](http://yrong.tk/2017/03/02/owncloud)

### License

MIT
