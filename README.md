# Ruby container based on ubuntu

[![License](https://img.shields.io/github/license/betadots/container-ruby.svg)](https://github.com/betadots/container-ruby/blob/main/LICENSE)
[![Sponsored by betadots GmbH](https://img.shields.io/badge/Sponsored%20by-betadots%20GmbH-blue.svg)](https://www.betadots.de)

---

this is mainly a fork of https://github.com/docker-library/ruby

only change is:

From

```shell
FROM buildpack-deps:bookworm
```

to

```shell
FROM buildpack-deps:jammy
```

## Why not upstream?

[https://github.com/docker-library/ruby/pull/247#issuecomment-442621857]
