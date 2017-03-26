THE MANIFOLD REALMS WRAPPER
===========================

[![Greenkeeper badge](https://badges.greenkeeper.io/passcod/mfdrm.svg)](https://greenkeeper.io/)

![Screenshot](https://i.imgur.com/aDZr3s3.png)

Uses node-webkit to provide a single-purpose window
onto [The Manifold Realms]. Made in the same vein as
my earlier [twd](https://github.com/passcod/twd) and
also [kndl](https://github.com/passcod/kndl).

[The Manifold Realms]: http://themanifoldrealms.makopool.com

Require node-webkit 0.7.x or greater.

RUNNING
-------

### all platforms

#### from source:

```bash
# Install node-webkit
$ git clone git://github.com/passcod/mfdrm.git
$ cd mfdrm
$ nw .
```

#### from package:

```bash
# Install node-webkit
$ wget https://github.com/passcod/mfdrm/releases/download/v1.0.0/app.nw
$ nw app.nw
```

#### making your own package:

```bash
# Install node-webkit
git clone git://github.com/passcod/mfdrm.git
cd mfdrm
zip -9 app.nw LICENSE README.md icon.png index.html package.json
```

### pre-built binaries

These are a nightmare to make.
Do it yourself if you want to.
