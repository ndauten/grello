# Grello: A Trello to Git CLI

For the hacker, almost every software artifact, whether code
or writing, is chronicled via a git repository. The old
addage (yes, surprisingly old by now) is that in case of a
fire, on always types `git add .; git commit -m "Its on Fire
Safety Save; git push" and get the hell out of there. Users
can rest assured that whatever remote will keep their lives
afloat. Unfortunately, modern applications make project and
life management much easier but lack any direct path to the
standard git-flow model. The aspiration of Grello is to
bridge that gap so that automated workflows will transform a
trello board into a local structure and automate committing
to git. 

## An Initial Design Brainstorm

Things that will be needed:

1. A design to mirror the web version locally: is this a
   file system? Is it editable? Two way? Do we just store
   JSON formatted text to push to git? 


