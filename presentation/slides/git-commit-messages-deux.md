##  Let's be poets

To write real, long, meaningful commit messages in your default $EDITOR - just run git commit without the -m flag

    git commit


Now be verbose about intention, cause, and effect. ICE!

> Re-arranged the import statements alphabetically to conform to the rest of the project.  Refactored the do_not_derp method to fix a race-condition that yielded, a derp. Resolves edge cases in CI that would cause it to derp. Fixes #12


note:
    Notice that we can interact withour issue tracker (the #12 is linked right against the issue, so not only do we have teh bug, we have the fixing commit in teh same data item.) And anyone that is reviewing the repository history knows immediately what I did without looking at the document changes.
