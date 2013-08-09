clean-repo
==========

These two scripts, used in conjunction, finds and cleans unwanted files from a git repository's history.

Usage
=====

show-large-files -fp

clean-repo <absolute filepath of files>

after you run clean-repo, you must do a "git push origin --force --all" and a "git push origin --force --tags"
