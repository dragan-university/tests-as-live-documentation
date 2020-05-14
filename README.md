# Tests as Live Documentation

## Presentation outline

### Different terms used

* Acceptance Test-Driven Development
* Agile Acceptance Testing
* Behavior-Driven Development
* Specification By Example

## My notes

### The need for tests as documentation

Our job is to make sure the software we make is of good quality and our
customers are going to be happy while using it. To to do that we need to create
and exceute tests that will allow us to measure the software quality. But how do
we know we have enough tests?

We need to involve other people to determine that.

We need to talk to customers or BAs or POs to find out whether our tests
sufficiently cover the system functionality. To be able to answer us they need
to understand our tests. That's why we need to create tests that non-technical
people can understand.

The tests written in this way become 'live documentation' of the system.

### From Ideas to Tests

Business people together with BAs and POs create initial product requirements.
They focus on clarifying initial ideas, checking market conditions,
investigating possible competition and prioritizing features. Because of this
focus they may not produce the specification that is clear enough for developers
and testers.

Testers should be next in line to process the spec. We should add more detail,
eliminate ambiguity and produce the new version of the spec. Business people
should still be able to understand the new version, and at the same it should
make the work of software developers easier.

This new version of the spec should be the tests itself. They should be written
using more precise language, that can still be understood by all the
participants in a software development project.

### Myth: Use BDD only if non-technical people need to understand the tests

Frequently I hear argument "We used BDD because we wanted to create tests that non-technical
people can understand. However they have not used that much and we abandoned the approach".
This is so wrong. We don't do BDD just to include non-technical people. We do that because
it is good practise that leads to well defined and clear test cases. When we practice BDD
approach we create test cases that can be used as live documentation for the system. This
documentation never gets obsolete and is always in sync with the source code.
That by itself is enough reason to use and practice it :)

## Bridging the Communication Gap

L110
I am getting more and more convinced every day that communication is, in fact,
what makes or breaks software projects.

L115
Agile acceptance testing and specification by example essentially help us to
close the communication gap between different participants in a software
project (business people, software developers, testers), ensure that they speak
the same language and build a truly shared and consistent understanding of the
domain.

L122
These are the most important benefits for product owners, business analysts and
project managers:

* Developers will actually read the specifications that you write
* You will be sure that developers and testers understand the specifications
  correctly
* You will be sure that they do not skip parts of the specifications
* You can track development progress easily
* You can easily identify conflicts in business rules and requirements caused by
  later change requests
* You’ll save time on acceptance and smoke testing

From a developer’s perspective, these are the most important advantages of agile
acceptance testing and specification by example:

* Most functional gaps and inconsistencies in the requirements and
  specifications will be flushed out before the development starts
* You will be sure that business analysts actually understand special cases that
  you want to discuss with them.
* You will have automated tests as targets to help you focus the development
* It will be easier to share, hand over and take over code

From a tester’s perspective, these are the most important benefits of agile
acceptance testing and specification by example:

* You can influence the development process and stop developers from making the
  same mistakes over and over
* You will have a much better understanding of the domain
* You’ll delegate a lot of dull work to developers, who will collaborate with
  you on automating the verifications
* You can build in quality from the start by raising concerns about possible
  problems before the development starts
* You’ll be able to verify business rules with a touch of a button
* You will have a lot more time for exploratory testing
* You will be able to build better relationships with developers and business
  people and get their respect

L191
One of the main messages I want to convey with this book is that the biggest
benefit of agile acceptance testing is improved communication and mutual
understanding, not test automation. There is too much focus on tools today and
in my opinion this is quite wrong.

L258
Telephone game



## References

* [Bridging the Communication Gap: Specification by Example and Agile Acceptance Testing by Gojko Adzic](Kindle)
* [Specification by Example by Gojko Adzic](PDF)
* [Writing Great Specifications by Kamil Nicieja](BPL)
* [3 Ways How Specification By Example and Gherkin Improve Collaboration by Kamil Nicieja](https://dzone.com/articles/3-ways-specification-by-example-with-gherkin-reduc)
* [Tests as Documentation by Slalom Build](https://medium.com/slalom-build/tests-as-documentation-498d449b0f32)
* [Specification by Example by Alister Scott](https://www.thoughtworks.com/insights/blog/specification-example)
* [Specification by Example by LeSS](https://less.works/less/technical-excellence/specification-by-example.html)
* [Specification by Example Explained by ShriKant Vashishtha](https://www.scrumday.in/wp-content/uploads/2017/09/specification-by-examples-writing-executable-specification.pdf)
* [Wikipedia: Specification by Example](https://en.wikipedia.org/wiki/Specification_by_example)
* [A simple, effective test automation strategy](https://medium.com/@abstarreveld/a-simple-effective-test-automation-strategy-aa5ed2c74ca4) - "ETAS2 - A simple, effective test automation strategy.pdf"
