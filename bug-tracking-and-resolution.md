# Bug tracking and resolution
This process is inspired by: http://www.joelonsoftware.com/articles/fog0000000029.html

## How to submit a bug
If you are testing a fix or feature that has an existing ticket – and the issue
you've found is small – add a comment to that ticket. Otherwise, if there is
not a ticket – or the issue is large or a new feature request – create a new
ticket. Avoid dropping bugs in real-time chat. Include:

1. Steps to reproduce
1. What you expected to see.
1. What you saw instead

Example:

1. Steps to reproduce
  * Create a product
  * Add three categories to the product
  * Visit the product's landing page

1. What you'd expect to see
  * As a normal (logged out) user, when I visit the product's show page, I expect to see the categories listed below the product name.

1. What you saw instead
  * I saw only the product name, there were no categories listed beneath it.

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

It is important the bug be reassigned to the reporter after a fix has been deployed so they can confirm the fix is good. This gives all parties a sense of closure.
