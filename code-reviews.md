# Code reviews

## Developer
### Requesting a review
As the developer of a feature, ping the team members e.g., `/cc @beerlington,
@jordpo` who have the most knowledge of the changes in the pull request.

## Reviewer
Before beginning a review, understand **why** the change is being made.
Throughout the review, be thorough and **take the time you need**.

### Reading through code
Look for the following:
* Tests exist
* Tests passing and makes sense
* Understandability
* Code conventions
* Framework best practices
* DRY business logic
* Code consistency

Ask the following questions:
* Is the intent of the code clear? Does it match the why?
* Is each commit self-contained? And does it have a clear commit message?
* Are the changes necessary?

### Leaving feedback
The tone of feedback should be open and questioning rather than certain and
accusatory. Once a pull request is open, the code is the entire team's
responsibility, not just that of the developer who initially wrote the code. It
can be helpful to frame feedback in 'we' rather than 'you'. It also works to be
strictly objective, or take ownership of your feedback as an opinion.

Keep in mind that while you might feel 100% certain you see a better way of
doing something, it's likely the developer put a decent amount of thought into
their work already and the code is how it is for good reasons. So if you make
an overly strong statement, it's likely you'll end up looking foolish. And no
one wants that!

#### Constructive feedback
* "Would it work to... ?" (impersonal question)
* "Could we try... ?" (impersonal question)
* "Ember has a method..." (objective statement)
* "I think this would be better if..." (owned opinion)

#### Destructive feedback
* "You should have..." (accusatory statement)
* "Why didn't you..." (accusatory question)
* "It's stupid to do this..." (just rude)
* "What were you thinking when..." (condescending and just rude)

