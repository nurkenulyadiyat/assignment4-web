# Assignment 4 — Forms and Validation

**Student:** Adiyat Nurkenuly  
**Group:** SE-2527

A simple website made with **HTML, a small CSS file, and Bootstrap 5.3.6**. No JavaScript.

## Tasks

- `task0.html`: Contact form with Name, Email, Message, labels and Submit.
- `task1.html`: HTML5 validation with `required`, `type="email"`, `minlength`, `maxlength`.
- `task2.html`: Bootstrap form styling, responsive grid, placeholders and helper text.
- `task3.html`: Bootstrap `is-valid`/`is-invalid` examples and live CSS-only feedback using `was-validated`.
- `task4.html`: Registration form with names, email, password fields, gender, hobbies, country, Submit and Reset, plus validation feedback.

`index.html` is the homepage. The navbar links to all tasks.

## Run locally

1. Open this folder in VS Code.
2. Open `index.html` using Live Server (or double-click it).
3. Use the navbar to open Task 0–4 and test the forms.

Bootstrap CSS is saved locally in `css/bootstrap.min.css`, so the design works without internet. `css/styles.css` contains only a few custom rules.

## What validation does

- HTML5 automatically blocks empty `required` fields, invalid emails, and too-short values.
- Task 3 uses static Bootstrap `is-valid`/`is-invalid` examples and a `was-validated` form. The field colors and feedback update using CSS selectors, **without JavaScript**.
- Task 4 requires first name, last name, email, both passwords (at least 8 characters), a gender option and a country. Hobbies are optional.
- HTML alone **cannot check whether the two passwords match**. The assignment requires the fields and HTML5 validation, but does not explicitly require a password match check.
- Buttons open `success.html` after built-in validation. This is **only a demonstration**: the form is not connected to a backend and does not save data. Personal input fields have no `name` attributes so their values are not added to the GET URL. (The radio group uses `name="gender"` so only one radio can be selected.)
