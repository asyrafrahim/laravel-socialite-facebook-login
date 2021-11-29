<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

## Laravel 8 Socialite Facebook Login

Laravel 8 Socialite package allows to implement a robust, eloquent interface to OAuth authentication with various social media platforms such as Facebook, Twitter, Google, LinkedIn, GitHub, GitLab, and Bitbucket.

## Note

Create a Facebook app. Get app id and app secret from Facebook developers app and then register both id in config/services file. 

Facebook will send sensitive data to provided redirect_uri, so it is ensuring this connection is private, by forcing to use valid SSL.

As long as you do not setup a valid domain with proper certificate, Facebook won't let you use production API. 

Therefore, you cannot test on localhost because it needed HTTPS.