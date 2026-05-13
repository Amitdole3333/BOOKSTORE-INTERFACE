# Bookstore Interface

A simple static bookstore showcase built with HTML, CSS, and Bootstrap. The project displays a home page with featured books and individual detail pages for each book.

## Features

- Responsive book showcase layout
- Book cover images with separate detail pages
- Bootstrap 5 styling through CDN links
- Simple navigation back to the home page
- Book metadata sections such as genre and description

## Project Structure

```text
public/
  index.html
  book1.html
  book2.html
  book3.html
  images/
    Atomic -habits-2.png
    Deep-Work book.jpg
    Rich dad poor dad.jpg
```

## Getting Started

No installation is required because this is a static HTML project.

1. Open the project folder.
2. Open `public/index.html` in a web browser.
3. Click a book to view its detail page.

## Pages

- `index.html` - Main bookstore showcase page
- `book1.html` - Atomic Habits detail page
- `book2.html` - Rich Dad Poor Dad detail page
- `book3.html` - Deep Work detail page

## Dependencies

The pages use Bootstrap 5.3.3 from the jsDelivr CDN, so an internet connection is needed for Bootstrap styles and scripts to load.

## Notes

- Keep book images inside `public/images/`.
- Use relative paths when linking pages or image files.
- Since there is no backend, all content is edited directly in the HTML files.
