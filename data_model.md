

## Endpoints:
/ - Mein Gitstream: Aggregation aller Timelines, die für mic hinteressant sind.
/foo - Timeline User | Orga
/foo/bar - Timeline Projekt
/foo/~0815 - Permalink of a posting
/foo/bar/~0815 - Permalink of a posting

## Blog Post - Data
* Body (*Markdown*) - The contens of a post
* Author (*string*) - The git username
* Timeline (*string*) - The User/Organisation | Projekt
  /foo/bar
  foo := user | orga
  bar := projekt
* Created, Updated (*Timestamp*)
* Permalink (*string*) - The Permalink*

## Blog Post - View:
* Body
* Author with image an link
* Time since creation
* Link to the origin
* Images and videos should be embeddable
* The Title my be part of the markdown


