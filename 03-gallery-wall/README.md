# 03 — Gallery Wall 🖼️

**Your job: write the CSS. The HTML is done.**

You're curating a small gallery. Open `goal.png` to see the target:

1. A **hero painting** hanging dead center on a tall wall — centered horizontally *and* vertically.
2. A **row of three smaller frames** beneath it, evenly spaced.

Open `index.html` with Live Server, then open `style.css` and work through TODO 1 → TODO 8. Refresh after each and compare with the goal.

The hero-centering is the famous **"center a div"** — the single most-googled layout problem in web history. Tonight you join the club, and after this you'll know it forever: a flex container, `min-height: 100vh`, `justify-content: center`, `align-items: center`.

For the lower shelf, try `justify-content: space-between` first, then try giving each `.frame` a `flex: 1` instead — notice how one spaces them out and the other stretches them to fill.

**Concepts:** centering with `justify-content` + `align-items`, `min-height: 100vh`, `gap`, `flex: 1`, `max-width: 100%` on images.
