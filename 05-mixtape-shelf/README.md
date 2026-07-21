# 05 — Mixtape Shelf 📼 (homework)

**Your job: write the HTML. The CSS is done — and you may not change it.**

This is the flip of everything so far. Usually you get HTML and style it. Real work is often the reverse: you inherit someone's CSS (or a design system's) and you have to produce markup that fits it.

Open `style.css` and **read it like a blueprint.** It's expecting:

- **two** containers with class `shelf`
- inside each shelf, **four** boxes with class `cassette`
- inside each cassette, a `label` (the album name) and a `year`

Write that structure in `index.html` (there's a marked spot). Put your own favourite albums on the shelves. When the HTML matches what the CSS expects, two rows of cassettes appear, standing on their shelves.

If nothing shows up, you've got a class-name typo or a missing wrapper — compare your HTML against the CSS comments line by line. That hunt *is* the exercise.

**Concepts:** the container/child mental model, reading CSS you didn't write, nesting `flex-direction: column` boxes inside a `flex-direction: row` parent.
