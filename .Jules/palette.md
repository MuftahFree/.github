## 2024-05-16 - Decorative SVGs and Keyboard Navigation
**Learning:** Purely visual/decorative SVG elements can be announced as noise by screen readers if not properly hidden. Also, interactive elements like custom hover nodes and info blocks lack keyboard focus visibility unless explicitly handled.
**Action:** Always add `aria-hidden="true"` to decorative `<svg>`s and explicitly add `tabindex="0"` alongside `:focus-visible` CSS rules to custom interactive components to ensure keyboard accessibility matching mouse behavior.
