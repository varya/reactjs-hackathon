# Draft

## Plan

1. Introduction
1. The tests we have
   Unit tests and tons of graphs, and they does not help in some cases (make an example).
   1. The tests we don't have
1. Customer context
   Metrics for "does my website makes sense for the customer right now"? Code review does not help.
   1. Examples of errors
      * wrong price
      * big table of data
        No-one notices change
   1. How to test?
      * Graphics
      * By chance
      * Manually
   Regression might be in production much longer before you realize it.
   1. Perceptual diffs
      Visual regression tests
1. The idea of visual regression testing
   1. The flow
      Baseline screenshots
1. Styleguide perspective
   Big pages provide big diffs even if everything is correct (expected changes).
   Margin of 1 block makes big diff of the whole page.
1. Variants of checks:
   * sizes (desktop, mobile)
   * browsers
   * products (emails)
1. Needed features
   1. Ignore things
      You care only about things you care about
   1. Test the behavior
      Drive UI with JS events like in Selenium.
1. Where to apply
   If you could not get some practises, now you can
   1. Continuous deployment
      Doing impossible 50 times a day (article)
   1. Huge changes
   1. Removing code
1. Psycology
   1. Problems
      Devs must be accurate but nothing checks it. Code review does not help.
   1. Fun
      Waiting for implemented feature to deliver demotivates. Pushing offen makes people happier.
   1. Diff makes feel safier
      You won't break the world when you push
   1. You don't even write a test
      Thanks to component approach
   1. Empowers junior engineers to do more
      And not junior as well.
      We all are bravier and so more productive.
1. Business perspective
1. Conclusion
   1. Plans for future
   1. This is a experiment. Help!

## External Materials

### Video

* [Velocity 2013: The Secret of Safe Continuous Deployment: Perceptual Diffs](https://youtu.be/1wHr-O6gEfc) by Brett
Slatkin from Google.
* [A Live Intro to Gemini Visual Regression Testing](https://youtu.be/joADgrvvrYM)

### Texts

[Wraith discussion and YCombinator](https://news.ycombinator.com/item?id=6135447)

## Ideas

### Testing

* acceptane testing
* functional
* system
* stress
* conformance
* smoke
* black box
* load
* compatibility
* performance
* regression
* white box
* unit

### Business
Speed is our advantage towards the bigger players...

being productive from the day one (connect to junior)

### Good words

secret to safe continuous deployment

perceptual diffs

catching the unintended consequenses of modifying interface.
