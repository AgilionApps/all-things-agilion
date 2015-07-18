# QA

Make sure the developer has left QA instructions on the ticket. If they
haven't, request them.

Two passes of QA need to be done on each feature:

1. Test the changes following the instructions left by the developer i.e., the
happy path. The goal is to verify the feature is working.
1. Test the changes by *not* following the developer's instructions. This means
try to break the feature and test anything and everything regardless of whether
or not it seems related to the feature. The goal is to discover bugs.

These two passes can either be done by the same person, or two different
people. If both are done by one person, intentionally change the mindset when
moving from the first pass to the next. Taking a break between passes can make
it easier to come at the same feature with a different approach.
