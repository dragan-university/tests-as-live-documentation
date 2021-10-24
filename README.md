# Tests as Live Documentation

## Presentation outline

### Different terms used

* Acceptance Test-Driven Development
* Agile Acceptance Testing
* Behavior-Driven Development
* Specification By Example

## My notes

### Hardest part of software development

During the past couple of decades software development was significantly improved.

Software design become mature with discovery of design patterns and various
other design principles. When applied properly we create software that is easy
to enhance and maintain.

Software tools and languages made software development easier and more efficient.

Agile processes helped in managing software projects more effectively.

However, one area is still waiting for major breakthrough, making sure we know what we need to build. Fred Brooks wrote long time ago "The hardest single part of building a software system is deciding precisely what to build".

### Problems with imperative specifications

Imperative specifications, which command what people should do without
demonstrating it, are not good as they are abstract, seemingly precise but leave
quite a lot of potential for mistakes.

We each have our own assumptions that affect the way we understand these
statements. The fact that we have heard, read and understood something in
English does not necessarily mean that we understood it in the same way.

Another issue is that classical project requirements focus on what but not on
why. They are effectively a proposed solution to a problem, but do not tell us
what the problem actually is.

Both traditional and agile development processes expect clients and business
experts to specify what the system should do and rely on them to get it right.
They should definitely be in the driving seat of projects, but there is lots of evidence that better results can be achieved if developers and testers also have
a say in what is to be built.

[
US Army Military experiment:

The researchers attended a military exercise and listened in while the
commanders were giving orders to their teams. During the exercise, they wrote
down everything that the teams did. After the exercise, they discussed the
actual actions of the teams with the commanders. The results of the research
were that actions on the ground matched commanders’ expectations completely only
in 34% of the cases.

commanders = customers or BAs
orders = specifications
teams on ground = developers and testers
]

### The need for ATDD

1

Software is a remarkably sensitive discipline. If you reach into a base of code
and you change one bit you can crash the software.  Go into the memory and
twiddle one bit at random and very likely you will elicit some form of crash.
Very, very few systems are that sensitive. You could go out to one of these
bridges over here, start taking bolts out and they probably wouldn’t fall. I
could pull out a gun and start shooting randomly and I probably wouldn’t kill
too many people. I might wound a few but — you know — you get a bullet in the
leg or a lung and you’d probably survive. People are resilient — they can
survive the loss of a leg and so forth. Bridges are resilient — they survive the
loss of components. But software isn’t resilient at all: one bit changes and —
BANG! — it crashes. Very few disciplines are that sensitive.

But there is one other discipline that is, and that’s Accounting. The right
mistake at exactly the right time on the right spreadsheet — that one-digit
error can crash the company and send the offenders off to jail. How do
accountants deal with that sensitivity? Well, they have disciplines. And one of
the primary disciplines is dual-entry bookkeeping. Everything is said twice.
Every transaction is entered two times — once on the credit side and once on the
debit side. Those two transactions follow separate mathematical pathways until
they end up at this wonderful subtraction on the balance sheet that has to yield
to zero.

This is what test-driven development is: dual-entry bookkeeping. Everything is
said twice — once on the test side and once on the production code side and
everything runs in an execution that yields either a green bar or a red bar just
like the zero on the balance sheet. It seems like that’s a good practice for us:
to acknowledge and manage these sensitivities of our discipline.

Robert C. Martin

2

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

### Spec gap

The complete description of the system is contained not in a single place, but
in the specification document, combined with some emails, with some change requests, and in worst case with some verbal communication.

### Myth: Use BDD only if non-technical people need to understand the tests

Frequently I hear argument "We used BDD because we wanted to create tests that non-technical
people can understand. However they have not used that much and we abandoned the approach".
This is so wrong. We don't do BDD just to include non-technical people. We do that because
it is good practise that leads to well defined and clear test cases. When we practice BDD
approach we create test cases that can be used as live documentation for the system. This
documentation never gets obsolete and is always in sync with the source code.
That by itself is enough reason to use and practice it :)

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
* [TDD as double entry book keeping](http://blog.unhandled-exceptions.com/index.php/2009/02/15/uncle-bob-tdd-as-double-entry-bookkeeping/)
