# Personal Web Page Project

This is a responsive, accessible personal web page built with semantic HTML5 and custom CSS3. The page highlights my interests, personality, and creative flair through visual styling, interactive elements, and thoughtful layout.

## Features

### Semantic HTML5
- Proper use of `header`, `footer`, `section`, `nav`, and other semantic elements.
- Organized structure for accessibility and screen readers.

### Advanced CSS
- Custom properties (`--variables`) for theme control
- Responsive typography using `clamp()`
- Grid and Flexbox layouts for different content areas
- Media queries for mobile, tablet, and desktop breakpoints
- Light/Dark mode support via `[data-theme="dark"]`
- Smooth hover effects and transitions

###  Special Requirements Met

####  Custom List Markers
- Used `::marker` to style list items with emojis (💖 and ⭐)

####  Inline Text Styling
- Used `::before` and `::after` pseudo-elements for decorative inline text like `.fancy-text`

####  Styled Form
- A form with:
  - Fieldset + legend
  - At least three input types (e.g., `email`, `date`, `textarea`)
  - One HTML5-specific input (`date`, `email`, etc.)
  - Client-side validation with `required`, `pattern`, etc.
  - Matching theme styling

####  Styled Links
- At least three working links
- `:hover` styles apply whether visited or not
- `:visited` links have a unique style

####  No CSS Conflicts
- Carefully scoped styles with class selectors
- Variable-based theming ensures no clashing declarations



##  Getting Started

1. Clone or download this repo.
2. Open `index.html` in your browser.
3. Toggle between light/dark themes (if implemented).

##  Notes

- All links are placeholder or external.
- The form is non-functional (no backend).
- No email addresses are hardcoded (per project rules).
- Fully passes HTML + CSS validation as per W3C standards.