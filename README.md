# WSGI Secure Cookie and Session

Provides interfaces for secure cookies and sessions in WSGI
applications. Secure cookies are cryptographically signed (but not
encrypted) to prevent tampering. Sessions are data associated with a
given user across requests and responses.

> [!NOTE]
> This is a fork of the official `secure-cookie` package maintained by
> the Doist backend team.
>
> We maintain this because the package is almost abandoned, and needs
> several patches to run against recent Werkzeug versions. However, we
> do this in pure maintenance mode. Do not expect any new feature or
> further developments. We may abandon this at any time, without any
> prior warning. In other words: use this at your own risks.


## Install

Install in a [virtualenv][] with [pip][]:

```sh
$ pip install secure-cookie
```

[virtualenv]: https://virtualenv.pypa.io/en/stable/
[pip]: https://pip.pypa.io/en/stable/


## Links

-   Documentation: https://secure-cookie.readthedocs.io/
-   Releases: https://pypi.org/project/secure-cookie/
-   Code: https://github.com/pallets/secure-cookie
-   Issue tracker: https://github.com/pallets/secure-cookie/issues
-   Official chat: https://discord.gg/t6rrQZH
