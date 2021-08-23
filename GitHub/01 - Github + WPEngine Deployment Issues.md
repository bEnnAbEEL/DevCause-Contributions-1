# Github + WPEngine Deployment Issues

## WP File Manager

* [ ] What happens to Uploads folder if we need a latest form demo site. Because we don't have now  WP File Manger in use due to GitHub Actions push.

## Miscellaneous Files

* [ ] What happens to HTML / Notes / VSCode Settings / Other files that are required to be in the project not needed to be pushed to live site. Those will be included full time OR is there a way to not push them to demo site from GitHub repo.
* [ ] The bundle and bundle.min files have a lots and lots on conflicts then resolving those can be pretty tough. Also we need to re-create the bundle files for CSS changes on both end after merging so how that will be handled? Fetch the repo, run npm locally again and push it again to repo after merge conflicts?

## New Setup From already created GitHub repo

* [ ] The user copying repo cannot have any old folders like Plugins / Mu Plugins / Uploads / Theme folder etc. Else the Git bash will not download the new repo due to overwrite possibility.
