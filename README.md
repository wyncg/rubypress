# rubypress-without-ssl-check

Refer to rubypress gem

This gem is almost the same as rubypress gem written by Zach Feldman. Only difference is this gem bypass OpenSSL verify_certificate_identity check, which causes hostname does not match the server certificate in some cases.

It's a very bad practice to bypass the check. We don't recommend use this gem on production.