<a name="HowtoContribute-ContributingtoApacheShiro"></a>
#Contributing to Apache Shiro

*   [Introduction](#HowtoContribute-introduction)
*   [Help Wanted Here](#HowtoContribute-help)
*   [Procedure for Raising Development Issues](#HowtoContribute-issues)
*   [Procedure for reporting bugs and issues and enhancement suggestions](#HowtoContribute-procedure)
*   [Git Usage](#HowtoContribute-git)
*   [Git Committers](#HowtoContribute-committer)
*   [Contribution Notes and Tips](#HowtoContribute-tips)

<a name="HowtoContribute-introductions"></a>
<a name="HowtoContribute-Introduction"></a>
##Introduction

Apache Shiro is an [Open Source](https://opensource.org/) software security framework that performs authentication, authorization, cryptography and session management. The Shiro Project is an volunteer project released under a [liberal license](license.html "License"). Anyone can participate and volunteer. No need to be an experienced developer or have great visions. Roll up your sleeves and come try, help is always welcome and your input will be appreciated!

There are many ways how to contribute to this project, you can participate directly by:
* coding
* documenting
* answering questions
* proposing ideas
* reporting bugs
* suggesting bug-fixes
* etc.

Or you can participate with resource donations:
* staff time
* conference presentations
* publicity
* software
* general hardware/money [donations](http://www.apache.org/foundation/thanks.html) via the [Apache Software Foundation](http://www.apache.org)

Subscribe to the [Shiro mailing lists](mailing-lists.html "Mailing Lists").

You can get your local working copy of the [latest and greatest code](download.html "Download") by following the directions in [Download](download.html "Download") page. Review the To Do list in the [issue tracker](https://issues.apache.org/jira/browse/SHIRO) and then choose a task that interests you.

Perhaps you have noticed something that needs patching, or have a new feature to contribute. Make the changes, do the testing, generate a patch, and discuss on the [dev mailing list](mailing-lists.html "Mailing Lists"). The process is easy and explained below.

<a name="HowtoContribute-help"></a>
<a name="HowtoContribute-HelpWantedHere"></a>
##Help Wanted Here

You can be a huge help by providing extra assistance in any of the following areas:

*   Assisting to improve documentation and the website.
*   Testing Shiro on various configurations and reporting back, especially Shiro's less-frequently-used features.
*   New samples for the 'shiro-sample' to concisely describe and demonstrate features. Such samples can also enable automated testing.
*   Debugging - producing reproducible test cases and/or finding causes of bugs. Most bugs are [recorded as issues](#HowtoContribute-procedure)).
*   Providing new use-cases and requirements.
**	If you think that Shiro does not quite meet your needs then tell us about it on the mailing list.
*   Specifying, analysing or designing new features - and beyond.
**	If you wish to get further involved with this, please join the [`shiro-dev` mailing list](mailing-lists.html "Mailing Lists"), install and try out Shiro and read some of the [mail archives](mailing-lists.html "Mailing Lists").
***	Don't just say "it should have XYZ" without reading anything first - because chances are, somebody has already thought of that feature.
*   Packaging easy-to-install packages (such as Red Hat Package Managers (RPM)) for the myriad of possible configurations out there.
**	The project does not maintain anything but the basic .zip and .tar.gz packages, but anyone is welcome to build their own specific packages and announce those on the mailing list.
*   ... and one more thing - don't forget to tell everyone, how great Shiro is! The more people that know about and start to use Shiro, the larger the pool of potential contributors will be.

<a name="HowtoContribute-procedure"></a>
<a name="HowtoContribute-Procedureforreportingbugsandissuesandenhancementsuggestions"></a>
##Procedure for Reporting Bugs and Issues and Enhancement Suggestions

If you think that you have found a bug or you have a suggestion for improvement, then please discuss it on one of the [mailing lists](mailing-lists.html "Mailing Lists"). However, please check our [issue tracker](https://issues.apache.org/jira/browse/SHIRO) first as it may be already reported.

The [Apache Shiro Issue Tracker](https://issues.apache.org/jira/browse/SHIRO) collates our known issues. Obviously not every issue is listed there. Some issues have been discussed on the mailing list but do not yet have an issue recorded.

The Roadmap is the best way to get an overview. The Unscheduled list also needs regular review, and committers will schedule some of those for the next release.

When creating a new issue, please provide a concise Summary Title and a short Description. Add further information as Comments and include links to the mail archives. The normal procedure is to discuss the issue on the mailing list and then add relevant notes to the issue tracker, otherwise it becomes cluttered.

<a name="HowtoContribute-issues"></a>
<a name="HowtoContribute-ProcedureforRaisingDevelopmentIssues"></a>
##Procedure for Raising Development Issues

There are two methods for discussing development and submitting patches. So that everyone can be productive, it is important to know which method is appropriate for a certain situation and how to go about it without confusion.

###Mailing List

Research your topic thoroughly before beginning to discuss a new development issue on the [mailing list](mailing-lists.html "Mailing Lists"). Search and browse through the email archives - your issue may have been discussed before. Prepare your post clearly and concisely.

Most issues will be discovered, resolved, and then patched quickly via the developer mailing list. Larger issues, and ones that are not yet fully understood or are hard to solve, are destined for the issue tracker.

###Issue Tracker

Experienced developers use the [issue tracker](https://issues.apache.org/jira/browse/SHIRO) directly, as they are very sure when they have found a bug and when not. Less experienced users should first discuss it on the user or developer mailing list (as appropriate). Impatient people always enter everything into the issue tracker without caring if it is a bug of Shiro ,or their own installation/configuration mistake - please do not do this.

Discuss an issue on the developers mailing list first to work out any details. After it is confirmed to be worthwhile, and you are clear about it, then submit the bug description or patch via Bug Tracking..

Perhaps you do not get any answer on your first reply, so just post it again until you get one. But please not every hour - allow a few days for the list to deal with it. Bear in mind that other countries will have holidays at different times to your country and that they are in different time zones. You might also consider rewriting your initial posting. It may have not been clear to the readers on the mailing list.

<a name="HowtoContribute-submitThroughJIRA"></a>
###Submitting a Patch Through JIRA

While we encourage you to submit your contribution through GitHub pull requests, you can also attach a patch in a JIRA ticket. For the purpose of these instructions, we'll assume that you already have a system with Git and have found a bug to fix or have a feature that you'd like to submit, and you're willing to contribute that code or documentation under the Apache License 2.0.

Further, if you're fixing a bug we'll assume that you've either filed a bug report (where you will attach your patch) or are submitting a fix for a known bug. If you find a bug and would like to fix it, that's awesome! Please be sure to file the bug too, though.

If you want to add a feature, you should bring it up for discussion on the dev@shiro.apache.org mailing list before implementing it. This ensures that it meshes with the plans that other contributors have for Apache Shiro, and that you're not doing redundant work. Other developers may also have ideas for the feature or suggestions that will help you land the feature without having to re-do the work. More information about our mailing lists can be found here.

In short, communication is a vital part of making a contribution to an Apache project.

<a name="HowtoContribute-git"></a>
<a name="HowtoContribute-GitUsage"></a>
##Git Usage

An overview of how to use Git to participate in Shiro development. Beginners, do't be afraid - you cannot accidentally destroy the actual code repository, because you are working with a local copy as an anonymous user. Therefore, you do not have the system permissions to change anything. You can only update your local repository and compare your revisions with the real repository. The [Download Shiro](download.html "Download") page explains how to check-out the code base and build your local copy.

<a name="HowtoContribute-gettingStartedGit"></a>
###Git, Getting Started

Add your name and email to your `~/.gitconfig`:

``` bash
$ git config --global user.name "Your Name"
$ git config --global user.email you@domain.com
```

Grab the Shiro source:

``` bash
$ git clone https://gitbox.apache.org/repos/asf/shiro.git
```

Make sure you're working with the most recent version. Do a `git pull` if you cloned the source more than a few hours ago.

``` bash
$ git checkout -b mybranch
```

This does two things:
* creates the branch mybranch
* changes your working branch to mybranch.
Running `git branch` will show you which branch you're working on, with an asterisk next to the active branch.

``` bash
[user@localhost shiro]$ git branch
master
* mybranch
```

Use `git add` to stage the changes. Commit the changes to your working branch:

``` bash
git commit -m "Insert a meaningful summary of changes here."
```

Finally, you can create a patch and attach it to the JIRA issue:

``` bash
git format-patch master --stdout > ~/patch-name.patch
```

*   When sending a patch, you usually do not need to worry about which Git branch it should be applied to. The maintainers of the repository will decide.
*   Every contribution is worthwhile! Even when the code isn't perfect or documentation has typos. Even if you got it wrong the first time around. Any contribution is a start of something special. Through your continued effort and the help of the community, your contribution will evolve.

<a name="HowtoContribute-review"></a>
###Review

Fter submitting pull request, you should receive a response within a few days. If you receive no response within a week, please send a message to the shiro-dev mailing list (dev@shiro.apache.org).

<a name="HowtoContribute-committer"></a>
<a name="HowtoContribute-GitCommitters"></a>
##Git Committers

After a developer has consistently provided contributions such as code, documentation and discussion, and demonstrated committment, then the rest of the dev community may vote to grant this developer commit access to the Git repository. See the [ASF developers resources](http://www.apache.org/dev/) and especially the [Source code repositories](http://www.apache.org/dev/version-control.html).

<a name="HowtoContribute-patches"></a>
<a name="HowtoContribute-Howtoprepareandcontributepatches"></a>
##Contributing as a Non-Committer

Non-committers, have to submit patches for review. Apache Shiro accepts GitHub pull requests. 

Apache Shiro has a read-only mirror on GitHub that is kept in sync with the canonical Git repo maintained by the Apache Software Foundation. For detailed instructions see the [GitHub Contribution Guidelines](https://github.com/apache/shiro/blob/master/CONTRIBUTING.md).

<a name="HowtoContribute-tips"></a>
<a name="HowtoContribute-ContributionNotesandTips"></a>
##Contribution Notes and Tips

This is a collection of tips for contributing to the project in a manner that is productive for all parties.

###Links
*   [Tips for email contributors](http://www.apache.org/dev/contrib-email-tips.html)
*   Old questions and answers in [archives](mailing-lists.html "Mailing Lists").

*	There are no dumb questions. But browse, search and learn from mailing list archives.
*	Research your topic thoroughly before beginning to discuss a new development issue. 

###Emails
*	Start new threads with new Subject for new topics, rather than reusing the previous Subject line. Use a descriptive title!
**	Clearly explain your issue and write a concise email message.
*   Try to at least offer a partial solution and not just a problem statement.
*   Prepend your email subject line with a marker when that is appropriate, e.g.:
**	[Proposal]
**	[RT] (Random Thought which quickly blossom into research topics)
**	[STATUS] (development status of a certain facility)

*   Reduce clutter, don't send an e-mail which simply says "thanks".
*   Keep all project-related discussion on the mailing list. It is better to utilise the wider audience, rather than to break off into private discussions. You never know who else will have the answer to your issues, and anyway other people are interested in the outcome.
<input type="hidden" id="ghEditPage" value="how-to-contribute.md"></input>
