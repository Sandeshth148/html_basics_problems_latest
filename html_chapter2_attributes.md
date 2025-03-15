# 📌 HTML Attributes - Detailed Guide

HTML attributes provide **additional information** about an element. They are always included **inside the opening tag** and follow the format:

```html
<tagname attribute="value">Content</tagname>
```

---

## 🔹 1. Global Attributes

These attributes can be used on **any HTML element**.

### ✅ `id`

- Specifies a **unique identifier** for an element.

```html
<p id="intro">This is an introduction.</p>
```

### ✅ `class`

- Defines **one or more CSS classes** for styling.

```html
<p class="highlight">Styled text</p>
```

### ✅ `style`

- Allows **inline CSS styling**.

```html
<p style="color: blue; font-size: 20px;">Blue text</p>
```

### ✅ `title`

- Provides **tooltip text** when hovered over.

```html
<p title="This is a tooltip">Hover over me</p>
```

### ✅ `data-*`

- Stores **custom data** inside elements.

```html
<button data-user="admin">Click me</button>
```

---

## 🔹 2. Commonly Used Attributes

### ✅ `href` (For `<a>` Links)

- Defines the **URL** a link points to.

```html
<a href="https://example.com">Visit Example</a>
```

### ✅ `src` (For Images, Scripts, and Videos)

- Specifies the **source URL** of media files.

```html
<img src="image.jpg" alt="Sample Image" />
```

### ✅ `alt` (For Images)

- Provides **alternative text** if the image fails to load.

```html
<img src="broken.jpg" alt="Image not found" />
```

### ✅ `target` (For Links)

- Controls **where the link opens**.

```html
<a href="https://example.com" target="_blank">Open in new tab</a>
```

| Value     | Behavior                      |
| --------- | ----------------------------- |
| `_self`   | Default (same tab)            |
| `_blank`  | Opens in a **new tab**        |
| `_parent` | Opens in the **parent frame** |
| `_top`    | Opens in the **full window**  |

---

## 🔹 3. Form Attributes

### ✅ `placeholder`

- Shows a **hint inside input fields**.

```html
<input type="text" placeholder="Enter your name" />
```

### ✅ `required`

- Makes a field **mandatory**.

```html
<input type="email" required />
```

### ✅ `disabled`

- Disables user input.

```html
<input type="text" disabled />
```

### ✅ `readonly`

- Prevents user edits but **allows selection**.

```html
<input type="text" value="Read-only text" readonly />
```

### ✅ `maxlength`

- Sets the **maximum number of characters** allowed.

```html
<input type="text" maxlength="10" />
```

---

## 🔹 4. Table Attributes

### ✅ `colspan`

- Makes a cell **span multiple columns**.

```html
<td colspan="2">Merged columns</td>
```

### ✅ `rowspan`

- Makes a cell **span multiple rows**.

```html
<td rowspan="3">Merged rows</td>
```

---

## 🔹 5. Media Attributes

### ✅ `autoplay`

- Starts playback **automatically** (for videos/audio).

```html
<video src="video.mp4" autoplay></video>
```

### ✅ `controls`

- Adds **play, pause, volume** controls.

```html
<audio src="audio.mp3" controls></audio>
```

### ✅ `loop`

- Repeats media **indefinitely**.

```html
<video src="clip.mp4" loop></video>
```

### ✅ `muted`

- Starts media with **sound off**.

```html
<video src="silent.mp4" muted></video>
```

---

## 🔹 6. Accessibility Attributes

### ✅ `aria-label`

- Provides **an accessible label** for screen readers.

```html
<button aria-label="Close">X</button>
```

### ✅ `tabindex`

- Controls **keyboard navigation order**.

```html
<input type="text" tabindex="1" />
```

### ✅ `role`

- Defines the **purpose of an element** for assistive technologies.

```html
<div role="alert">Error message</div>
```

---

## 📌 Summary

| Attribute     | Purpose                               |
| ------------- | ------------------------------------- |
| `id`          | Unique identifier                     |
| `class`       | Apply CSS styles                      |
| `style`       | Inline CSS                            |
| `title`       | Tooltip on hover                      |
| `href`        | Link destination                      |
| `src`         | Media source URL                      |
| `alt`         | Alternative text for images           |
| `target`      | Open links in new tab or same tab     |
| `placeholder` | Input field hint text                 |
| `required`    | Makes a field mandatory               |
| `disabled`    | Disables an input field               |
| `readonly`    | Prevents editing but allows selection |
| `colspan`     | Merges table columns                  |
| `rowspan`     | Merges table rows                     |
| `autoplay`    | Starts media automatically            |
| `controls`    | Adds media controls                   |
| `loop`        | Repeats media                         |
| `muted`       | Starts muted media                    |
| `aria-label`  | Improves accessibility                |
| `tabindex`    | Keyboard navigation order             |
| `role`        | Defines an element's purpose          |

---

## 🛠 More Resources

- [MDN Web Docs - HTML Attributes](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes)

---

📖 **This Markdown file provides a structured and detailed reference for HTML attributes.** 🚀
