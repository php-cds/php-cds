# PHP Community Driven Standards

<p align="center">
<img src="https://avatars3.githubusercontent.com/u/19323243?v=3&s=300" width="150" />
</p>

[![Gitter](https://badges.gitter.im/php-cds/php-cds.svg)](https://gitter.im/php-cds/php-cds?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

PHP CDS is not a group or organisation, it's a concept. Its core idea is for the community to create RFCs,
discuss them, then hold a vote on their acceptance as a community standard.

Its **aim is to** be as loosely coupled to any individual, group or organisation as possible.
RFCs/Standards are proposed, discussed, agreed upon in the simplest possible fashion by the community.
Anyone willing to contribute to the PHP community is welcome to participate in the CDS process.

Its **aim is not** to propose standards itself, have members or limit discussion.

Because there is no membership involved, there's no in-house lobbying. If you propose ideas, you don't need
to convince the right people: You are free to propose anything you want, and the community as a whole can accept or reject your idea. 

## PSRs

### From PHP-CDS

None yet.

### From PHP-FIG
=======

|  Name|
|------|
| [PSR-0](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-0.md)
| [PSR-1 Basic Coding Standard](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-1-basic-coding-standard.md)
| [PSR-2 Coding Style Guide](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md)
| [PSR-3 Logger Interface](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-3-logger-interface.md)
| [PSR-4 Autoloader](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-4-autoloader.md)
| [PSR-6 Caching Interface](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-6-cache.md)
| [PSR-7 HTTP Message Interface](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-7-http-message.md)


## How the Process Works

### Create an RFC

An RFC is a request-for-comment, mostly in the form of an issue in the [php-cds/php-cds](https://github.com/php-cds/php-cds/issues/new) repository.
The author describes his idea, maybe even first draft of an API, and then opens it immediately for discussion and voting.

### Voting for an RFC

RFCs can be voted on immediately using [Github reactions](https://github.com/blog/2119-add-reactions-to-pull-requests-issues-and-comments)
using :+1: and :-1:. Based on this immediate feedback, the author can quickly see whether there is merit to their idea.

Participants have the ability to watch for activity using Github's watch function on the [php-cds/php-cds](https://github.com/php-cds/php-cds) repository.

### Discussion on implementation

If an author decides to create a concrete implementation of an interface/API/document based on an RFC,
all discussion should happen in the [php-cds/php-cds-discussion](https://github.com/php-cds/php-cds-discussion) repository.

Discussion in a separate repository prevents noise for those who are only interested in voting.

Those who want to be more involved in the community driven standards process can watch the [php-cds/php-cds-discussion](https://github.com/php-cds/php-cds-discussion) repository.

## Get involved

All you need to get involved is a Github account. You can participate in several different ways:

### Vote

Watch the [php-cds/php-cds](https://github.com/php-cds/php-cds/watchers) and especially the [php-cds/php-cds-psr](https://github.com/php-cds/php-cds-psr) repositories for new RFCs and PSRs. Vote immediately using [Github reactions](https://github.com/blog/2119-add-reactions-to-pull-requests-issues-and-comments)
with :+1: and :-1: on the incoming RFC's issue tracking page.

You can vote RFCs in [php-cds/php-cds](https://github.com/php-cds/php-cds) and PSRs in [php-cds/php-cds-psr](https://github.com/php-cds/php-cds-psr). We will however announce in [reddit.com/r/php](https://www.reddit.com/r/PHP/) and [Twitter @php_cds](https://twitter.com/php_cds) about new and ending PSR voting as well as ending RFCs.

### Discuss

If you want to get more involved, you can watch the [php-cds/php-cds-discussion](https://github.com/php-cds/php-cds-discussion) repository, where pull-requests and discussion about implementations happen. You can participate on all discussions in this repository.

### Support

You can express your support for a standard by pressing the star button. This signals to other people that you support the idea
or concept and also that you have an active interest in community driven standards.

### Moderate

To keep discussions level-headed and to maintain state of RFCs, moderators are needed. If you want to be a moderator, create a [php-cds/php-cds issue](https://github.com/php-cds/php-cds/issues).

A moderator must not limit discussion or censor ideas. In an ideal world, moderators wouldn't be involved at all. They do not have any special
purpose other than to help maintain clean repositories on behalf of the community.

## Workflow

### Create a RFC

RFC (request for comments) are made using the Github issue tracker of the [php-cds/php-cds](https://github.com/php-cds/php-cds/issues) repository. You can create an issue, add a title prefixed with [RFC] and
start writing about your idea. That's it.

Try to be as concise as possible so readers will be able to quickly digest and understand your idea before voting.

## How to vote on an RFC

In the Github issue tracker of the php-cds/php-cds repository you see all RFCs (issues with a title prefixed by `[RFC]`).
After reading the issue description, try to understand it and express your opinion with a [Github reaction](https://github.com/blog/2119-add-reactions-to-pull-requests-issues-and-comments)
using :+1: and :-1:.

## Implement/discuss an RFC

Once you think you have enough positive feedback from the community (as seen by the [Github reactions](https://github.com/blog/2119-add-reactions-to-pull-requests-issues-and-comments))
you are free to open a discussion thread in the php-cds/php-cds-discussion repository. People that are interested in joining
your RFC can discuss and reply at any time. You can also create Pull-Requests so people can easily comment on proposed code.

## Publish PSR

Once on a RFC has positive community reaction, you have decided to create a discussion and a concrete implementation, and you think your work is
done and ready for prime time, the RFC becomes a PSR-proposal (PHP Standard Recommendation) as soon as you create a issue in the
[php-cds/php-cds-psr](https://github.com/php-cds/php-cds-psr) repository.

Creating an issue in this repository means you want to have a final vote on the RFC asking the community for your proposal to become an official PSR.
It's completely up to you how you write your proposal. Any github member is able to express his opinion as a comment or as a vote using :+1: and :-1:.

A vote is considered successful if 2/3 of all votes are positive (:+1:). This means that an RFC becomes a recommended standard, which will be displayed in the php-cds repositories. Please note that this doesn't mean everyone automatically will use it; its still just
a recommendation.

## PSR names and changes

PSRs do not have numbers, they have names. For example "PSR-event-dispatcher" or "PSR-logging", ideally corresponding to the PHP
namespace in which they reside ("PSR-event-dispatcher" -> `Psr\EventDispatcher`).

PSRs do not have an initial version number attached. If a change is required, the version will be incremented by 1.
For example, an update to "PSR-event-dispatcher" would become "PSR-event-dispatcher-2".
The current version of all accepted PSRs are displayed in the php-cds repositories.

## Close RFC and PSR

Every issue created in [php-cds/php-cds](https://github.com/php-cds/php-cds) (which represents an RFC) or [php-cds/php-cds-psr](https://github.com/php-cds/php-cds-psr) (which represents a PSR) has an allowed voting window. The voting window is always 14 days from the creation date. If an RFC or PSR has more than 1/3 negative votes, it will be closed.
