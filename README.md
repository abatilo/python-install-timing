# python-install-timing

I was curious to see how quickly it took to install `python` in a GitHub Action
environment. Comparing the install from `asdf` which uses `python-build` to
download and build `python` versus using the native `actions/setup-python`.
