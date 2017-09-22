---
layout: slide-deck
title: "jQuery—Javascript simplified"
desc: "An introductory slide deck explaining what jQuery is and how it helps us do Javascript-y things."

slides:
  - type: super-big-text
    content: |
      **jQuery—Javascript simplified**

  - content: |
      ## jQuery is Javascript

      - Simplifies the interface to HTML
      - Provides a bunch of already made functionality
      - *Not required to do HTML manipulation*

      **jQuery is essentially just a bunch of pre-written Javascript**

  - content: |
      ## It’s all money from here

      Everything that is jQuery is inside the `$()` function

      Use the `$()` function to select & manipulate HTML

  - content: |
      ## Select & go

      jQuery follows a simple order:

      1. Select something in the HTML
      2. Manipulate that HTML element

  - content: |
      ## Select with CSS

      jQuery (and Javascript) use CSS selectors to grab things in the HTML document

      - `ul`, `h1`, `div`
      - `.dino-list`, `.bones`
      - `#stego`
      - `main > p:first-child`
      - etc.

  - content: |
      ## Simplifies user interaction

      Much is based on user events:

      - `click`, `mousemove`, `doubleclick`, etc.

      jQuery makes this easy:

      ```js
      $('.btn').on('click', function () {
        // Do something
      });
      ```

  - content: |
      ## Videos & tutorials

      - [Document object model ➔](/topics/dom/)
      - [Javascript cheat sheet ➔](/topics/javascript-cheat-sheet/)

---
