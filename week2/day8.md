# 📅 Day 8 – June 25, 2025

## ✅ Topics Learned

### 🔹 1. CSS Specificity

- **Specificity** determines which CSS rule is applied when multiple rules target the same element.
- Order of specificity (from lowest to highest):
  1. Element selector (`div`, `p`)
  2. Class selector (`.class`)
  3. ID selector (`#id`)
  4. Inline styles (`style=""`)
- If two selectors have the same specificity, the **last defined rule** wins (CSS is read top to bottom).

```css
/* Example: ID will override class */
#heading {
  color: red;
}
.heading {
  color: blue;
}
```
🔹 2. CSS Box Model
- Content: The actual text or image
- Padding: Space around the content (inside the border)
- Border: Edge of the box
- Margin: Space between boxes (external spacing)

🔹 3. Units in CSS
-📏 Absolute Units:px – 
     - pixels (fixed size)
     - cm, mm, in, pt – used mostly for print
- 🔁 Relative Units:
    - % – relative to parent element
    - em – relative to the font-size of the element
    - rem – relative to the root (html) font-size
    - vw, vh – relative to the viewport's width/height

🛠️ Work Done
- Practiced overriding CSS rules using different selectors
- Visualized and experimented with box model using borders and padding
- Applied different units (px, %, em, rem) to layout elements

  ## create travelagent website
  https://travelagentwebsite.netlify.app/








