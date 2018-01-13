# kottans_frontend

## Task 0

1. [How to use Git and GitHub](https://www.udacity.com/course/how-to-use-git-and-github--ud775)

   * All stuff about forking was new to me.

   * Not only git status but also git branch can show you where you are (on what branch).

   * The whole idea: why do we need staging area at all. It was a feeling that it could be useful, but not so clear how exactly.

2. [try.github.io](https://try.github.io/levels/1/challenges/1)

   * The fact that we can use `-a` option on `git commit` was new to me. It auto removes deleted files with the commit.
     `git commit -am "Delete stuff"`
     
   * It was nice to hear that merge conflicts aren't that scary, you just need to decide which code to keep. (And where to read about this.)
   
   * Force delete for branch if you don't want this feature anymore. (When `git branch -d bad_feature` is not enough.)
   You can either add the `--force (-f)` option or use `-D` which combines `-d -f` together into one command.
   
## Task 1

1. [Linux Command Line Basics](https://classroom.udacity.com/courses/ud595)

   * All stuff about virtual machine was new to me. It was the first time using VirtualBox and Vagrant. 
   
   * One more interesting thing was thinking about what a shell command really is. How is it similar to, and different from a function in JavaScript.

2. [Configuring Linux Web Servers](https://classroom.udacity.com/courses/ud299)

   * It was a completely new experience for me.

   * Funny fact: if you didn't halt your virtual machine from the previous course you would have a bunch of troubles in this one. So make sure to do that.
   
3. [Networking for Web Developers](https://classroom.udacity.com/courses/ud256)

   Themes considered in this course wasn't completely new to me, but I definitely didn't know them so deep. 

   Some new things to name:

   * && in the command line, which means "run the first program; then if that succeeds, run the second program";

   * IPv6 addresses;

   * how routers drop packets when the link they are trying to send on is too busy, and TCP slows down if packets are dropped;

   * how traceroute works.

4. HTTP: The Protocol Every Web Developer Must Know - Part 1

   * The new thing was 1xx status codes;

   * the surprising thing was that PUT and DELETE verbs are sometimes considered as specialized versions of the POST verb, and they may be packaged as POST requests with the payload containing the exact action: create, update or delete;

   * the things that I intend to use in the future are tools to view HTTP traffic (by the way I tried another one great tool - Postman, an HTTP client).

5. HTTP: The Protocol Every Web Developer Must Know - Part 2

   * The new thing was persistent connections, which in combination with parallel connections were implemented to reduce connection-establishment delays;

   * (I don't know why it was surprising, it's kinda logical.) Nevertheless, the surprising thing was that just because a cached copy has expired doesn't mean that the server actually has newer content. So I agree, the combination of document expiration and server revalidation should be a very effective mechanism;

   * the things I intend to use in the future is the Cache-Control header.

## Task 2

0. [What is Version Control](https://classroom.udacity.com/courses/ud123)

   At the beginning of this course, I had thoughts like "Ok, it's a lot of already known stuff here." But starting from the lesson three it became clear, that it will be a lot of new stuff too :).

   Some things to name:

   * -w flag for `git log` (and all that `git log` vs. `git show` stuff);

   * `git tag` was a new thing to me (before I only knew it exists);

   * some merging nuances and Relative Commit References;

   * the complete lesson six with all these `commit --amend`, `git revert` and `git reset`. This one was my favorite!

1. [GitHub & Collaboration](https://classroom.udacity.com/courses/ud456)

   This course was really intense. And it was clear from the very beginning, it will be a ton of new stuff.

   Some things to name:

   * `git pull` vs. `git fetch`;

   * stuff in lesson two about Reviewing Existing Work (`--author` flag to `git log` to filter the commits by the provided author; `--grep` flag to `git log` to filter commits, etc.);

   * "Stay in sync with source project" and "Squash Commits" from lesson three.

2. Yeah, I'm going to send a message in gitter channel with the link to my repo :)

## Task 3

* [Intro to HTML & CSS](https://classroom.udacity.com/courses/ud001)

  The majority of the information in this course was already well known. But still, I found out, I have never used  `<figure>` element before. And also I've got a few new useful bookmarks in my browser.
  
