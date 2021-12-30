# .dotfiles

This repository contains my configuration files for various applications which I want to share across multiple computers to maintain a consistent working environment. It requires the use of [GNU Stow](https://www.gnu.org/software/stow/) to manage symlinks of various settings

## Installation

1.  Install [Homebrew](https://brew.sh/).

2.  Install `git` and `stow` via Homebrew.

    ```
    brew install git stow
    ```

3.  Clone this repository and save it to the home directory

    ```
    git clone git@github.com:michaelfich/.dotfiles.git ~/.dotfiles
    ```

4.  Install applications that have their settings saved within this repository

5.  Navigate to the `.dotfiles` repository

    ```
    cd ~/.dotfiles
    ```

6.  Symlink the settings for a given application with **GNU Stow** by using the following command:

    ```
    stow */
    ```
