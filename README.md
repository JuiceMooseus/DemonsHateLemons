# ExtendedRealitiesProject

COMMIT RULES
Only a few rules for commits, fairly simple but makes it infinitely easier to find a commit later.

"Push small, push often." This mitigates the chance of a huge commit being riddled with bugs, as opposed to a single small commit having a much easier to find bug.

Present tense commit names. If you're struggling to figure this one out, just think "what instruction would someone give me for this thing I've just done?"

Commit Prefixes. There are different prefixes to use on each commit which describe what kind of change they are. They should always be fully lowercase, as most git software supports sorting by these prefixes, which are usually caps sensitive.

The following should be all of the prefixes we should need:
- feat - A Feature. If you add anything new, whether that be onto something that already exists, or entirely new, It's a feature.
- fix - A Fix. If something didn't work as intended, and it now does, It's a fix.
- refactor - A refactor is a change in the backend that doesn't change functionality. If you rearrange some code to make it easier to read or for future-proofing purposes, but it doesn't actually change the functionality, It's a refactor.
- docs - A prefix that is used exclusively for documentation. For example, when I commit the changes to this ReadMe, this would be a docs commit.

An example of the last two rules being abided by: "feat - Implement Lemon Pesticide Flamethrower Functionality"


For more of the prefix types, please consult this github documentation: https://gist.github.com/qoomon/5dfcdf8eec66a051ecd85625518cfd13#types
