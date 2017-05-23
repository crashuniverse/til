# Gerrit

Gerrit is a code review tool written for git. The smallest unit in gerrit is a
patch or a commit.

## Submit a change

    $ git push origin HEAD:refs/for/master

The only different thing about this is the `refs/for/master` branch. This is a
magic branch that creates reviews that target the `master` branch. In the output
of this command you’ll notice that there is a link to the HTTP interface of the
 Gerrit server we just pushed to.

## Review a change
Look at the Gerrit Code Review Screen you’ll notice a download command.

    $ git fetch http://gerrithost:8080/p/RecipeBook refs/changes/68/68/2

## Resources
[https://gerrit-documentation.storage.googleapis.com/Documentation/2.14/intro-quick.html](https://gerrit-documentation.storage.googleapis.com/Documentation/2.14/intro-quick.html)
