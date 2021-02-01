# Simple PHP Audio Example

This repo is a simple PHP example, to demonstrate to myself, the feasability of creating a Multiple Page application (MPA) that can track audio playing across several page loads. Single Page Application (SPA) have the advantage of maintaining a session across 'pages' via the use of 'routes'. With an MPA, this is not currently possible (&lt;portal&gt; may grant this) since each page navigation loads a new page resulting a small pause to the audio as the page changes.

The impetus to try this was to rethink/return-to web applications from the 'Progressive Enhancement' development position. SPA necessitate the use of client-side JavaScript, even if the initial webpage load is rendered on the server (SSR). Can I replicate feature sets with minimal JavaScript and no framework.

This repo is structured with a lite layout system.

You can find an online example hosted on a free Heroku dyno (You many need to wait 30secs for it to boot up) here: https://audio-across-webpage-php.herokuapp.com/

A NodeJS/FastifyJS version of this can be found here: https://github.com/EnglishAdam/audio-across-webpage-example

## Start PHP Server Locally

With PHP install on your machine, call the following command from a command line tool to instantiate a PHP server.

```CONSOLE
php -S localhost:8000
```
