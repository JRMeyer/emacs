# emacs

The `dotemacs` file needs to be renamed to `.emacs` and moved to `~/`

`$ cp dotemacs ~/.emacs`

Run `emacs` once to automatically create `~/.emacs.d`:

`$ emacs`

Now, the C++ highlighting dependency needs to be moved to newly generated `~/.emacs.d`

`$ cp -r modern-cpp ~/.emacs.d/modern-cpp`

Enjoy!