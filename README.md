SKEL-HUB
========

Simple bash script to download and extract github repo to local directory, just like "git clone" but only the source code.

Installation
------------

Clone the repo and link script to your $PATH eg. `/usr/local/bin`

```sh
git clone --depth 1 git@github.com:ball6847/skel-hub.git
ln -s $PWD/skel-hub/skel-hub /usr/local/bin/skel-hub
```

Usage
-----

Simply get the source code. (directory with repo name will be created)

```sh
skel-hub user/repo
```

Create directory with a given name and download source code to it

```sh
skel-hub user/repo directory
```

Author
------

- Porawit Poboonma
