## 🖍️ CSS Types Overview

### 1. Inline CSS

**Where:**  
In your `index.html` file, you used inline CSS on the `<body>` tag.

**How:**  
The `style` attribute is added directly to the HTML element. This applies the background color only to this specific `<body>` element. Inline CSS is useful for quick, one-off styles that don’t need to be reused.

---

### 2. Internal CSS

**Where:**  
In your `index.html` file, inside the `<head>` section, you have a `<style>` block.

**How:**  
Internal CSS is written inside a `<style>` tag in the HTML `<head>`. It applies styles to the whole document and is useful for page-specific styles that don’t need to be shared across multiple pages.

---

### 3. External CSS

**Where:**  
In your `index.html` file, you link to an external CSS file in the `<head>`:

```html
<link rel="stylesheet" href="style.css">
