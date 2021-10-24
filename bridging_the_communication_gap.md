# Bridging the Communication Gap

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
In the telephone game (called Chinese whispers in the UK) a group of children
stand in line and then the first child whispers a phrase or sentence to the next
child. The second child whispers what it heard to the third one and so on. The
last child in the line says aloud the phrase or sentence that it heard. It is
often significantly different from the original phrase.

INCLUDE
Relying on people to remember all the details is futile. This is why features
rarely get implemented completely and correctly at the first attempt, so that
the project relies on testers running through the specification documents and
comparing them with what has been developed. This again poses a challenge since
testers often get involved only when the party is over and they are expected to
understand instantly a complex software system without taking too much of the
‘precious’ developers’ time on explaining things. As tight deadlines are a rule
rather than an exception these days, testers don’t have a lot of time to learn
about the development and system specifications. They are often expected to
approve a release in just a few days. This makes it hard for them to really
understand what they are testing and severely undermines the effectiveness of
testing.

L432 (p15)
Domino Construction Exercise

Customer, PO, Developer, Tester

There were lots of other bricks in the construction, but the primary business
goal was to make all the dominoes fall when the ball was rolled.

Customer explained to PO what he wants.
PO and Developer sit on opposite sides. Developers start building and asking
quesitons. Tester just listen and takes notes.

When developer finish, tester come and verifies. Because there was something in
conflict with her notes, she rejected the release.

Customer comes and just roles the ball. Not all dominos fall, so customer did
not accept.

The interesting thing was that the product owner never asked the customer about
the goal of the construction, so he was not able to communicate anything in this
respect.

Describing how and what but not why left the success of the project to pure
chance.

Classical project requirements focus on what but not on why. They are
effectively a proposed solution to a problem, but do not tell us what the
problem actually is.

Both traditional and agile development processes expect clients and business
experts to specify what the system should do and rely on them to get it right. I
do not agree with this. Business experts and clients should definitely be in the
driving seat of projects, but I think that much better results can be achieved
if developers and testers also have a say in what is to be built.

L492 (p19)

Cognitive diversity is very important

Getting different people involved in the process of specifying the system is
also very important from the aspect of cognitive diversity. When everyone in the
group approaches a problem from a similar viewpoint, ideas are reinforced by a
kind of echo effect and it becomes really hard to see blind spots. People in
homogenous groups often tend to make decisions to minimise conflicts and reach
consensus without really challenging or analysing any of the ideas put to
discussion. In psychology, this effect is known as groupthink.

L566 (p25)

Black-box test scripts are by nature very precise and contain clearly defined
steps and values, unlike traditional requirements which are generally a lot more
abstract.

L573
Robert C. Martin and Grigori Melnik even consider them the same thing in their
equivalence hypothesis:

"As formality increases, tests and requirements become indistinguishable. At the
limit, tests and requirements are equivalent."

L580
Concrete realistic examples give us a much better way to explain how things
really work than requirements. Examples are simply a very effective
communication technique and we use them all the time; this comes so naturally
that we are often not aware of it.

Test scripts that are produced to verify the system are also examples of how the
system behaves. They capture a very concrete workflow, with clearly defined
inputs and expected outputs.

## Agile Acceptance Testing in a nutshell

Agile Acceptance Testing revolves around the following five ideas: 

1. Use real-world examples to build a shared understanding of the domain
1. Select a set of these examples to be a specification and an acceptance test suite
1. Automate verification of the acceptance tests
1. Focus the software development effort on the acceptance tests
1. Use the set of acceptance tests to facilitate discussion about future change
requests, effectively going back to step 1 for a new cycle of development
