<a name="HowtoContribute-ContributingtoApacheShiro"></a>
#Contributing to Apache Shiro

*   [Introduction](#HowtoContribute-introduction)
*   [Help Wanted Here](#HowtoContribute-help)
*   [Procedure for reporting bugs and issues and enhancement suggestions](#HowtoContribute-procedure)
*   [Git Usage](#HowtoContribute-git)
*   [Git Committers](#HowtoContribute-committer)
*   [Procedure for Raising Development Issues](#HowtoContribute-issues)
*   [How to prepare and contribute patches](#HowtoContribute-patches)
*   [How to revert changes in Git](#HowtoContribute-revert)
*   [Contribution Notes and Tips](#HowtoContribute-tips)

<a name="HowtoContribute-introductions"></a>
<a name="HowtoContribute-Introduction"></a>
##Introduction

The Shiro Project is an [Open Source](https://opensource.org/) volunteer project released under a [very liberal license](license.html "License"). This means there are many ways to contribute to the project - either with direct participation (coding, documenting, answering questions, proposing ideas, reporting bugs, suggesting bug-fixes, etc..) or by resource donations (staff time, conference presentations, publicity, software) and even general hardware/money [donations](http://www.apache.org/foundation/thanks.html) via the [Apache Software Foundation](http://www.apache.org).

To begin with, we suggest you to subscribe to the [Shiro mailing lists](mailing-lists.html "Mailing Lists") (follow the link for information on how to subscribe and to access the mail list archives). Listen-in for a while, to hear how others make contributions.

You can get your local working copy of the [latest and greatest code](download.html "Download") by following the directions in our [Download](download.html "Download") page. Review the To Do list in the [issue tracker](https://issues.apache.org/jira/browse/SHIRO) and then choose a task that interests you. Perhaps you have noticed something that needs patching, or have a new feature to contribute. Make the changes, do the testing, generate a patch, and discuss on the [dev mailing list](mailing-lists.html "Mailing Lists"). (Do not worry - the process is easy and explained below.)

Document writers are usually the most wanted people so if you like to help but you're not familiar with the innermost technical details, don't worry: you can still be tremendously helpful!

<a name="HowtoContribute-help"></a>
<a name="HowtoContribute-HelpWantedHere"></a>
##Help Wanted Here

You can be a huge help by providing extra assistance in any of the following areas:

*   Assisting to improve documentation and the website.
*   Testing Shiro (especially its less-frequently-used features) on various configurations and reporting back.
*   New samples for the 'shiro-sample' to concisely describe and demonstrate features. Such samples can also enable automated testing.
*   Debugging - producing reproducible test cases and/or finding causes of bugs. Most bugs are recorded as issues (see [explanation below](#HowtoContribute-procedure)).
*   Providing new use-cases and requirements. If you think that Shiro does not quite meet your needs then tell us about it on the mailing list.
*   Specifying/analysing/designing new features - and beyond. If you wish to get further involved with this, please join the [`shiro-dev` mailing list](mailing-lists.html "Mailing Lists"), install and try out Shiro and read some of the [mail archives](mailing-lists.html "Mailing Lists"). You should have a reasonable fluency in security technologies, some Java and Maven skills, and a basic understanding of the Shiro architecture - don't just say "it should have XYZ" without reading anything first - because chances are, somebody has already thought of that feature!)
*   Packaging easy-to-install packages (such as RPMs) for the myriad of possible configurations out there. (The project does not maintain anything but the basic .zip and .tar.gz packages, but anyone is welcome to build their own specific packages and announce them on the forrest-dev list)
*   ... and there is just one other thing - don't forget to tell everyone who asks, how great Shiro is! The more people that know about and start to use Shiro, the larger the pool of potential contributors will be.

<a name="HowtoContribute-procedure"></a>
<a name="HowtoContribute-Procedureforreportingbugsandissuesandenhancementsuggestions"></a>
##Procedure for reporting bugs and issues and enhancement suggestions

If you think that you have found a bug or you have a suggestion for improvement, then please discuss it on one of the [mailing lists](mailing-lists.html "Mailing Lists"). However, please check our [issue tracker](https://issues.apache.org/jira/browse/SHIRO) first as it may be already reported.

The [Apache Shiro Issue Tracker](https://issues.apache.org/jira/browse/SHIRO) collates our known issues. Obviously not every issue is listed there. Some issues have been discussed on the mailing list but do not yet have an issue recorded.

The Roadmap is the best way to get an overview. The Unscheduled list also needs regular review, and committers will schedule some of those for the next release.

When creating a new issue, please provide a concise Summary Title and a short Description. Add further information as Comments and include links to the mail archives. The normal procedure is to discuss the issue on the mailing list and then add relevant notes to the issue tracker, otherwise it becomes cluttered.

<a name="HowtoContribute-git"></a>
<a name="HowtoContribute-GitUsage"></a>
##Git Usage

An overview of how to use Git to participate in Shiro development. Do not be afraid - you cannot accidentally destroy the actual code repository, because you are working with a local copy as an anonymous user. Therefore, you do not have the system permissions to change anything. You can only update your local repository and compare your revisions with the real repository. The [Download Shiro](download.html "Download") page explains how to check-out the code base and build your local copy.

<a name="HowtoContribute-committer"></a>
<a name="HowtoContribute-GitCommitters"></a>
## Git Committers

After a developer has consistently provided contributions (code, documentation and discussion) and demonstrated committment, then the rest of the dev community may vote to grant this developer commit access to the Git repository. See the [ASF developers resources](http://www.apache.org/dev/) especially the [Source code repositories](http://www.apache.org/dev/version-control.html).

<a name="HowtoContribute-issues"></a>
<a name="HowtoContribute-ProcedureforRaisingDevelopmentIssues"></a>
## Procedure for Raising Development Issues

There are two methods for discussing development and submitting patches. So that everyone can be productive, it is important to know which method is appropriate for a certain situation and how to go about it without confusion. This section explains when to use the developer [mailing list](mailing-lists.html "Mailing Lists") and the [issue tracker](https://issues.apache.org/jira/browse/SHIRO).

Research your topic thoroughly before beginning to discuss a new development issue. Search and browse through the email archives - your issue may have been discussed before. Prepare your post clearly and concisely.

Most issues will be discovered, resolved, and then patched quickly via the developer mailing list. Larger issues, and ones that are not yet fully understood or are hard to solve, are destined for the issue tracker.

Experienced developers use the issue tracker directly, as they are very sure when they have found a bug and when not. However, less experienced users should first discuss it on the user or developer mailing list (as appropriate). Impatient people always enter everything into the issue tracker without caring if it is a bug of Shiro or their own installation/configuration mistake - please do not do this.

As a rule-of-thumb, discuss an issue on the developers mailing list first to work out any details. After it is confirmed to be worthwhile, and you are clear about it, then submit the bug description or patch via Bug Tracking.

Perhaps you do not get any answer on your first reply, so just post it again until you get one. (But please not every hour - allow a few days for the list to deal with it.) Bear in mind that other countries will have holidays at different times to your country and that they are in different time zones. You might also consider rewriting your initial posting. It may have not been clear to the readers on the mailing list.

<a name="HowtoContribute-patches"></a>
<a name="HowtoContribute-Howtoprepareandcontributepatches"></a>
##Contributing as a Non-Committer

If you're a committer on an Apache project, it means that you can commit directly to the project's repository. For instance, with Apache Shiro committers are allowed to directly push commits into the git repository.

Non-committers, however, have to submit patches for review. Apache Shiro accepts GitHub pull requests. If you are new to Git and GitHub, check these two links:

*   [GitHub 15 minutes tutorial](https://try.github.io/levels/1/challenges/1)
*   [Creating Pull Requests](https://help.github.com/articles/creating-a-pull-request/)

Apache Shiro has a read-only mirror on GitHub that is kept in sync with the canonical Git repo maintained by the Apache Software Foundation. Submitting GitHub pull requests is the easiest way to get your contribution upstream. For detailed instructions see the link below:

[GitHub Contribution Guidelines](https://github.com/apache/shiro/blob/master/CONTRIBUTING.md)

<a name="HowtoContribute-submitThroughJIRA"></a>
###Submitting a patch through JIRA

While we encourage you to submit your contribution through GitHub pull requests, you can also attach a patch in a JIRA ticket. For the purpose of these instructions, we'll assume that you already have a system with Git and have found a bug to fix or have a feature that you'd like to submit, and you're willing to contribute that code or documentation under the Apache License 2.0.

Further, if you're fixing a bug we'll assume that you've either filed a bug report (where you will attach your patch) or are submitting a fix for a known bug. If you find a bug and would like to fix it, that's awesome! Please be sure to file the bug too, though.

If you want to add a feature, you should bring it up for discussion on the dev@shiro.apache.org mailing list before implementing it. This ensures that it meshes with the plans that other contributors have for Apache Shiro, and that you're not doing redundant work. Other developers may also have ideas for the feature or suggestions that will help you land the feature without having to re-do the work. More information about our mailing lists can be found here.

In short, communication is a vital part of making a contribution to an Apache project.

<a name="HowtoContribute-gettingStartedGit"></a>
###Getting Started

First, lets make sure that you've added your name and email to your `~/.gitconfig`:

``` bash
$ git config --global user.name "Your Name"
$ git config --global user.email you@domain.com
```

You'll grab the Shiro source with git:

``` bash
$ git clone https://gitbox.apache.org/repos/asf/shiro.git
```

If you already have the source, make sure you're working with the most recent version. Do a `git pull` if you cloned the source more than a few hours ago. (Apache Shiro development can move pretty fast!)

``` bash
$ git checkout -b mybranch
```

This does two things: One, it creates the branch mybranch and two, it changes your working branch to mybranch. Running `git branch` will show you which branch you're working on, with an asterisk next to the active branch, like so:

``` bash
[user@localhost shiro]$ git branch
master
* mybranch
```

Make whatever changes you're going to make, be sure to use git add to stage the changes, and then you're going to commit the changes to your working branch:

``` bash
git commit -m "Insert a meaningful summary of changes here."
```

Finally, you can create a patch and attach it to the JIRA issue that you created for the bug you are fixing.

``` bash
git format-patch master --stdout > ~/patch-name.patch
```

<a name="HowtoContribute-review"></a>
###Review

Once you've submitted your pull request, you should receive a response within a few days. If you receive no response within a week, please ping the shiro-dev mailing list (dev@shiro.apache.org).

<a name="HowtoContribute-tips"></a>
<a name="HowtoContribute-ContributionNotesandTips"></a>
##Contribution Notes and Tips

This is a collection of tips for contributing to the project in a manner that is productive for all parties.

*   See general ASF [Tips for email contributors](http://www.apache.org/dev/contrib-email-tips.html)
*   There is no such thing as a dumb question. Always check the [archives](mailing-lists.html "Mailing Lists") to see if someone else asked it first and maybe already received an answer.
*   Every contribution is worthwhile. Even if the code isn't perfect. Even if the documentation has typos. Even if you got it wrong the first time around. Any contribution is a start of something special. Through your continued effort and the help of the community, your contribution will evolve and get ever closer to "perfect".
*   Use sensible and concise email subject headings. Search engines, and humans trying to browse a voluminous list, will respond favourably to a descriptive title.
*   Start new threads with new Subject for new topics, rather than reusing the previous Subject line.
*   Keep each topic focused. If some new topic arises then start a new discussion. This leaves the original topic to continue uncluttered.  
    Whenever you decide to start a new topic, then start with a fresh new email message window. Do not use the "Reply to" button, because threaded mail-readers get confused (they utilise the In-reply-to header). If so, then your new topic will get lost in the previous thread and go unanswered.
*   Prepend your email subject line with a marker when that is appropriate, e.g. [Proposal], [RT] (Random Thought which quickly blossom into research topics <i class="fa fa-smile-o" aria-hidden="true"></i>, [STATUS] (development status of a certain facility).
*   Remember that most people are participating in development on a volunteer basis and in their "spare time". These enthusiasts will attempt to respond to issues. It may take a little while to get your answers.
*   Research your topic thoroughly before beginning to discuss a new development issue. Search and browse through the email archives - your issue may have been discussed before. Do not just perceive a problem and then rush out with a question - instead, delve.
*   Try to at least offer a partial solution and not just a problem statement.
*   Take the time to clearly explain your issue and write a concise email message. Less confusion facilitates fast and complete resolution.
*   Do not bother to send an email reply that simply says "thanks". When the issue is resolved, that is the finish - end of thread. Reduce clutter.
*   You would usually do any development work against the master branch in Git.
*   When sending a patch, you usually do not need to worry about which Git branch it should be applied to. The maintainers of the repository will decide.
*   Keep all project-related discussion on the mailing list. It is much better to utilise the wider audience, rather than to break off into private discussion groups. You never know who else will have the answer to your issues, and anyway other people are interested in the outcome.
*   Become familiar with the mailing lists. As you browse and search, you will see the way other people do things. Follow the leading examples.
<input type="hidden" id="ghEditPage" value="how-to-contribute.md"></input>
