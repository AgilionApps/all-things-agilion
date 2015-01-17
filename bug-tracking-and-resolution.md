# Bug tracking and resolution
This process is inspired by: http://www.joelonsoftware.com/articles/fog0000000029.html
## How to submit a bug
Create a ticket. Include:

1. Steps to reproduce
1. What you expected to see.
1. What you saw instead

## Bug Resolution
Bugs take priority over in-process work.

1. PM makes sure the bug is clearly defined and moves it to Up Next
1. Bug is assigned to a single Dev to come up with a fix
1. Dev moves ticket from Up Next to In Progress
1. Dev fixes the bug, gets it reviewed via the normal process, deploys it
1. Dev moves the ticket from In Progress to QA
1. Dev reassigns the ticket to the original Reporter
1. Reporter tests the fix and either:
  1. Accepts the ticket and moves it to Done
  1. Rejects the ticket and moves it back to Up Next
1. If the fix is rejected, repeat the cycle
