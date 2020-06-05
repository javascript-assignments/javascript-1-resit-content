# JavaScript 1 Course Assignment

Choosing appropriate variable and function names will form part of your assessment, as will proper and consistent formatting of your code.

---

## Instructions

---

The HTML and CSS needed for the level 1 requirements is provided in the [repo](https://github.com/javascript-assignments/javascript-1-resit). Download or clone this repo and add your code to it.

Add your JavaScript code to the `.js` files provided.

## Level 1

### `index.html`

This API URL returns a random joke every time you call it:

`https://official-joke-api.appspot.com/random_joke`

Make a call to this URL and display the `setup` and `punchline` properties.

Replace the content of the `h2` tag with the `type` property from the API result together with the string "Joke". If the `type` is "General" the `h2` should display `General Joke`.

If there is an error the `h2` should display an error message. You can hardcode this message.

Example HTML from the repo:

```html
<h2>Random Joke</h2>

<div class="joke setup"></div>
<div class="joke punchline"></div>
```

Change the `title` metatag value on the page to be the value of the `setup` property.

---

### `jokes.html`

This API URL returns 10 jokes every time you call it:

`https://official-joke-api.appspot.com/random_ten`

Make a call to the URL, loop through the results and display the `type`, `setup` and `punchline` properties for only 5 of the results. Don't display all 10.

Example HTML from the repo you can create for each joke:

```html
<div class="col-sm-6 col-md-4 col-lg-3">
    <div class="card">
        <div class="joke-detail">
            <h4 class="type">Type</h4>
            <div class="setup">Setup</div>
            <div class="punchline">Punchline</div>
        </div>
    </div>
</div>
```

Change the `title` metatag value on the page to be the value of the `setup` property from the 3rd result.

Catch any errors and display a message in the `h1` element on the page if an error occurs.

---

### `about.html`

Write code to reverse the order of the paragraphs on this page.

---

### `dynamic.html`

There is a number input in the example HTML.

Write an event listener that creates a `<div>` for the number value in the input when the value changes. For example, if the value is 4 create HTML like this:

```html
<div>Number 1</div>
<div>Number 2</div>
<div>Number 3</div>
<div>Number 4</div>
```

Write an event listener for the reset button to remove the `<div>` elements created.

---

### `contact.html`

There is a single text input on this page called `firstName`.

Add appropriate inputs for the following:

-   lastName
-   email
-   subject
-   message

When the form on this page is submitted, write code to validate the inputs with the following rules:

-   `firstName` - required
-   `lastName` - must have a value with a minimum length of 3
-   `email` - must have a value and be formatted like an email address
-   `subject` - must have a value with a minimum length of 7
-   `message` - must have a value with a minimum length of 15

If any of the inputs fail validation display the relevant error message.

---

## Rules

-   Copying and sharing of any code will result in your resit being given a mark of zero.
-   You may only use plain JavaScript for this assignment, no libraries or frameworks. You will be given a mark of zero if you use a library or framework for your JavaScript code.

## Submission

-   Create a repository in your GitHub account called `your-name-js1-resit`, e.g. `mary-smith-js1-resit`, and **make sure it's public**
-   If you downloaded the repository you can simply commit and push your code to your repository
-   If you cloned the repository you can change the origin url so that pushes will be sent to your repo:

```js
git remote set-url origin NEW_URL
```

where `NEW_URL` is your repo's URL.

-   Submit the repo link
