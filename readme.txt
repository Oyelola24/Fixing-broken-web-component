# 💳 Pricing Card Web Component

A reusable and lightweight custom HTML element for showcasing pricing plans. Built with vanilla JavaScript and Web Components — no frameworks or libraries required.

## ✨ Features

- ✅ Custom HTML element `<pricing-card>`
- ✅ Shadow DOM encapsulation (isolated styles)
- ✅ Simple setup — works in all modern browsers
- ✅ Accepts attributes for dynamic content:
  - `title`: Plan name
  - `price`: Plan pricing text
  - `features`: JSON array of feature items

## 🔧 Usage

1. Save the code in a file named `pricing-card.html`
2. Open it in any modern web browser

### 🔍 Example

```html
<pricing-card
  title="Basic Plan"
  price="$9.99 /month"
  features='["1 GB Storage", "Basic Support", "All Core Features"]'>
</pricing-card>
