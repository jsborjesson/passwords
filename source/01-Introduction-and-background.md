# Passwords - subject for deprecation?

_By Jimmy Börjesson (jb222rw)_

## Introduction

At the time of writing, the Heartbleed scandal is just about to blow over. Its effects was not
disastrous for me, though no less than annoying. I had unique, randomly generated passwords on every
site, and they were all stored in a password manager with a locally encrypted database. Even if it
was transfered over a vulnerable connection, the key has never been transfered and just one layer of
the encryption would have been endangered.

Changing out all of my passwords took less than an hour, my password manager made it very simple to
generate new ones, but I still had to go through the forms on every single website. I was feeling
pretty happy with myself, this process would have taken me more than three times as long a year ago.

I then remembered that my mother would have to go through this process as well, but her password
manager was a paper notebook. It was her compromise when I argued that she needed unique passwords,
but she thought password managers were too complicated. Suddenly I wasn't feeling so good about
being able to switch out my passwords on 30 different accounts so quickly. I knew that the few
accounts she needed to change was going to cause her more trouble than all of mine - maybe password
managers are not the perfect solution to this problem.

Many people will use the same password everywhere\[6\], and it will probably be a bad
password\[1\]. We can try to educate people, making them aware that they need to
think about security and that they should install extra software for keeping all of their passwords
safe, but they just want to get into their accounts as smoothly as possible, and be confident that
nobody else will. Passwords are putting a lot of the responsibility of account security on the user.
**Is this really their problem?**

## Background

### Question

**Why are bad passwords so common? Is this a problem with the users, or a problem with passwords as
as a technology?**

### Purpose

People are generally bad at using good passwords\[1\]. The purpose of this paper is to
explore why that is the case, and explore the alternative forms of authentications.

### Previous studies

There has been many articles\[1\]\[2\]\[3\] that measure the type of
passwords people use, but the general purpose seems to be to educate people to come use better
passwords. This paper puts the responsibility on the developers instead.

One common technology is OAuth\[4\], which uses another account as authentication. This prevents you
from having to remember yet another password, and often also from having to type it in again, since
you tend to use services you rarely log out of for this. There has been some suggestions of other
methods as well, like using email as authentication\[5\]. Of course in the future we might have
access to more technology (like retina scanners, more accurate facial recognition, et cetera), but
today there does not seem to be an option that is as simple to implement as passwords.

## Keywords

passwords, security, safety, authentication
