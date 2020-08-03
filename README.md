## This is a collection of tools to make working with [repo](https://gerrit.googlesource.com/git-repo) easier

## repo-bisect

Similar to **git bisect**, but works with an entire repo.

Note that due to the way certain code review tools like [gerrit](https://www.gerritcodereview.com/)
work, the git *committer date* may reflect when commits are uploaded
for review rather than when they are actually introduced into the
project.
