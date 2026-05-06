# sumitkh1008.github.io
# 🚀 Markdown Rendering Test Suite
## Testing Subheaders and Typography

This is a paragraph designed to test **bold text**, *italicized text*, and ~~strikethrough~~. You can even combine them to see if the renderer handles ***bold italics*** correctly.

> **Note:** This is a blockquote. It should be visually offset from the rest of the text, often with a vertical bar on the left side.

---

## 🛠 Features & Requirements

### Task List (Interactivity Test)
- [x] Support for GitHub Flavored Markdown (GFM)
- [x] Proper header scaling
- [ ] Working checkboxes
- [ ] Auto-linking URLs: https://www.google.com

### Nested Lists
1. First major point
    * Sub-point alpha
    * Sub-point beta
2. Second major point
    * Another sub-item

---

## 📊 Data & Organization

### Table Test
| Feature | Status | Priority | Notes |
| :--- | :---: | :---: | :--- |
| **Parsing** | ✅ | High | Must handle pipe symbols |
| **Theming** | 🎨 | Med | CSS injection test |
| **Speed** | ⚡ | Low | Large file handling |

### Code Blocks
Here is an example of syntax highlighting for Python:

```python
def greet_user(name):
    # This is a comment
    greeting = f"Hello, {name}!"
    return greeting

print(greet_user("Markdown Tester"))
