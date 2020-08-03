## This is a collection of tools to make working with [repo](https://gerrit.googlesource.com/git-repo) easier

## repo-bisect

Similar to **git bisect**, but works with an entire repo.

Note that due to the way certain code review tools like [gerrit](https://www.gerritcodereview.com/)
work, the git *committer date* may reflect when commits are uploaded
for review rather than when they are actually introduced into the
project.

## repo-archive

Backup and restore local repo state.  This is useful for minimizing
time and space required to backup and restore repo trees for routine
backups, transferring between computers, upgrading drives, etc.

Archives can be directories, which can then be managed using standard
Unix tools like **tar(1)**, or they can be zip files.
