# Based Lyrics Website

This is a simple lyrics website where users can submit lyrics here for credit.
There are no ads, trackers, cookies or JavaScript.

## Ways to contribute

- By adding a lyrics.
- Fix errors in lyrics or add minor improvements.

## Rules for submission

- Model submission files after [example.md](example.md). Put them in `src/`.
- Lyrics should start with a title, with a single `#`, *on the first line*. No
  empty line at the top, not trailing line at the end. The file needs to be `\n`
  terminated in inux-fashion (if you're on linux you don't need to care, it
  should be automatic).
- File names should be the name of the dish with words separated by hyphens
  (`-`). Not underscores, and definitely not spaces.

**If you fail to do these things, I will close your submission and you will have to resubmit. I am tired of having to fix more than 50% of submissions.**

### Tags

You can (and should) add tags at the end of your lyrics. The syntax is:
```
;tags: tag1 tag2 tag3
```

The tag line should be a single line, at the end of the markdown file, preceded
by a blank line.

Add between 1 and 4 tags, **prioritize existing tags**. As a general guideline,
add the band name, album name, genre and sub-genre, and possibly the artist
name.

## About the site

The front page, for now, will just be a list of lyrics automatically generated
from the content of `src`.
As more articles are added, the site will be reorganized, categorized
or will implement server-side scripting or searches.
This is not necessary yet though.

## License

This website and all its content is in the public domain.
By submitting text or images or anything else to this repository,
you waive any pretense of ownership to it,
although you are welcome and recommended to give yourself credit
at the bottom of a submitted page for you adding it
(including personal or donation links).
