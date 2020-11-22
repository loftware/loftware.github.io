---
---
# Welcome!

[The Loft](https://loftware.org) is a collection of open source, peer-reviewed
[Swift](https://swift.org) packages.

## Resources

- [Website](https://loftware.org)
- [Forums](https://forums.loftware.org)
- [GitHub organization](http://github.com/loftware), including
  [source](https://github.com/loftware/loftware.github.io) for this site.
- [Incubation area](http://github.com/loft-nest) for unreviewed packages. A
  package idea that has been successfully pitched can be developed here.
- [Discord server](https://discord.gg/2AkrfW) 

## Philosophy

Access to high-quality software libraries is game-changing for software
development. Libraries allow programmers to
- stop solving problems that may have been solved by others
- focus on their own areas of domain expertise 
- move faster, without breaking things
- communicate ideas more effectively

The Loft's mission is to build a vibrant and widely-used package ecosystem for
Swift.

Community is crucial to this effort.  A healthy library ecosystem has a degree
of consistency that can only be achieved if developers communicate about and
record design principles, rationales, and best practices.  The peer review
process is essential to ensuring the quality and relevance of new
packages. Finally, the best libraries are not simply invented, but *discovered*
and *evolved over time* based on interaction with users.  Therefore, The Loft is
as much a community of users and developers, and a repository of their shared
knowledge, as it is source code.

## Peer Review

Like the [Swift evolution
process](https://github.com/apple/swift-evolution/blob/main/process.md), the
procedure for adding packages to The Loft is based on the [Boost submission
process](https://www.boost.org/development/submissions.html).

The key difference from Swift's evolution process is due to the decentralized
nature of The Loft: there is no core team to make rulings, so acceptance of new
packages into the collection is entirely up to the review manager. Of course, in
making a determination, the review manager should try to reflect the consensus
of the most thoughtful reviews.

## Ownership

Original authors and their designated maintainers **maintain full control** over
the evolution of their packages, without required review, once accepted into the
Loft collection.  This policy is key to motivating participation.

## Stability and API Evolution

The best package APIs evolve in response to input from their growing user bases,
having accounted for the common features of a broad range of use-cases.
A policy that promises never to break existing code would cause many APIs to
crystallize too soon.  Therefore,

- There is no Loft policy mandating ABI stability.
- There is no Loft policy mandating API stability.
- A high degree of API stability with only conscientious exceptions is strongly
  encouraged.
- Any package maintainer is free to promise full API, or even ABI, stability to
  their clients.
- Loft libraries follow [semantic versioning](https://semver.org/) conventions,
  which allow dependencies to be tracked and help to prevent working code from
  breaking due to implicit upgrades.

## Granularity

A highly granular structure is encouraged, allowing users to control
their dependencies, helping to prevent dependency loops among packages,
and encouraging contribution without undue implied maintenance commitment.
Umbrella re-exporting packages based on category (e.g. "Algorithms,"
"DataStructures," etc.) can make usage more convenient when granularity
is unneeded.

## Infrastructure/Systems

Infrastructure development and maintenance can be a major drag on an
open-source organization's viability.

- GitHub's services are:
  - free for open-source projects.
  - mostly excellent.
  - well-known and understood.
  - well-documented.
  - used successfully to support many important projects.
- Therefore, the Loft makes maximal use of GitHub's facilities and loft
  libraries are strongly encouraged to do the same.
- Opening an issue tracker to arbitrary non-actionable bug reports can create an
  untenable time sink for an open-source maintainer.  Therefore, exposing an
  issue tracker for a project is not required as long as the project accepts
  PRs.

## License

Like Swift itself, all Loft Libraries are Apache 2.0 licensed.
