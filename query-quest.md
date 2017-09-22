---
layout: slide-deck
title: "’Query quest"
desc: "An activity to help understand online documentation by presenting a series of quests that can only be solved by digging through the documentation."

slides:
  - type: super-big-text
    content: |
      **’Query quest**

  - content: |
      ## What & why

      Since jQuery is a bunch of pre-written Javascript we need to know what’s available.

      Searching through & understanding documentation is a critical component of being a developer.

      **Effectively finding what you need will help you write the code you want.**

  - content: |
      ## Set up

      1. Form into pairs
      2. Get a pencil & a piece of paper
      3. Work through each problem by finding a suitable pre-built function in the jQuery documentation
      4. *We’ll discuss the answers at the end*

      ### [https://api.jquery.com/ ➔](https://api.jquery.com/)

  - type: timer
    minutes: 12

  - type: code
    numbered: 1
    before: |
      ### Find a jQuery function to make the following change in the HTML:
    html: |
      <a class="btn">Button!</a>

      ⬇

      <a class="btn btn-ghost">Button!</a>

  - type: code
    numbered: 2
    before: |
      ### Find a single jQuery function that could make both these changes:
    html: |
      <a class="btn">Button!</a>

      ⬇

      <a class="btn btn-ghost">Button!</a>

      ⬇

      <a class="btn">Button!</a>

  - type: code
    numbered: 3
    before: |
      ### Find a jQuery function to add new HTML to the following location:
    html: |
      <ul>
        <li>List item</li>
      </ul>

      ⬇

      <ul>
        <li>List item</li>
        <li>New list item</li>
      </ul>
    html_lines: "9"

  - type: code
    numbered: 4
    before: |
      ### Find a jQuery function to make the following change in the HTML:
    html: |
      <img src="images/thing.jpg" alt="">

      ⬇

      <img src="images/thing-big.jpg" alt="">

  - type: code
    numbered: 5
    before: |
      ### Find a jQuery function to make the following change in the HTML:
    html: |
      <div class="tab" hidden></div>

      ⬇

      <div class="tab"></div>

  - type: code
    numbered: 6
    before: |
      ### Find a jQuery function to change all of these items individually:
    html: |
      <ul>
        <li>List item</li>
        <li>List item</li>
        <li>List item</li>
      </ul>

      ⬇

      <ul>
        <li>List item 1</li>
        <li>List item 2</li>
        <li>List item 3</li>
      </ul>

  - type: code
    numbered: 7
    before: |
      ### Find a jQuery function that will wait for a user to click on this element:
    html: |
      <button id="the-btn">Click me!</button>

  - type: code
    numbered: 8
    before: |
      ### Find a jQuery function that will download a separate HTML file and insert it:
    html: |
      <div class="tab"></div>

      ⬇

      <div class="tab">
        <h2>Stegosaurus</h2>
        <p>The Stegosaurus is know for its large back plates and spiky tail.</p>
      </div>

  - type: code
    numbered: 9
    before: |
      ### Find a jQuery function that gets the information inside the <div>:
    html: |
      <div class="tab">
        <h2>Brontosaurus</h2>
        <p>The Brontosaurus is controversial dinosaur—both real and not real.</p>
      </div>
    html_lines: "2-3"

  - type: code
    numbered: 10
    before: |
      ### You’ve selected the <h2> with jQuery, find a function that gets the surrounding element:
    html: |
      <div class="tab">
        <h2>Ankylosaurus</h2>
      </div>
    html_lines: 1

  - type: code
    numbered: 11
    before: |
      ### Find a jQuery function that gets the information a user typed into the input field:
    html: |
      <label for="name">Name</label>
      <input id="name">
    html_lines: 2

  - type: code
    numbered: 12
    before: |
      ### Find a jQuery function that will wait for the user to send the form information:
    html: |
      <form method="post" action="contact.php">
        <div>
          <label for="name">Name</label>
          <input id="name">
        </div>

        <button type="submit">Send</button>
      </form>
---
