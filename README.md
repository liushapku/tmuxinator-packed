# tmuxinator-packed

This packs tmuxinator with some of its dependencies, so it can be run without using gem.

The files are copied from tmuxinator ubuntu (installed using apt-get) release version 3.0.1

Credit and should go to the following.

- tmuxinator: https://github.com/tmuxinator/tmuxinator
- thor: https://github.com/rails/thor
- xdg: https://rubyworks.github.io/xdg/
- erubis: https://github.com/kwatch/erubis

LISENCE should follow those repos.


# run

- clone the repo
- install ruby
- run `RUBYLIB=lib bin/tmuxinator`
