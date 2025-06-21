# Assignment-Day6

# CSS Box, Layout, and List Exercises

## Qs1. Create a Box using `<div>`

**Requirements:**
- Height: `150px`
- Width: `300px`
- Background color: `grey`
- Border: `5px`, `black`, `dotted`
- Margins:
  - Top: `20px`
  - Right: `1em`
  - Bottom: `40px`
  - Left: `2em`
- Padding: `1em` on all sides

---

## Qs2. Create 3 `<div>`s with the following properties

**Each Div Should Have:**
- Height & Width: `100px`
- Background color: `pink`
- Border: `2px` solid `black`
- Shape: Circle (Hint: use `border-radius: 50%`)
- Layout: All 3 divs should be on a **single line** (Hint: use `display: inline-block` or `flexbox`)

---

## Qs3. Create a List of Technologies

Technologies:
- HTML
- CSS
- JavaScript
- NodeJS
- ReactJS
- SQL
- MongoDB
- Java
- C++
- C
- Python

**Task:**
- Change the display of all list items to `inline` using CSS.

**Observation:**
- Did the bullet points disappear?  
  Try to find out why this happens when you use `display: inline`.

> 💡 **Hint:** Bullet points (default list markers) are part of the block-style layout. When you use `display: inline`, the list item behaves like inline text, which removes the marker. You can retain bullets using `list-style-position: inside;` or manage with custom styles.
