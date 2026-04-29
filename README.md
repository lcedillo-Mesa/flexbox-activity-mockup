# CSS Flexbox — Part 2: Style the Mock-Up
### Guided Version

You have already discovered what flexbox does by uncommenting the CSS.

Now it is your turn to **write it yourself.**

You have been given:
- The same `index.html` file from Part 1 — do not change it
- A new `style.css` with some properties **missing**
- A mock-up showing what your page should look like when you are done

> **Your goal:** Fill in the missing CSS values so your page matches the mock-up.

---

## Before You Start

Open these three things side by side:

1. `style.css` in Codespaces
2. The live preview (right-click `index.html` → Open with Live Server)
3. The mock-up reference sheet

---

## Word Bank

You will use these values to fill in the blanks. Each one is used **once**.

```
flex        flex-start        row        flex-end
```

You can also look at your **cheat sheet** if you need help.

---

## Step 1 — Open your style.css

Find the `.navbar` section. It looks like this:

```css
.navbar {
  background-color: #1a3a4a;
  display: flex;
  flex-direction: column;
  align-items: /* BLANK 1 */;
  gap: 4px;
  padding: 20px 24px;
}
```

---

## Blank 1 — `.header` → `align-items`

**Look at the mock-up.**

The heading and tagline are on the **LEFT side** of the header.

**Ask yourself:** Which word from the word bank means "start" or "left"?

> **Hint:** The value starts with the word **flex**.

Fill in Blank 1: `align-items: ______________ ;`

**Save with Ctrl + S. Check your preview.**

✅ Does the header text sit on the left? If yes, move to Step 2.

---

## Step 2 — Find the `.nav` section

It looks like this:

```css
.nav {
  background-color: #0F6E56;
  display: flex;
  flex-direction: /* BLANK 2 */;
  justify-content: /* BLANK 3 */;
  gap: 20px;
  padding: 10px 24px;
}
```

---

## Blank 2 — `.nav` → `flex-direction`

**Look at the mock-up.**

The nav links are sitting **side by side** in a line going left to right.

**Ask yourself:** Which value makes items go left to right — row or column?

> **Hint:** Think about rows in a table — they go across, not up and down.

Fill in Blank 2: `flex-direction: ______________ ;`

**Save with Ctrl + S. Check your preview.**

✅ Are the links sitting side by side? If yes, move to Blank 3.

---

## Blank 3 — `.nav` → `justify-content`

**Look at the mock-up.**

The links start from the **left edge** of the nav bar.

**Ask yourself:** Which value puts things at the beginning — flex-start or flex-end?

> **Hint:** Start = beginning = left side.

Fill in Blank 3: `justify-content: ______________ ;`

**Save with Ctrl + S. Check your preview.**

✅ Do the links start from the left? If yes, move to Step 3.

---

## Step 3 — Find the `.main` section

It looks like this:

```css
.main {
  background-color: #F1EFE8;
  display: /* BLANK 4 */;
  flex: 1;
  gap: 16px;
  padding: 20px;
}
```

---

## Blank 4 — `.main` → `display`

**Look at the mock-up.**

The two sections are sitting **next to each other**.

**Ask yourself:** What is the one property that turns flexbox on?

> **Hint:** You have typed this many times today. It is two words joined by a colon.

Fill in Blank 4: `display: ______________ ;`

**Save with Ctrl + S. Check your preview.**

✅ Are the two sections side by side? If yes, move to Step 4.

---

## Step 4 — Find the `.footer` section

It looks like this:

```css
.footer {
  background-color: #1a3a4a;
  display: flex;
  justify-content: /* BLANK 5 */;
  align-items: center;
  padding: 12px 24px;
}
```

---

## Blank 5 — `.footer` → `justify-content`

**Look at the mock-up.**

The footer text is on the **right side**.

**Ask yourself:** Which value pushes things to the end — flex-start or flex-end?

> **Hint:** End = finish = right side.

Fill in Blank 5: `justify-content: ______________ ;`

**Save with Ctrl + S. Check your preview.**

✅ Is the footer text on the right? 

---

## Check Your Work

Go through this list one by one:

- [ ] Header background is dark teal `#1a3a4a`
- [ ] Header text is on the **left**
- [ ] Nav background is green `#0F6E56`
- [ ] Nav links start from the **left**
- [ ] Main background is warm off-white `#F1EFE8`
- [ ] Two sections sit **side by side**
- [ ] Footer text is on the **right**

If something does not look right, go back to that blank and check your word bank again.

---

## Stuck?

**Step 1:** Look at your word bank at the top of this sheet.

**Step 2:** Look at your cheat sheet — find the property name and read the values next to it.

**Step 3:** Ask your partner.

**Step 4:** Put your hand up.

---

## You Did It!

Great work. Show your teacher your preview before closing your laptop.
