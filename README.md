## Project Library
A toy project to manage books I have read in 2020.

[Demo](https://library-6b733.firebaseapp.com) (It may be empty when the server is down).

![demo](demo.gif)


### Tech Stack
- Language: JavaScript (HTML/CSS)
- Project Setup: Vanilla JS
- Database: ~localStorage~ FireBase

### Todo
- CRUD (no Update)
  * [x] Create
  * [x] Read (`populate()`)
  * [x] Delete (right click)
- Card
  * [x] Toggle read status on click
- Card form
  * [x] file chooser for the book cover
  * [x] add `default.png` when img file is not specified
- Database
  * [x] local storage
- Filter
  * [x] filter by `read`, `reading`, `not-yet`
- any more ideas?

### Progress
2020-10-27
- Firebase Reading DB complete
- Firebase Storage read complete

2020-10-26
- Firebase setup

2020-10-16
- Filtering added.
  + Can filter books by `read`, `reading`, and `not-yet`.
  + Code refactored.
- Add book counts.

2020-10-12
- localStorage added.
- Toggling card's states added.
  + change states of the card from `read`--`reading`-`notyet` and back to `read`.
- Remove card feature added.

2020-10-11
- Can add a new book (card).
- Can toggle cards to different states.
  + `read` to `reading` to `not-yet` and back to `read`.
- Google fonts added.

2020-10-10
- A form to add a new book added.
- A default book image added.
