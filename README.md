# MGT858 - Database Systems, Spring 2021

Hello 👋👋! This is the "about" page for MGT858 "Database Systems" at the Yale
School of Management in Spring 2021. This is the first time I'm teaching this
course and I'm super jazzed about it 🤩🥳. This is a living document — you can
track changes by looking the git commits. 

Jump to [Covid info](#covid).

This repo tracks information and policies for our
class: Yale's MGT858 in the Fall of 2020.

## Overview

| Key                     | Value                                                                     |
| ----------------------- | ------------------------------------------------------------------------- |
| 🎓 Course number           | MGT858                                                                    |
| 📚 Units                  | 2 units in Yale College and equivalent elsewhere                          |
| 👥 Enrollment             | Open to any student at Yale                             |
| 🕓 Meeting Time | Tues. & Thurs. 10:30-11:40 AM EST, March 23 - May 4, 2021                 |
| 🏫 Meeting Location | Some room in [Evans Hall](https://map.yale.edu/place/building/EVANS?) |
| 💻 Zoom link       | See Canvas for now. Link is in there.                                     |
| 📅 Calendar | [Yale SOM Spring 2021 Academic Calendar](https://som.yale.edu/programs/mba/integrated-curriculum/the-academic-calendar#spring2021) |
| 🌐 Website         | http://858.mba (offline sometimes until semester begins)                  |


MGT858 introduces enrolled students to the database systems used in modern
technology companies.  You will emerge from this course an SQL ninja,
well-prepared for tech sector roles including data scientist, product manager,
and technical program manager.  The first half of the course covers relational
databases (those that use SQL, generally) and the latter half covers other
kinds of systems including noSQL, distributed, full-text, columnar, tick,
caching, graph, and blockchain-based databases. We will discuss the role of
these database systems in customer-facing products and also how these databases
are used to make data-driven management decisions.  The coursework includes
bi-weekly homework assignments and a final examination, all of which require
writing code and must be submitted using the git version control system.
(Experience with git is not required; however, some experience programming is
necessary. The particular language does not matter.) Students can expect to
spend perhaps six hours per week on homework.


I don't know how many students will enroll in this course. As of Nov 24th, 2020,
65 SOM students are registered for the course. I suspect we'll get some non-SOM
students who wish to enroll in the course and also some SOM students who drop.
(Yale College students are welcome to enroll and will require a form signed by
both Kyle Jensen and your residential dean.)
I likely will *not* accept shoppers or auditors. The number of admitted students
will be affected by the room to which we're assigned and, of course, by the
social distancing practices in place at the time.

## <a name="covid"></a>Covid dystopia clusterfarce 2019/2020/2021 🦠😷🔬🌡 

Yale SOM is doing its utmost to ensure you, students, have the best
possible experience during the Covid-19 pandemic. I do not know right
now what form teaching will take in Spring-2. I told the registrar that
I would teach in "hybrid" mode in which I will teach from Evans every
day, knowing that some of you will join online (by Zoom) and some of you
will come to Evans as you are willing and able. I am committed to ensuring
you have a fantastic experience no matter what mode of learning
we find ourselves.

Please take a moment to review the [student accessibility
services](https://sas.yale.edu/faculty/online-courses-and-covid-19-response)
information about COVID-19. If you have accessibility needs, please let me know
so that I can meet them!

## How to use this document/repo

Because our class info and policies are tracked using git, you can see if and
how they change over the course of the semester. Further, you have the ability
to make changes yourself---please send me a pull request. Similarly, if you
feel these documents are lacking, please open an
"[issue](https://github.com/yale-mgt-858-spring-2021/about)" on GitHub for this
repo and we'll address the issue. Finally, because our git repo is hosted on
GitHub, you can easily receive push notifications of changes to this repo.
(Woot!)

## Office hours

The office hours for each of the teaching staff is shown
below. Though, if you are reading this before the start of
the semester, it is possible some staff are missing because
they did not yet determine their schedule. Office hours will
likely be held virtually.

Feel free to send an email if these times do not work for you.

| Person          | Hours            | Location/URL                                                                |
| --------------- | ---------------- | ----------------------------------------------------------------------- |
| Kyle Jensen     | TBD | TDB |
| TAs TDB   | TBD | TDB |

## Development environment

You will need to write code a lot of code this semester, mostly domain-specific
query languages like [PostgreSQL-flavored SQL](https://www.postgresql.org/docs/), the [ElasticSearch
DSL](https://www.elastic.co/guide/en/elasticsearch/reference/current/query-dsl.html), and
the [Redis query commands](https://redis.io/commands). It is possible you'll need to write
code in a more general programming language like [Python](https://www.python.org/), [Ruby](https://www.ruby-lang.org/en/),
or [Go](https://golang.org/). I haven't finished the homework assignments, so I don't know
yet. I'm weary to make you write too much code because I want to make the class manageable
for those with limited computer science backgrounds. But, I also want you to learn about
database systems 😜 and so some coding will be required. 

Most of the homework assignments and the final exam will require using the [git
version control system](https://git-scm.com/) for submission. You'll sign up
for GitHub, join the [yale-mgt-858-spring-2021
organization](https://github.com/yale-mgt-858-spring-2021) on GitHub and
submit your assignments (in part) by pushing up code to GitHub. Usually I'll
give you some starter code like empty `.sql` files with examples queries.
When you complete your assignments, you'll make git commits and push those
commits up to GitHub so that I can download your answers and test them.
Obviously this requires knowing a little bit of git. I'll point you to some
git tutorials, but I'm not going to teach git in class. You are forewarned
😉.

You can complete the homework assignments on any kind of computer: Windows,
Mac, Linux, whatever. You'll almost certainly need to install some software in
order to do so. Obviously you'll need git. You might also need _ clients_ for
different database systems. For example, you will almost certain need a
PostgreSQL client or a Redis client.  The `$XYZ` _client_ is a piece of
software that connects to the `$XYZ` _server_ in order to send the server
queries (or other commands) and interpret the responses. (Here, `$XYZ` is a
stand-in for PostgreSQL, Redis, MongoDB, etc.) Now, it could be that you don't
want to set up the `$XYZ` client software on your computer, which would be totally resonable: it
can be a pain in the rear-end. For this reason, I will give each student an
[AWS Cloud9](https://aws.amazon.com/cloud9/) environment, for which I will pay
🤑.  Cloud9 is an integrated development environment that includes a shell and
a code editor running on a Linux virtual machine. If you choose to use C9, rad.
But, it's not a panacea; if you use Cloud9 you'll be on a Linux environment so
you might have to learn some Linux-foo 🐧. I will use Cloud9 for all my 
tutorials (eg. videos I make to assist you with homework) and I will offer
guidance on how to set up your Cloud9 environment in order to complete homework.
But, in general I will _not_ offer guidance on how to install the `$XYZ` client/server
on your personal computer.

You can access Cloud9 through the link in your Dashboard on the [class
website](http://858.mba).  Therein you should see credentials for logging into
Cloud9. You'll need to supply an account number, username, and password. All
that is in your dashboard under the "user secrets" section. (I won't create the
Cloud9 environments until the beginning of the semester.)

## Preparing for the course

I am receiving a few emails from students about how best to prepare for the
class. There's a few ways to think about doing so. One is to prepare narrowly
for the content you're going to encounter. For SQL, in my person opinion, the
best way to do so is going through the exercises at
[SQLBolt](https://sqlbolt.com/).  I think that website is fantastic and it's
part of the assigned reading in class. For the other database systems we'll
use, the answer is less clear.  You can read about
[ElasticSearch](https://github.com/elastic/elasticsearch) (the reprentative
full-text search database we'll use);
[ClickHouse](https://github.com/ClickHouse/ClickHouse) (the representative
columnar store we'll use); [Redis](https://github.com/redis/redis) (the
representative caching database we'll use);
[MongoDB](https://github.com/mongodb/mongo) (the representative noSQL
database we'll use); and [Neo4j](https://github.com/neo4j/neo4j) (the
representative graph database we'll use).

A second way to prepare is to level-up your computer skills in general,
particularly your *nix skills. A good resource for doing so is [MIT's missing
semester course](https://missing.csail.mit.edu/).

Finally, you might think about getting your personal computer set up for
writing code. That usually starts with choosing a package manager
([homebrew](https://brew.sh/) on Mac OS) and
[Chocolatey](https://chocolatey.org/) on Windows and choosing a [good code
editor](https://github.com/collections/text-editors). I use
[VSCode](https://code.visualstudio.com/) and [NeoVim](https://neovim.io/).

Also 😜, you'll want to be familiar with [git](https://git-scm.com/). You can
find [many tutorials
online](https://medium.com/@javinpaul/top-10-free-courses-to-learn-git-and-github-best-of-lot-967aa314ea).
Your use of git this semester will be super simple because you won't generally
have collaborators. If you like, you can use a [git gui](https://git-scm.com/downloads/guis).
I use GitHub Desktop often, mostly for line-by-line staging of changes.

