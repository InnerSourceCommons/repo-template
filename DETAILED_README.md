## How to Create a Detailed READ.ME

There are many of good examples for how to write a `README.md` and what kind
of information to include in a `CONTRIBUTING.md` file in various open source projects.
Pages like [how to write a readme that rocks](https://m.dotdev.co/how-to-write-a-readme-that-rocks-bc29f279611a),
[Open Source Guide from GitHub](https://opensource.guide/) as well as
the book [Producing Open Source](https://producingoss.com/en/producingoss.html)
all have valuable information on what kind of information to provide. While
Producing Open Source does not have a chapter on writing a good README per se,
the [Getting Started chapter](https://producingoss.com/en/producingoss.html#starting-from-what-you-have)
does provide a fairly extensive list of things that fellow host team members,
users and contributors will need.

# Insert the name of your project here

## Mission

This should contain a brief (3-5 sentences) description of the mission of your
project. The goal is to state what you are planning to work on and help external
contributors understand roughly which types of features will likely be welcome
for this project.

See also [mission statement chapter](https://producingoss.com/en/producingoss.html#mission-statement) in Producing Open Source Software.

## Getting Started

This section should contain brief documentation written for first time users on
how to get started using the project. Further more detailed documentation can be
linked to from here.

## Further information

This section can list any or all of the following:

- A list of features, use cases that the software addresses.
- Information on design principles that are used to resolve trade-offs
- Links to further user level documentation
- Answers to frequently asked questions (FAQ), preferably in a format that allows to link to specific questions and their answers for easier reference.

## Getting help

This section should contain a brief documentation on how to get help for the
project as a user. This could be as simple as pointing users to the issue
tracker if this is how your project would like to answer questions. It could
also point to an archived and searchable chat channel, some archived searchable
mailing list, some online user forum.

## Getting involved

This section should include information on how to get in touch with the project:
Typically this will contain links to archived, searchable and linkable
communication channels.

## Contributing

This section should document (or link to documentation) on all things that a
first time contributor needs to know to get started. Typically not all of the
topics below will be covered. Focus on what differs in your project from
standard setup and what previous contributors found hard to understand.

- Finding the source code.
- Finding a list of issues that your project needs help with - these can be both, technical and non-technical issues. Typically you will keep those in an issue tracker accessible to contributors.
- Links to further documentation e.g. about the architecture of the project, general coding conventions, testing conventions...
- For technical contributions: Making changes, building the project and testing your changes.
- Submitting your changes back to the project.

Ideally you also include information on what the preferred process for changes
looks like for the project: Should contributors first open an issue and submit a
proposal, or are they welcome to submit changes right away? What is important to
you when reviewing contributions?

In addition you should outline any design values you want to follow in the
project. Making those explicit often helps resolve trade-offs more quickly and
more easily. In addition it helps making changes to otherwise implicit
assumptions transparent.

Over time you will notice that this section grows substantially. In that case
think about moving the information to separate files, e.g. a `CONTRIBUTING.md` and `TESTING.md`.