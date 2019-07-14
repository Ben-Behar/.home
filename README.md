# .home

 This is a collection of scripts that define the structure for a dotfile tracking git repository.  It is useful for those of us (like me) who find themselves modifying some of their dotfile configurations, but also tend to make mistakes and wish they could just roll back to a previous version.

#### Getting started

 * Duplicate this repo into a PRIVATE repository (so you don't do something dumb like accidentally broadcasting your ssh keys!!)
 * Clone your PRIVATE forked repository into your $HOME directory.
 * Run the command `capture-dotfiles` and select which files you want to "capture" into the git repository history (again keep in mind what you want to remain private)
 * You should now see all of your dotfiles stored within the local repository prefixed with an `_`
 * You can now use `git add` & `git commit` to create a version history of your changes and modifications

#### Suggestions
Again, remember to be careful what files you upload to public spaces.  A private repo may be secret enough for your needs but some things just aren't worth risking! If you're more conservative (like myself) you can always delete all of your remote tracking in your local repository (`git remote remove origin`), this way even if you accidentally try to push commits they won't go anywhere!
