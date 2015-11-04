# Galen Introduction at Google Dev Fest 2015 in Hamburg

It’s a pain for testers and developers. Running an application with different browsers. Resize the browser window and verify that the web page is working on different screen size. Due to “Responsive Design” there are high efforts on this kind of stuff.

Sure it’s possible to calculate the delta between images to ensure that the layout does not differ between the last checks. But especially when you build up a new application or start a new design this approach doesn’t really work out. Here comes the Galen Framework to the rescue: Describe like in TDD you’re requirements in a DSL and let the framework verify it for you. The Galen DSL uses relations between elements to describe your checks. For test execution the Selenium automation stack is used. So you can even utilize Saucelabs. And the Galen Framework can be used in Java– und JavaScript projects. Additionally Galen delivers impressive reports for analyzing the failures.
