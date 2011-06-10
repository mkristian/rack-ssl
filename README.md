Rack::SSL
=========

Force SSL/TLS in your app.

1. Redirects all "http" on given port (option-key :port, default 80) requests to "https" with a given port (option-key :ssl_port, default 443)
2. Set `Strict-Transport-Security` header
3. Flag all cookies as "secure"

Usage
-----

    use Rack::SSL
