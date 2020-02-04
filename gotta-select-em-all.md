---
layout: slide-deck
title: "Gotta select ’em all"
desc: "An activity to remind everyone of all the amazing & complex CSS selectors that exist to help understand choosing elements in JavaScript."

slides:
  - type: super-big-text
    content: |
      **Gotta select ’em all**

  - content: |
      ## What & why

      To code JavaScript (& jQuery) we need to understand all the complex CSS selectors.

      JavaScript uses CSS selectors to choose what HTML we want to manipulate.

      **Effectively understanding CSS selectors means being able to manipulate HTML.**

  - content: |
      ## Set up

      1. Form into pairs
      2. Get a pencil & a piece of paper
      3. Work through each chunk of HTML
        <br>& write the CSS selector to grab it
      4. *We’ll discuss the answers at the end*

  - type: code
    numbered: 1
    html: |
      <a class="btn">Button!</a>
    html_lines: 1

  - type: code
    numbered: 2
    html: |
      <div>
        <label for="name">Name</label>
        <input id="name">
      </div>
      <div>
        <label for="email">Email</label>
        <input type="email" id="email">
      </div>
    html_lines: 3

  - type: code
    numbered: 3
    html: |
      <ul>
        <li>List item</li>
        <li>List item</li>
        <li>List item</li>
        <li>List item</li>
        <li>List item</li>
        <li>List item</li>
        <li>List item</li>
        <li>List item</li>
      </ul>
    html_lines: "3,5,7,9"

  - type: code
    numbered: 4
    html: |
      <ul class="list-group">
        <li>List item</li>
        <li>List item</li>
        <li>List item</li>
      </ul>

      <ul>
        <li>List item</li>
        <li>List item</li>
        <li>List item</li>
      </ul>

      <ol class="list-group">
        <li>List item</li>
        <li>List item</li>
        <li>List item</li>
      </ol>
    html_lines: "2,3,4,14,15,16"

  - type: code
    numbered: 5
    html: |
      <nav>
        <ul>
          <li><a href="#">Link</a></li>
          <li><a class="current" href="#">Link</a></li>
          <li><a href="#">Link</a></li>
        </ul>
      </nav>

      <div class="tab">
        <h2>Heading</h2>
      </div>
      <div class="tab current">
        <h2>Heading</h2>
      </div>
      <div class="tab">
        <h2>Heading</h2>
      </div>
    html_lines: "12"

  - type: code
    numbered: 6
    html: |
      <ul class="list-group">
        <li>
          <h2>Heading</h2>
          <ol class="list-group">
            <li><h2>Heading</h2></li>
            <li><h2>Heading</h2></li>
            <li><h2>Heading</h2></li>
          </ol>
        </li>
        <li>
          <h2>Heading</h2>
          <ol class="list-group">
            <li><h2>Heading</h2></li>
            <li><h2>Heading</h2></li>
            <li><h2>Heading</h2></li>
          </ol>
        </li>
      </ul>
    html_lines: "3,11"

  - type: code
    numbered: 7
    html: |
      <div class="tab">
        <h2>Heading</h2>
      </div>
      <div class="tab" hidden>
        <h2>Heading</h2>
      </div>
      <div class="tab" hidden>
        <h2>Heading</h2>
      </div>
    html_lines: "4,7"

  - type: code
    numbered: 8
    html: |
      <div class="tab" aria-hidden="true">
        <h2>Heading</h2>
      </div>
      <div class="tab" aria-hidden="false">
        <h2>Heading</h2>
      </div>
      <div class="tab" aria-hidden="true">
        <h2>Heading</h2>
      </div>
    html_lines: "4"

  - type: code
    numbered: 9
    html: |
      <a href="#" rel="external">Link!</a>
      <a href="#" rel="colleague external">Link!</a>
      <a href="#" rel="friend">Link!</a>
      <a href="#" rel="friend">Link!</a>
      <a href="#" rel="external">Link!</a>
      <a href="#" rel="spouse">Link!</a>
      <a href="#" rel="external spouse">Link!</a>
      <a href="#" rel="me">Link!</a>
    html_lines: "1,2,5,7"

  - type: code
    numbered: 10
    html: |
      <a href="https://wikipedia.org/wiki/a">Link!</a>
      <a href="https://wikipedia.org/wiki/b">Link!</a>
      <a href="https://google.com">Link!</a>
      <a href="https://wikipedia.org/wiki/c">Link!</a>
      <a href="https://github.com">Link!</a>
      <a href="https://wikipedia.org/wiki/d">Link!</a>
      <a href="https://starwars.com">Link!</a>
      <a href="https://wikipedia.org/wiki/e">Link!</a>
    html_lines: "1,2,4,6,8"

---
