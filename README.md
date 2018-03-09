# testSoftindex
React/Redux table component with add-item form and filters.

## Stack:

-html
-css (PostCSS)
-js (React/Redux/Babel)
-module bundler (Webpack)

## Task:

Implement a single-page client application, consisting of 2 parts: the table and the form of adding records to the table.

The form has the following fields:

    First Name (string)

    Last Name (string)

    Phone (string)

    Gender (boolean)

    Age (number)

Each field must have a validation rule. An invalid field must be visually highlighted. The form adds an entry only if there are no errors. The form and the table are on the same screen, so when you send the form data, the data in the table is updated automatically, and the form fields are cleared.

The table should provide for sorting by each of the fields and deleting records.

The records in the table must be saved on the client and loaded after the page is reloaded.
