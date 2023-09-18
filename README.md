lockfile
=========
Handle locking via pid files.

*Attention:* This is a fork of [Ingo Oeser's amazing work](https://github.com/nightlyone/lockfile) whose behavior differs a bit. While the original package allows a process to obtain the same lock twice, this fork forbids this behavior.

![Build Status](https://github.com/Acconut/lockfile/actions/workflows/ci.yml/badge.svg)

Install
-------

Install one of the [two latest major releases](https://go.dev/dl/) of Go. Then run

```
go get github.com/Acconut/lockfile
```

Documentation
-------------

[Package documentation at pkg.go.dev](https://pkg.go.dev/github.com/Acconut/lockfile).

Contributing
------------

Contributions are welcome. Please open an issue or send me a pull request for a dedicated branch.
Make sure the git commit hooks show it works.

git commit hooks
-----------------------
enable commit hooks via

        cd .git ; rm -rf hooks; ln -s ../git-hooks hooks ; cd ..


License
-------
MIT
