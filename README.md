# JSON Content Formatting Guide

This repository uses a simple and consistent format for links inside JSON files.

## Link Formatting Rules

### 1. Hyperlinked Text

If you want a word or phrase to appear as a clickable link, use the following Markdown syntax:

```text
[yourword](https://yourlink.com)
```

**Example**

```json
{
  "description": "Learn more at [ImageKit](https://imagekit.io)"
}
```

---

### 2. Plain URLs

If you want to display a URL without custom link text, use the full URL directly.

**Example**

```json
{
  "website": "https://yourlink.com"
}
```

---

## Image Management

All images used by this project are hosted on **ImageKit**.

To replace or update an image:

1. Log in to your ImageKit account.
2. Upload the new image or replace the existing one.
3. Copy the generated ImageKit URL.
4. Update the corresponding URL in the JSON file.

Example:

```json
{
  "image": "https://ik.imagekit.io/your-account/example-image.png"
}
```

---

## Complete Example

```json
{
  "title": "Sample Project",
  "description": "Visit our [Documentation](https://docs.example.com) for detailed guides.",
  "website": "https://example.com",
  "support": "https://support.example.com",
  "image": "https://ik.imagekit.io/your-account/project-banner.png"
}
```

---

## Best Practices

* Use `[text](https://yourlink.com)` when you want descriptive clickable text.
* Use plain URLs (`https://yourlink.com`) when displaying a direct website or API endpoint.
* Always use secure `https://` URLs.
* Keep links descriptive and meaningful.
* Manage and update all project images through **ImageKit** to ensure URLs remain consistent.
