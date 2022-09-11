# gh-migration
This repo is used to manage the migration from bugs.python.org to GitHub.

# Relevant Documents

## PEPs

* [PEP 581 -- Using GitHub Issues for CPython](https://www.python.org/dev/peps/pep-0581/): outlines the rationale for the migration and
* [PEP 588 -- GitHub Issues Migration Plan](https://www.python.org/dev/peps/pep-0588/): outlines the initial migration plan
* [PEP 595 -- Improving bugs.python.org](https://www.python.org/dev/peps/pep-0595/): includes issues with PEP 581/588, migration considerations, and a list of advantages that Roundup has over GitHub Issues

PEP 581 has been accepted, PEP 588 is still a draft (thus subject to changes), and PEP 595 has been withdrawn (but still contains valuable information).

## Discourse threads

* [PEP 581 - Using GitHub Issues](https://discuss.python.org/t/pep-581-using-github-issues/535) (Dec 2018, 37 msgs): early discussion about PEP 581
* [Proposal: Create “Bug Triage” team on GitHub](https://discuss.python.org/t/proposal-create-bug-triage-team-on-github/992) (Mar 2019, 59 msgs): discussion about the triage team, labels, CODEOWNER file, etc.
* [What are next steps for PEP 581?](https://discuss.python.org/t/what-are-next-steps-for-pep-581/864) (Feb 2019, 3 msgs): short discussion about triaging, components and priority labels
* [Using CLA Assistant for Python](https://discuss.python.org/t/using-cla-assistant-for-python/990) (Mar 2019, 25 msgs): discussion about using CLA-assistant
* [CLA-assistant is No-Go](https://discuss.python.org/t/cla-assistant-is-no-go/2066) (Jul 2019, 32 msgs): discussion about using CLA-assistant

## Mailing list threads

* [PEP 581: Using GitHub Issues for CPython](https://mail.python.org/archives/list/python-dev@python.org/thread/W4W6YSJH7ZOG3N6Y6BFFGVT6CPDS7X2P/) (Mar 2019, python-dev, 7 msgs)
* [Steering Council Update for April 2019](https://mail.python.org/archives/list/python-committers@python.org/thread/UEKNCJ36H6GZKDD7MENZYJKD3FB3TIYX/) (Apr 2019, python-committers, 12 msgs)
* [PEP 581 (Using GitHub issues for CPython) is accepted](https://mail.python.org/archives/list/python-dev@python.org/thread/CQWQIM5Y6ELN3NRBT5RR6U5WY5WF7KXZ/#CQWQIM5Y6ELN3NRBT5RR6U5WY5WF7KXZ) (May 2019, python-dev, 24 msgs)
* [PEP 595: Improving bugs.python.org](https://mail.python.org/archives/list/python-dev@python.org/thread/OFENXHCWVADJS7I4HLY4F5MHCDW6TJV6/#OFENXHCWVADJS7I4HLY4F5MHCDW6TJV6) (May 2019, python-dev, 13 msgs):
* [PEP 581/588 RFC: Collecting feedback about GitHub Issues](https://mail.python.org/archives/list/python-dev@python.org/thread/S5L54M2HJ4DM46HLU45HVEYYAQYXHEQ2/#S5L54M2HJ4DM46HLU45HVEYYAQYXHEQ2) (Aug 2019, python-dev, 3 msgs)
* [Re: PEP 581/588 RFC: Collecting feedback about GitHub Issues](https://mail.python.org/archives/list/python-committers@python.org/thread/IFSHRRBKRP56NOVI4DDWNWKAUK53C5SK/#2HWYHURO7XETBZO7YR4V6JDWX3FA2OA5) (Sep 2019, python-committers, 11 msgs)

## Mailing list threads (historical)

* [PSF Infrastructure Committee's recommendation for a new issue tracker](https://mail.python.org/archives/list/python-dev@python.org/thread/KSJTYU4XC5VTLHJGV76ZCGTEQZY26D7X/#6MY6XXFRXFGSGQ3NJELX7HEJUISMHYIC) (Oct 2006, python-dev, 3 msgs)
* [PSF Infrastructure has chosen Roundup as the issue tracker for Python development](https://mail.python.org/archives/list/python-dev@python.org/thread/VK3C6G6QNRDOT66YSX4TZSUG2JUFQK2F/#VK3C6G6QNRDOT66YSX4TZSUG2JUFQK2F) (Oct 2006, python-dev, 3 msgs)

## GitHub repos, issues, and projects

* [PEP 581/588 RFC: Collecting feedback about GitHub Issues](https://github.com/python/core-workflow/issues/359) (core-workflow repo): a long list of features/issues with comments and votes (from Aug 19th)
* [Consider whether or not to migrate bugs.python.org source code to this repo](https://github.com/python/bugs.python.org/issues/2) (bugs.python.org repo): contains info about different repos related to our fork of Roundup, b.p.o, and the other instances
* [Backup GitHub information](https://github.com/python/core-workflow/issues/20) (core-workflow repo): discussion about backing up GitHub data

* [Adding triagers role into CPython GitHub](https://github.com/python/core-workflow/projects/3) project (core-workflow repo)
* [Migrating to CLA Assistant](https://github.com/python/core-workflow/projects/1) project (core-workflow repo)

## Wiki links

* How to make the tracker read-only: https://wiki.roundup-tracker.org/ReadOnlyTracker
* The [Desired Tracker Features](https://wiki.python.org/moin/DesiredTrackerFeatures) page discusses features we wanted for Roundup, and different ways to handle labels
* The [Tracker Development](https://wiki.python.org/moin/TrackerDevelopment) page contains (mostly outdated) info about setting up and maintaining Roundup and irker, and using roundup-admin
* The [Tracker Development Planning](https://wiki.python.org/moin/TrackerDevelopmentPlanning) page contains other discussions

## Zulip streams

* https://python.zulipchat.com/#narrow/stream/130206-pep581

## Twitter threads

* https://twitter.com/mariatta/status/1128531347914407936 : Tweet about PEP 581 being approved, with some comments/concerns/suggestions
* https://twitter.com/VictorStinner/status/1128476712084410373 : Tweet about PEP 581 being approved, with a comment about not being able to assign issues to non-coredevs

## Blog posts

* [Python Core Sprint 2018: Part Two / PEP 581](https://mariatta.ca/core-sprint-2018-part-2.html#pep-581) (Sep 2018, Mariatta's blog)
* [Mariatta Wijaya: Let's Use GitHub Issues Already!](https://pyfound.blogspot.com/2019/05/mariatta-wijaya-lets-use-github-issues.html) (May 2019, PSF blog)

## Other links

* [Karthikeyan test tracker on GitLab](https://gitlab.com/tirkarthi/python-bugs/-/issues) (from [a python-dev mail](https://mail.python.org/archives/list/python-dev@python.org/message/O7MIL7DLR6HZ7XMZIUTZE6VWY2ROCY4F/))



# Other instances

In addition to bugs.python.org, we are also hosting two other instances:

## Jython

* Jython is already using [GitHub issues](https://github.com/jython/jython/issues)
* Still has a legacy instance of Roundup at https://bugs.jython.org/ (bjo)
* [Thread on the Jython ML that suggests to switch to GitHub issues but keep bugs.jython.org around](https://sourceforge.net/p/jython/mailman/jython-dev/thread/CAOhO%3DaNp9oPkMwO58vK0L5gqL_nG8UD0mWom%3D1XLqxdbyfU34w%40mail.gmail.com/#msg37020624)
* They are using [the form on python.org](https://www.python.org/psf/contrib/contrib-form) to sign the CLA and bpo to check it.
* They would be fine with a mostly read-only bjo

## Roundup

* The tracker for Roundup is at https://issues.roundup-tracker.org/
* They are not planning to migrate
* They depend on us for hosting, unless they find another place
