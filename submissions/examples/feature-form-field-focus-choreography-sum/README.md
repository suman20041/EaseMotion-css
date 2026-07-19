# Form Field Focus Choreography

## 1. What does this do?

A frontend-only form demo that choreographs floating labels, helper text slide-in, error shake, and a success check draw into one cohesive focus/validation motion pattern.

## 2. How is it used?

Open `demo.html` in a browser. Focus a field to float its label and slide in helper text. Submit empty fields to trigger shake errors, or fill valid values and submit to watch the success check draw.

```html
<div class="field is-focused">
  <div class="field-shell">
    <input id="email" type="email" placeholder=" " />
    <label for="email">Email address</label>
  </div>
  <p class="helper">We’ll only use this for demo feedback.</p>
</div>
```

## 3. Why is it useful?

Form polish usually becomes disconnected micro-snippets. This demo shows beginners one readable motion system for focus → help → error → success, matching EaseMotion’s philosophy of expressive, human-readable interaction patterns.

## Issue

Resolves #51867
