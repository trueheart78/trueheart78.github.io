---
layout: page
title: Resume
permalink: /resume/
update: 2018-08-30
---

# Hi, I'm Josh.

[Strengths](#strengths) |
[Experience](#experience) |
[Side Projects](#side-projects) |
[Open Source](#open-source-contributions) |
[Work History](#work-history) |
[Education](#education)

![refresh if you don't see a 'taylor waving.gif'][taylor-hi]

I love writing Ruby & Go :sparkling_heart:, rocking out to Taylor Swift :notes:, and using gifs to
make others smile :smile:.

I'm looking for a light-hearted, collaborative team, that could benefit from my strong back-end
development skills.

## Strengths

[:back: to the top][top]

![refresh if you don't see a 'taylor swift strong.gif'][taylor-strong]

* I :heart: Ruby & Go. I love the communities, and the languages.
* I aspire to be an excellent software craftsman.
* I enjoy writing good documentation, as I find it highly valuable.
* I think of myself as a very good mentor.
* I always consider future maintainers.
* I desire to contribute to open source.
* I was called "Gif Captain" by my manager.

## Experience

[:back: to the top][top]

![refresh if you don't see a 'taylor swift whats up.gif'][taylor-whats-up]

* Five years of Ruby.
* Five years of being a huge Taylor Swift fan.
* Thirteen years of PHP, MySQL, and JavaScript.
* Ten years of managing critical on-line systems.

## Side Projects

[:back: to the top][top]

![refresh if you don't see a 'taylor award dance.gif'][taylor-award-dance]

I’ve written some fun things over the past few years.

### I :heart: Ruby

My somewhat active blog. I post about development-related topics, from Ruby and Rails, to Heroku
and command-line tools. Uses Jekyll so I only have to use markdown, and is hosted on GitHub pages.

* Site: [iheartruby.com][iheartruby]
* Source: [GitHub][iheartruby-source]

### Dropbox Gif Linker (Formerly my Gifs Gem) :gem:

I have a lot of gifs in my Dropbox, so I wanted a simpler way to get a publicly viewable URL. It
connects to Dropbox’s api and creates a public share, caches that in a key-value store (in said
Dropbox), and provides an embeddable URL. Great for bypassing HipChat’s 2mb animation limit, as well
as for markdown support.

Originally written in Ruby, now written in Go.

* Go Source: [GitHub][dropbox-gif-linker-source]
* Ruby Source: [GitHub][gifs-gem-source]

### Caring for Karen Sue :credit_card:

A charity-focused site, built in Ruby and using Sinatra as the web framework. I started this during
my early days of Ruby.

* Site: [caringforkarensue.com][caringforkarensue]
* Source: [GitHub][caringforkarensue-source]

### Book Notes :notebook:

Where I put notes from books I’ve read. Makes it much easier to study across machines, and provides
a handy, searchable reference.

* Source: [GitHub][book-notes-source]

### Book Notes Generator :repeat:

Extracted from the early version of my Book Notes, it reads a YAML file (example link) and generates
the core markdown files for the chapters and sections. It also places them directly into the above
Book Notes project in a new folder, with a handy Readme link provided at the end. _I should really 
change this into a gem or a binary_.

* Source: [GitHub][book-notes-generator-source]

### Dotfiles :file_folder:

Sharing dotfiles between my linux laptop, my work Mac, and a CentOS VM, I saw a need to make this
as seamless as possible. It’s managed via git for easy updates, and includes a script to check for 
the status of existing symlinks and creates/corrects those that it identifies. Scripting is done
via Ruby.

* Source: [GitHub][dotfiles-source]

### Game Selector :space_invader:

A Ruby application with the Sinatra framework that accesses the `/games` endpoint of my blog, and 
uses Nokogiri to parse lists, caches it in Redis for five minutes, and returns a randomly selected
title.

* Site: [blog.trueheart78.com/games#unplayed][game-selector-example]
* Source: [GitHub][game-selector-source]

### Dead To Us :skull:

A goof project to display team members at CMM that are "dead to us" (read: anyone that has left the
team). Originally a Rails 5 project, I converted it to a basic HTML site on AWS S3 for faster load
times.

* Site: [deadtous.com][dead-to-us]
* Source: [GitHub][dead-to-us-source]

### TimeToTaylor :clock7:

This consists of an AWS Lambda that I wrote in Go, and a web page on AWS S3 that interacted with it
using an AWS API Gateway endpoint. They don't talk to each other anymore now that the showtime has
passed, but I'm keeping it around for the next one.

* Site: [timetotaylor.com][time-to-taylor]
* API Endpoint: [time-to-taylor-endpoint][time-to-taylor-endpoint]
* Site Source: [GitHub][time-to-taylor-html-source]
* Lambda Source: [GitHub][time-to-taylor-go-source]

### Alexa Alerter :rotating_light:

A Ruby application with the Sinatra framework that receives a message from an Alexa skill (_"tell
Josh I need them"_), and uses Twilio to both call and text me.

* Source: [GitHub][alexa-alerter-source]

### Alexa Food Tracker (WIP) :spaghetti:

A Ruby application with the Sinatra framework that will integrate with an Alexa skill to provide
answers to questions like, "What do we have for snacks?", and "What do we have for dinner?".
Currently in the process of learning Elm for the desired front-end that will be required. _I may
just use Rails' CRUD for now._

* Source: [GitHub][alexa-food-tracker-source]

## Open Source Contributions

[:back: to the top][top]

![refresh if you don't see 'taylor swift epic.gif'][taylor-epic]

### Turbolinks

Discovered an IE8-related bug in Turbolinks and submitted a PR to the project. It was merged later that same day.

* Pull request: [GitHub][turbolinks-pr]

## Work History

[:back: to the top][top]

![refresh if you don't see a 'taylor mountain.gif'][taylor-mountain]

### CoverMyMeds (2015 to present)

* Mentored multiple software apprentices.
* Ushered in a gif revolution.
* Primary maintainer for the JWT authentication projects.

### Vya (2007 to 2015)

#### Senior Software Developer (2010 to 2015)

* Migrated the marketing portal codebase to run on both Windows Server 2008 and CentOS.
* Transitioned the codebase version control system from SVN to Git.
* Became a Zend Certified Engineer for PHP 5.3 – [License ZEND022958][php-cert]

#### Internet Application Developer (2007 to 2010)

* Created a dynamic reporting system to offload work from support.
* Migrated the marketing portal codebase to from Mac OS X Server to Windows Server 2008, in production.
* Introduced the use of coding standards.

### Self-Employed Contractor (2004 to 2007)

* Maintained the _Advanced Office System (AOS)_ REALTOR-focused showing system.
* Worked with REALTOR-based listing services to create custom data imports for clients.
* Created an integrated online support system for managing user-submitted tickets.

## Education

[:back: to the top][top]

![refresh if you don't see a 'taylor swift studying.gif'][taylor-studying]

Associate of Computer Science in Software Applications and Programming, ITT Technical Institute, 2004

## Thanks for Reading!

[:back: to the top][top]

![refresh if you don't see a 'taylor heart.gif'][taylor-heart]

[top]: #hi-im-josh
[iheartruby]: http://iheartruby.com
[iheartruby-source]: https://github.com/trueheart78/trueheart78.github.io
[dropbox-gif-linker-source]: https://github.com/trueheart78/dropbox-gif-linker
[gifs-gem-source]: https://github.com/trueheart78/gifs
[caringforkarensue]: https://caringforkarensue.com
[caringforkarensue-source]: https://github.com/trueheart78/CaringForKarenSue2014
[book-notes-source]: https://github.com/trueheart78/book-notes
[book-notes-generator-source]: https://github.com/trueheart78/book-notes-generator
[dotfiles-source]: https://github.com/trueheart78/dotfiles
[game-selector-example]: http://blog.trueheart78.com/games/#unplayed
[game-selector-source]: https://github.com/trueheart78/game-selector
[dead-to-us]: https://www.deadtous.com/
[dead-to-us-source]: https://github.com/trueheart78/dead-to-us-html
[time-to-taylor]: http://timetotaylor.com
[time-to-taylor-endpoint]: https://gvitovaif0.execute-api.us-east-2.amazonaws.com/development/showtime
[time-to-taylor-html-source]: https://github.com/trueheart78/timeToTaylor.com
[time-to-taylor-go-source]: https://github.com/trueheart78/timeToTaylor
[alexa-alerter-source]: https://github.com/trueheart78/alexa-alerter
[alexa-food-tracker-source]: https://github.com/trueheart78/alexa-food-tracker
[github]: https://github.com/trueheart78
[turbolinks-pr]: https://github.com/turbolinks/turbolinks/pull/284
[php-cert]: http://www.zend.com/en/yellow-pages/ZEND022958
[contact-converter]: https://github.com/trueheart78/Contacts-To-PDF
[caring-for-karen]: https://caringforkarensue.com/
[caring-for-code]: https://github.com/trueheart78/CaringForKarenSue2014
[email-me]: mailto:iloveyourresume@nym.hush.com
[taylor-hi]: /assets/images/resume/taylor-hi.gif
[taylor-strong]: /assets/images/resume/taylor-strong.gif
[taylor-whats-up]: /assets/images/resume/taylor-whats-up.gif
[taylor-award-dance]: /assets/images/resume/taylor-award-dance.gif
[taylor-epic]: /assets/images/resume/taylor-epic.gif
[taylor-studying]: /assets/images/resume/taylor-studying.gif
[taylor-mountain]: /assets/images/resume/taylor-mountain.gif
[taylor-heart]: /assets/images/resume/taylor-heart.gif
[taylor-work-it-jlo]: /assets/images/resume/taylor-work-it-jlo.gif
[taylor-call-me]: /assets/images/resume/taylor-call-me.gif