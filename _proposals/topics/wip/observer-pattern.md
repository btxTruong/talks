# Everyday Design Patterns: Observer Pattern

- Slack webhook trying to do something when an event happens
- first attempt is a bunch of if statements that check for a certain type of event and then do an action
  - this is okay, but is starts to become unmanageble
  - testing is fine at first, but it gets harder
- move each block in conditional to function
  - testing is easy
  - we still have a giant if block that we have to test
- dispatch events when we get them aka emit events when we get them
  - in node there is an `EventEmitter` and I wanted to use it
  - draw the early stages of the event emitter

- this loosk familiar, flask does this
  - what else uses the observer pattern?
    - DOM, UIs, PPB?

- design patterns used properly feel like they fit and make everything work together
  - feels natural
  - improves API
  - using the eventemitter felt natural that I wanted to use it again and isnt that the whole point of design patterns
  - they are tried and tested solutions to commonly occuring problems in software design

- pyee
  - how to use classes
  - this is good because it can plug into event loops
    - blog post about how PyEE will make asyncio useable

- formal definition
  - honestly even after learning it, i didn't see it until it all clicked
  - Pub/Sub

- takeaway: if you like somethng about a library, find out why you like it
  - digging deeper and learning about these patterns will improve your design
