---
title: Overview
weight: 1
---

Using this package you can register one or more checks to verify the health of your application.

These are the checks created by us:

- [CPU Load](cpu-load)
- [Database Connection](db-connection)
- [Debug Mode](debug-mode)
- [Environment](environment)
- [Flare Error Count](flare-error-count)
- [Horizon](horizon)
- [Ping](ping)
- [Redis](redis)
- [Schedule](schedule)
- [Used Disk Space](used-disk-space)

## Third party checks

If you have created [a custom check](/docs/laravel-health/v1/basic-usage/creating-custom-checks), consider packaging it up so others can make use of it too. Take a look at the [spatie/cpu-load-health-check](https://github.com/spatie/cpu-load-health-check) for a good example of how to package a health check. If you don't know how to create a package, consider watching the [Laravel Package Training](https://laravelpackage.training).

When you've created a custom check, [let us know](mailto:info@spatie.be), and we'll add it to the list above

