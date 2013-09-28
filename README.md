heroku-buildpack-tweener
========================

A heroku buildpack that executes an arbitrary shell script between other heroku buildpack executions. 

This buildpack looks for a folder in the app root:
./.buildpack_shell/fin/

The first shell script in ./.buildpack_shell is run by the buildpack and moved into ./.buildpack_shell/fin/.
