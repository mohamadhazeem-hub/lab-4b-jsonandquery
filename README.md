# BIC21203 Web Development
## Lab 4b: Client-Side Scripting (JSON and jQuery)

### Student Information

- **Name:** Mohamad Hazeem Bin Mohd Zahri
- **Student ID:** AI250064
- **Course:** BIC21203 Web Development
- **Lab:** Lab 4b — JSON and jQuery

---

## Introduction

This lab focuses on using JSON, JavaScript, and jQuery to develop interactive web pages. It consists of three questions involving JSON data creation, retrieving and displaying JSON data, and manipulating HTML elements using jQuery.

## Question 1 — Create and Structure JSON Data

### Description

In Question 1, a JSON file named `books.json` is created to store information about two books. Each book contains a title, author, publication year, and genres.

### Files

- `books.json`

### How to Run

1. Open `books.json` in Visual Studio Code.
2. Check that the file contains the two book objects.
3. Save the file.
4. Open the file to verify its JSON structure.


## Question 2 — Retrieve and Display JSON Data

### Description

In Question 2, JavaScript's `fetch()` API is used to retrieve data from `books.json`. The webpage displays the title of the first book, the author of the second book, and the genres of both books.

### Files

- `books.html`
- `books.json`

### How to Run

1. Open the project folder in Visual Studio Code.
2. Ensure that `books.html` and `books.json` are in the same folder.
3. Install the Live Server extension if it is not already installed.
4. Right-click `books.html`.
5. Select **Open with Live Server**.
6. Check that the required book information appears on the webpage.

**Note:** A local development server is required to run the `fetch()` request successfully.

### Expected Output

- First book title: The Great Gatsby
- Second book author: Harper Lee
- The Great Gatsby — Fiction, Classics
- To Kill a Mockingbird — Fiction, Coming-of-Age

### Screenshot
<img width="1051" height="717" alt="image" src="https://github.com/user-attachments/assets/6e430891-9129-4252-9818-e648e8c1807a" />


## Question 3 — Compare Native JavaScript and jQuery

### Description

In Question 3, jQuery is used to manipulate HTML elements and handle button click events.

The program performs three operations:

1. Changes the text of `myElement` to "Modified Text".
2. Adds the `myStyle` CSS class to `myDIV`.
3. Displays an alert message when the button is clicked.

### Files

- `jquery-dom.html`

### How to Run

1. Open the project folder in Visual Studio Code.
2. Open `jquery-dom.html`.
3. Right-click the file and select **Open with Live Server**.
4. Verify that the text changes to "Modified Text".
5. Check that the `myDIV` element has a coral background and padding.
6. Click the **Click me** button.
7. Verify that the alert message "Button clicked!" appears.

**Note:** An internet connection is required to load jQuery from the CDN.

### Screenshot
<img width="1072" height="542" alt="image" src="https://github.com/user-attachments/assets/6bbf62c4-78b0-41ac-84bc-2b94d3231195" />


## 5. Conclusion

This lab demonstrates how JSON stores structured data, how JavaScript retrieves and displays JSON data using `fetch()`, and how jQuery simplifies DOM manipulation and event handling.

The three questions provide practical experience in developing web pages using JSON, JavaScript, and jQuery.
