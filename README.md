# Lens & Light — Photography Blog
### CSS Flexbox Activity




You have been given an `index.html` and a `style.css` file. The HTML is complete — do not change it. Your job is to fill in the missing CSS values so your page matches the mock-up.

---

## Resources

- **Flexbox cheat sheet** — your printed reference sheet
- **CSS-Tricks flexbox guide** — https://css-tricks.com/snippets/css/a-guide-to-flexbox/
- **Mock-up** — the reference image showing what your finished page should look like

---

## Before You Start

Open these three things side by side in Codespaces:

1. `style.css` on the left
2. The live preview (right-click `index.html` → Open with Live Server)
3. The mock-up reference sheet

Look at the mock-up carefully before you write anything. Ask yourself:
- Where is the text in the header sitting?
- Which way are the nav links going?
- Are the sidebar and images side by side or stacked?
- Where is the footer content sitting?

---

## Your Task

Your `style.css` has two types of things to complete:

- **`???`** — a value is missing, replace it with the correct one
- **Missing properties** — some rules have no flex properties at all, you need to add them yourself

Save with **Ctrl + S** after every change and check your preview.

---

## Section by Section

Work through each section in order. Check the mock-up after each one before moving on.

---

### Header

**Goal:** Title and tagline stack top to bottom. Text sits on the **left** side.

Find `.header` in your CSS. Two values have `???` — replace them both.

- `flex-direction` controls whether items go left to right or top to bottom
- `justify-content` controls where items sit along that direction

✅ Check: Does the header text sit on the left side?

---

### Nav

**Goal:** Links sit **side by side** with space evenly distributed around each one.

Find `.nav` in your CSS. Two values have `???` — replace them both.

- One controls the direction items flow
- One controls the spacing between and around items

✅ Check: Are the links in a row with even spacing?

---

### Hero

**Goal:** Title and text sit **side by side**.

Find `.hero` in your CSS. One value has `???` — replace it.

✅ Check: Are the title and text next to each other?

---

### Main

**Goal:** Sidebar and images sit **side by side**.

Find `.main` in your CSS. This rule is missing **two properties entirely** — you need to add them yourself.

Think about:
1. What turns flexbox on?
2. What makes the children go left to right?

✅ Check: Is the sidebar sitting next to the images?

---

### Sidebar

**Goal:** Photo info stacks **top to bottom**.

Find `.sidebar` in your CSS. One value has `???` — replace it.

✅ Check: Is the camera info stacking vertically in the sidebar?

---

### Images

**Goal:** The two photos stack **on top of each other** and fill the available space equally.

Find `.images` in your CSS. One value has `???` — replace it.

Find `.photo` in your CSS. One value has `???` — replace it with the value that makes both photos share the space equally.

✅ Check: Are both photos stacked in a column and the same height?

---

### Footer

**Goal:** Footer content sits on the **left** side.

Find `.footer` in your CSS. One value has `???` — replace it.

✅ Check: Is the footer text on the left?

---

## Bonus — Responsive Font Sizes

All font sizes in the file currently use `px` which is a fixed unit. Update them to use `rem` instead so they respond to the user's browser settings.

A rough guide:

| px | rem |
|----|-----|
| 11px | 0.7rem |
| 12px | 0.75rem |
| 13px | 0.85rem |
| 14px | 0.9rem |
| 18px | 1.125rem |
| 22px | 1.375rem |

Refresh the page after each change to see the effect.

---

## Challenges

You have finished the main layout — good work. The challenges below ask you to add new sections to the page. For each one, the HTML is given to you. Add it to `index.html` in the place described, then complete the CSS in `style.css`.

---

### Challenge 1 — Gallery Section

Add a row of photo cards that wraps onto the next line when there is not enough space.

**Where to add the HTML:** Paste after the closing `</div>` of `.main` in `index.html`.

**What to do in the CSS:** Find `.gallery-grid` in `style.css` and fill in the four `???` values.

Properties you will need: `display` · `flex-wrap` · `gap` · `justify-content`

> **Hint:** Which value of `flex-wrap` lets items move to the next line?

✅ Check: Do the six cards sit in rows and wrap when the screen is narrow?

---

### Challenge 2 — About Me Section

Add a section with a profile image on the left and your bio text on the right.

**Where to add the HTML:** Paste after the `.gallery` div in `index.html`.

**What to do in the CSS:** Find `.about`, `.about-content`, and `.about-tags` in `style.css` and fill in the `???` values.

Think about:
- `.about` — should the image and text go side by side or stack?
- `.about-content` — should the name, bio, and tags stack or sit in a row?
- `.about-tags` — should the tags sit side by side?

✅ Check: Is the image on the left with your bio text next to it? Do the tags sit in a row?

---

### Challenge 3 — Your Own Section

Design and build a section from scratch. You decide everything — the content, the layout, and the class names.

**Ideas to try:**
- A contact row with a name and email address side by side
- A centred quote from a photographer you admire
- A stats row showing photos taken, locations visited, years shooting

**Steps:**
1. Decide what your section will contain
2. Add your HTML to `index.html` — create your own class names
3. Write the CSS rules at the bottom of `style.css`
4. Use at least **two flex properties**

---

## Check Your Whole Page

Before you finish, go through this list:

- [ ] Header text is on the left
- [ ] Nav links are side by side with even spacing
- [ ] Hero title and text are side by side
- [ ] Sidebar and images are side by side
- [ ] Sidebar info stacks top to bottom
- [ ] Two photos stack top to bottom and are the same height
- [ ] Footer content is on the left
- [ ] Font sizes use rem not px
- [ ] At least one challenge section is added and styled
