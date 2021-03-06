# Questions

This is the issue tracker for Ember Data. The Ember.js community uses this site
to collect and track bugs and discussions of new features. If you are having
difficulties using Ember Data or have a question about usage please ask a
question on StackOverflow: http://stackoverflow.com/questions/ask and tag
your question with `ember.js` and `ember-data`.

The Ember.js community is very active on StackOverflow and most questions
receive attention the same day they're posted:
http://stackoverflow.com/questions/tagged/ember.js
http://stackoverflow.com/questions/tagged/ember-data

# Issues

Think you've found a bug or have a new feature to suggest? Let us know!

## Reporting a Bug
1. Update to the most recent master release if possible. We may have already
fixed your bug.

2. Search for similar issues. It's possible somebody has encountered
this bug already.

3. Provide JSFiddle or JSBin demo that specifically shows the problem. This
demo should be fully operational with the exception of the bug you want to
demonstrate. The more pared down, the better. A preconfigured [JSBin (RESTAdapter)][rest] | [JSBIN (JSONAPIAdapter)][json-api] |
[JSFiddle][2] with mocked requests is available.


[rest]: http://emberjs.jsbin.com/nunico/1/edit?html,js,output
[json-api]: http://emberjs.jsbin.com/sarobu/1/edit?html,js,output
[2]: http://jsfiddle.net/842xesgc/

4. If possible, submit a Pull Request with a failing test. Better yet, take
a stab at fixing the bug yourself if you can!

The more information you provide, the easier it is for us to validate that
there is a bug and the faster we'll be able to take action.

## Requesting a Feature

1. Search Issues for similar feature requests. It's possible somebody has
already asked for this feature or provided a pull request that we're still
discussing.

2. Provide a clear and detailed explanation of the feature you want and why
it's important to add. Keep in mind that we want features that will be useful
to the majority of our users and not just a small subset. If you're just
targeting a minority of users, consider writing an add-on library for Ember.

3. If the feature is complex, consider writing some initial documentation for
it. If we do end up accepting the feature it will need to be documented and
this will also help us to understand it better ourselves.

4. Attempt a Pull Request. If you're at all able, start writing some code. We
always have more work to do than time to do it. If you can write some code
then that will speed the process along.

# Pull Requests

We love pull requests. Here's a quick guide:

1. Fork the repo.

2. Run the tests. We only take pull requests with passing tests, and it's great
to know that you have a clean slate, see notes on how to run unit tests [here](https://github.com/emberjs/data#how-to-run-unit-tests). (To see tests in the browser,
run `npm start` and open `http://localhost:4200`.)

3. Add a test for your change. Only refactoring and documentation changes
require no new tests. If you are adding functionality or fixing a bug, we need
a test!

4. Make the test pass.

5. Push to your fork and submit a pull request. Please provide us with some
explanation of why you made the changes you made. For new features make sure to
explain a standard use case to us.

We try to be quick about responding to tickets but sometimes we get a bit
backlogged. If the response is slow, try to find someone on IRC (#emberjs) to
give the ticket a review.

Some things that will increase the chance that your pull request is accepted,
taken straight from the Ruby on Rails guide:

* Use Ember idioms and helpers
* Include tests that fail without your code, and pass with it
* Update the documentation, the surrounding one, examples elsewhere, guides,
  whatever is affected by your contribution

Syntax:

* Two spaces, no tabs.
* No trailing whitespace. Blank lines should not have any space.
* a = b and not a=b.
* Follow the conventions you see used in the source already.

And in case we didn't emphasize it enough: we love tests!

NOTE: Partially copied from https://raw.github.com/thoughtbot/factory_girl_rails/master/CONTRIBUTING.md
