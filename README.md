# Bibliotheque — Library Management System

A comprehensive web-based library system built with HTML, CSS, and JavaScript. Features both a traditional borrow/return system and an extended books catalog with Somali literature.

## Overview

Bibliotheque is a single, unified application with two complementary interfaces:

1. **Library System** - Borrow and return books with activity logging
2. **Books Catalog** - Browse, search, filter, and reserve from an extended collection

## Features

### Library System Tab
- Browse books available for borrowing
- Borrow books with member tracking
- Return borrowed books with activity logging
- Real-time statistics (Available, Borrowed, Total)
- Search by title or author
- Filter by status (All, Available, Borrowed)
- Activity log with timestamps

### Books Catalog Tab
- Extended catalog of 20+ books including Somali literature
- Search by title, author, ISBN, or genre
- Sort by title, author, year, or rating
- Filter by genre (including Somali, Fiction, Sci-Fi, Non-Fiction, Classic, Technology, etc.)
- Detailed book information modal with descriptions
- Star ratings and availability status
- Reserve or join waitlists for books

## Files

| File | Description |
|------|-------------|
| `bibliotheque-merged.html` | Complete merged system (recommended) |
| `library-system.html` | Original borrow & return system |
| `bibliotheca.html` | Original books catalog |
| `README.md` | Documentation |

## How to Use

1. Download `bibliotheque-merged.html`
2. Open it in any modern web browser
3. Switch between tabs to access:
   - **Library System**: For borrowing and returning books
   - **Books Catalog**: For browsing the extended collection

No installation or server required — everything runs locally in your browser.

## Book Collections

### System Books (Borrow/Return)
Classic and academic titles available for borrowing including works by:
- Gabriel García Márquez
- Plato
- Marcus Aurelius
- Charles Darwin
- And more

### Catalog Books (Browse/Reserve)
20+ books across multiple genres:
- **Somali Literature** - Works by Hassan Sheikh Mumin, Farah Mohamed Ali Gaas, and others
- **Fiction** - Modern and classic novels
- **Non-Fiction** - Biographies, history, and personal development
- **Technology** - Programming and design books
- **Science & Philosophy** - Academic works

## Features

- **Dual Interface**: Two complementary systems in one application
- **Activity Tracking**: Log all borrow/return activities with timestamps
- **Member Management**: Track who borrowed what and when
- **Advanced Search**: Full-text search across titles, authors, and ISBNs
- **Filtering & Sorting**: Multiple ways to find and organize books
- **Responsive Design**: Works on desktop and mobile devices
- **No Backend Required**: Completely client-side, data persists during session

## Technical Details

- **HTML5** structure with semantic markup
- **CSS3** with custom properties and responsive grid layout
- **Vanilla JavaScript** (no dependencies)
- **Google Fonts**: Playfair Display (serif) + DM Mono (monospace)
- **Data persistence**: Session-based (localStorage ready for enhancement)

## Contributors

- [Sidiiq5](https://github.com/Sidiiq5) - Library System
- [bullhan66](https://github.com/bullhan66) - Books Catalog
- Merged & enhanced version

## Future Enhancements

- LocalStorage for persistent data across sessions
- Export activity logs to CSV
- User authentication system
- Database integration
- Advanced filtering by publication year or page count
- Book cover images
- User reviews and ratings

## License

Open source. Feel free to modify and distribute.
