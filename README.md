# alien_evolve

Evolve [alien](https://github.com/m-onz/alien) DSL patterns using hybrid N-gram genetic evolution.

# Idea

You have heard of live coding (algorave) but few people "evolve" their patterns. Combine this with alien constraints and this could be a powerful mechanism for algorithmic composition.

This is still a work in progress but the idea is...

* Run the alien_evolve.py script
* See the patterns.txt populate with patterns
* Open the [alien_evolve] object in Pd

The Pd object essentially opens the patterns.txt and allows you to index through the patterns. You can think of it a pre-computed pattern bank that you can use to drive any algorithmic process. 

The object could periodically re-read in the patterns.txt and the patterns.txt could begin to overwrite itself (like a circular buffer) but this is something I'm going to experiment with.
