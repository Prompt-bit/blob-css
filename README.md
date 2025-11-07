# BlobCSS

BlobCSS is a lightweight CSS library that gives your website modern UI features: glass containers, blob buttons, floating text, reusable cards, animated blobs, modals, and utility classes. All features are ready to use — just include the library.

Include BlobCSS in your project by adding this to your HTML head:
```html
<link rel="stylesheet" href="https://prompt-bit.github.io/blob-css/blob-css.css">
```
Or in your CSS:
```css
@import url('https://prompt-bit.github.io/blob-css/blob-css.css');
```

Glass Container: Wrap your content in a div with class "glass-container". Combine with utilities like m-3, p-3, text-center for spacing and alignment.
```html
<div class="glass-container m-3 p-3 text-center">
  <h2>Panel Title</h2>
  <p>Content inside a glass container.</p>
</div>
```

Blob Button: Use a button or link with class "blob-btn". Optional: add "floaty-text" to make the text float.
```html
<button class="blob-btn">Click Me!</button>
<h2 class="floaty-text">Optional Floating Text</h2>
```

Floating Text: Make headings or text float smoothly.
```html
  <h2 class="floaty-text">Floating Heading</h2>
  <p class="floaty-text">This text floats too!</p>
```

Blob Card: Create a reusable card component with class "blob-card".
```html
<div class="blob-card m-3 p-3 text-center">
  <h3>Card Title</h3>
  <p>Card content goes here.</p>
  <button class="blob-btn">Learn More</button>
</div>
```

Animated Blob: Add a morphing animated blob.
```html
<div class="blob"></div>
```

Modal Popup: Use a div with class "blob-modal". Add/remove "active" class with JavaScript to open/close.
```html
<button class="blob-btn" onclick="document.querySelector('.blob-modal').classList.add('active')">Open Modal</button>
<div class="blob-modal">
  <h3>Modal Title</h3>
  <p>Modal content here.</p>
  <button class="blob-btn" onclick="document.querySelector('.blob-modal').classList.remove('active')">Close</button>
</div>
```

Utility Classes: Quick styling helpers include m-3 (margin), p-3 (padding), text-center, d-flex, flex-column, justify-center, align-center.

```html
<div class="d-flex flex-column justify-center align-center m-3 p-3">
  <h2 class="floaty-text">Hello BlobCSS</h2>
  <button class="blob-btn">Click Me</button>
</div>
```
