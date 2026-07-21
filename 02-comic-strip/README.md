# 02 — Comic Strip 💥

**Your job: fix the CSS. Don't touch the HTML.**

Four panels, one joke. The panels are in the *right* order in the HTML — but the CSS is using the `order` property to shuffle them, so the punchline lands first. There's also a wrapping bug that squishes the panels on a narrow window.

Open `index.html` with Live Server. In `style.css`:

- **Bug A:** make the panels wrap onto a new line instead of squishing (`flex-wrap`).
- **Bug B:** fix the `order` values so the strip reads 1 → 2 → 3 → 4. The tidiest correct answer is very tidy indeed — and you could also just *delete* the four `order` lines. Think about why that also works. (When no order is set, flex items follow their order in the HTML — which is already correct here.)

This is what `order` is really for: changing *visual* order without touching the underlying HTML — handy for responsive layouts where the source order should stay meaningful.

**Concepts:** `order`, `flex-wrap`, source order vs. visual order.
