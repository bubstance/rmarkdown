Just a small example of some things you can do with a combination of R Markdown and LaTeX syntax/packages.

It's really neat.

### Required packages:
* R (obvs)
  * `sudo <package_manager_command> R`
    * Examples:
        * Arch
          * `sudo pacman -S R`
        * Debian/Mint/Ubuntu/etc.
          * `sudo apt install R`
        * Gentoo
          * `sudo emerge -av R`
  * `sudo R`
  * `install.packages('rmarkdown')`
  * `install.packages('bookdown')`
  * `install.packages('tufte')`

The `compiler` script I use with `vim` (in my [dot](https://github.com/bubstance/dot) repo) might complain about a missing R package;
just use the `install.packages()` command in a root R session to grab it.
