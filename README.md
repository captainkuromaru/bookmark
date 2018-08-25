# (yet another) bookmark

Yet Another bookmarking system done in PHP (and mariadb).

This is basically just something I use to learn about PHP (without using frameworks)

## goals

The system is a simple UI where a user can add new bookmarks for articles etc, which are added to (relational) DB and
then showed on user's bookmarklist page. Users can decide for every new bookmark whether they want it public (shown on public bookmarklist page for every user) or private.

## possible feature in future

- reading mode, where you can read simplfiied articles (stripped of unnecessary elements from source page) in a spirit of instapaper and similar services
- RSS for public bookmarklist

## process

I intend to use simple development process of MoSCoW, to keep on track of releasing the first version.

### v. 0.1
This is going to be very rough draft of the system, with almost no design decisions. You can think of it as a proof of concept.
(Imagine form with a few fields and a button... and then a list of your bookmarks)
