# PHP Community Driven Standards

<p align="center">
<img src="https://avatars3.githubusercontent.com/u/19323243?v=3&s=300" width="150" />
</p>

[![Gitter](https://badges.gitter.im/php-cds/php-cds.svg)](https://gitter.im/php-cds/php-cds?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

PHP CDS is not a group or organisation, it's a concept. What people could do here is to create RFCs for standards,
vote for it and discuss it.

Its **aim is to** be as loosely coupled to any individual, group or organisation as possible.
RFCs/Standards are proposed, voted and discussed in the most simple fashion possible by the community,
so basically by anyone who is willing to contribute to the PHP community.

Its **aim is not** to propose own standards, have members or limit any discussion.

Due to the fact that there are no members involved, there's no in-house lobbyism. If you propose some ideas, you don't need
to convince some special people: The community as a whole can vote your idea immediately. You are free to propose anything you want.

## PSRs

### From PHP-CDS

None yet.

### From PHP-FIG

|  Name|
|------|
| [PSR-0](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-0.md)
| [PSR-1 Basic Coding Standard](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-1-basic-coding-standard.md)
| [PSR-2 Coding Style Guide](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md)
| [PSR-3 Logger Interface](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-3-logger-interface.md)
| [PSR-4 Autoloader](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-4-autoloader.md)
| [PSR-6 Caching Interface](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-6-cache.md)
| [PSR-7 HTTP Message Interface](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-7-http-message.md)


## How this works

### Create RFC

RFCs is a request-for-comment, mostly in form of just an issue in [php-cds/php-cds](https://github.com/php-cds/php-cds/issues/new) repository.
The author writes down his idea, maybe even first draft of API and open it immediately for discussion and voting.

### Vote RFCs and PSRs

RFCs and PSRs can be voted immeditely by using [Github reactions](https://github.com/blog/2119-add-reactions-to-pull-requests-issues-and-comments)
using :+1: and :-1:. Due to this immediate feedback, the author sees pretty fast whether its worth to keep working on it.

### Discussion on implementation

If a author decides to create a concrete implemention of an interface/API/document based of a RFC,
then all discussion about this is happening in the  [php-cds/php-cds-discussion](https://github.com/php-cds/php-cds-discussion) repository.
You may ask why: Because this way people aren't flooded with
message alerts, when they just want to act as a voter. They have the ability to watch for news/RFCs using the Github watch
function of [php-cds/php-cds](https://github.com/php-cds/php-cds) or when they want to be more involved they could watch [php-cds/php-cds-discussion](https://github.com/php-cds/php-cds-discussion).

## Get involved

All you need is a Github account. There are basically four type of users:

### Voter

[Watch the php-cds/php-cds](https://github.com/php-cds/php-cds/watchers) and especially [php-cds/php-cds-psr](https://github.com/php-cds/php-cds-psr) repositories to see new incoming RFCs andd PSRs. Vote immediately using the [Github reactions](https://github.com/blog/2119-add-reactions-to-pull-requests-issues-and-comments)
with :+1: and :-1: on incoming RFCs in the issue tracker.
You can vote RFcs in [php-cds/php-cds](https://github.com/php-cds/php-cds) and PSRs in [php-cds/php-cds-psr](https://github.com/php-cds/php-cds-psr). We will however announce in [reddit.com/r/php](https://www.reddit.com/r/PHP/) and [Twitter @php_cds](https://twitter.com/php_cds) about new and ending PSR votings as well as ending RFCs.

### Discussion people

If you want to get more involved, you can watch the repository [php-cds/php-cds-discussion](https://github.com/php-cds/php-cds-discussion), where pull-requests and deeper
discussion about implementions happen. You can participate on all discussions in this repository.

### Supporter

You can express your support by pressing the star button. This signals to other people that you support the idea
of this concept and also that you try to follow the standards made by this community.

### Mods

To keep discussions on a human level and close RFCs that are negative voted, there are mods. If you want to be a mod, write a [php-cds/php-cds issue](https://github.com/php-cds/php-cds/issues).
However, the idea of this is not to limit any discussion and do censorship. In best world, mods are not involved at all. They do not have any special
purpose except to clean up.

## Workflow

### Create a RFC

RFC (request for comments) are made using the Github issue tracker of the [php-cds/php-cds](https://github.com/php-cds/php-cds/issues) repository. You can create a issue, add a title prefixed with [RFC] and
start writing about your idea. That's it. Its probably worth to mention: Try to keep issue as small as possible so people will
get very fast a picture of your idea and are able to vote.

## How to vote on a RFC

In the Github issue tracker of the php-cds/php-cds repository you see all RFCs (issue with a title prefixed by `[RFC]`).
You can open a issue, try to understand it and express your favour with a [Github reaction](https://github.com/blog/2119-add-reactions-to-pull-requests-issues-and-comments)
using :+1: and :-1:.

## Implement/discuss a RFC

Once you think you have enough positive feedback from the community (can be seen by the [Github reactions](https://github.com/blog/2119-add-reactions-to-pull-requests-issues-and-comments))
you are free to open a discussion thread in the php-cds/php-cds-discussion repository. People that are interested in joining
your RFC can discuss and reply at any time. You can also create Pull-Requests so people can comment better on code.

## Publish PSR

Once on a RFC has been voted, you decided to create a discussion and a concrete implemention, and you think your work is
done and ready for prime time: this RFC becomes a PSR-proposal (PHP Standard Recommendation) as soon as you create a issue in the
[php-cds/php-cds-psr](https://github.com/php-cds/php-cds-psr) repository.

Creating a issue in this repository mean, you want to have a final vote on the RFC asking the community
to become a official PSR.
It's completely up to you how you write that proposal. Any github member is able to express his favour as comment or as a vote using :+1: and :-1:.

Vote is successful if 2/3 of all votes are positive (:+1:). This means that a RFC becomes a PSR, which will be officially
marked/highlighted in the php-cds repositories. Note that this doesn't mean automatically everyone should use it, its only
a recommendation.

## PSR names and changes

PSRs do not have numbers, they have names. Example "PSR-event-dispatcher", "PSR-logging", ideally corrosponding to the PHP
namespace they are living in ("PSR-event-dispatcher" -> `Psr\EventDispatcher`).

All PSRs have per default no version affix. If a change in the PSR happens, the version is increased always by 1.
Example "PSR-event-dispatcher" gets new methods to its API or other changes, then the new version will be "PSR-event-dispatcher-2".
All current PSRs and versions are displayed in the php-cds repositories.

## Close RFC and PSR

Every issue created in [php-cds/php-cds](https://github.com/php-cds/php-cds) (which represent a RFC) or [php-cds/php-cds-psr](https://github.com/php-cds/php-cds-psr) (which represent a PSR) have a voting time. Voting time is always 14 days since the create date. If a RFC or PSR has more than 1/3 negative votes it will be closed.







