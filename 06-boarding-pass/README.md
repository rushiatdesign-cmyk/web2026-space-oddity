# 06 — Boarding Pass 🎫 (homework)

**Your job: build the whole thing — HTML and CSS — from a picture.**

This is the boss level. No starter markup, no TODOs. Just `goal.png`.

**Step 1 — box it in pen.** Print or open `goal.png` and draw the boxes, exactly like the Day 3 warm-up. You'll find:

- a **header row**: airline name on the left, a logo on the right (a flex row with `justify-content: space-between`)
- a **middle row**: three info columns — passenger, gate, seat (a flex row; each column a small stack of a label above a value)
- a **footer strip**: a barcode-ish band along the bottom

**Step 2 — build the rooms.** Write the HTML: the boxes you drew become `<div>`s (with a semantic `<header>`/`<footer>` where it fits).

**Step 3 — flex them.** The key move is nesting: a *row that contains columns* is a flex container whose children are themselves `flex-direction: column` containers. Get that and the whole thing falls into place.

Match the **vibe, not the pixels.** Your airline, your destination, your name on the ticket. This is the shape of every card, header, and profile block you'll ever build — worth owning.

**Concepts:** everything from 01–05, composed. Nested flex containers, `space-between`, `flex: 1`, `flex-direction: column` inside a row.
