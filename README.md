# TDD for iOS

For a coding kata, I'll do some unit testing. I'm following the NSScreencast style here. My favorite professional projects have of course involved TDD unit tests with the aide of dependency injection frameworks like Typhooon, etc. 

## Why

One of the great things I love about the iOS programming community is how much the "good parts" of the ruby culture rubbed off on it, particularly the unit testing culture. There are a lot of great software engineers who develop and do their own unit tests even before writing out their final code and it's not controversial.

I prefer processes when every engineer writes unit tests in the development language as they develop instead of shoving everything off to someone who only does QA. While this isn't always possible, it's so nice when it does make sense for the team, especially since when you look at the unit tests it's very easy to figure out how the code should work. 

### Unit Tests as Documentation

Unit tests serve as an informal mode of documentation that explains things a lot better than written documentation can. Often when encountering a new open source code base I'll check out the unit tests--if someone took the time to write some nice ones it speaks wonders.

### Change is not scary

Unit tests also allow for easier experimentation on existing code. Changes are not as catastrophic, and you have less of the syndrome of "If I do something, it will break all the working things!" feeling.

