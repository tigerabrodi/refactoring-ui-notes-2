# Starting from scratch

- Start with a feature, not a layout. Don't worry about navigation, logos or footers. Begin designing what will offer value to the user.
- Don't obsess over details.
- Start by designing in grayscale. It forces you to focus on structure, space and fonts.
- Don't design too much.
- Work in cycles.
- Choose a personality e.g. a banking system may have a personality of trust, security and professionalism.
- Fonts play a huge role in design. Choose wisely. Playful look, use rounded sans serif. For a professional look, use a serif font.
- When picking a color, think about the mood you want to convey and what looks good for you.
- Border radius makes it feel more playful and friendly.
- Limit your choices. It makes it easier to make decisions when designing. Colors, fonts, etc.
- You don't have to design the entire system upfront, but look for patterns and reuse them. Shadows, radius, opacity, colors, font sizes, etc.

# Hierarchy is everything

- When everything in an interface is competing for attention, it feels noisy and
  chaotic, like one big wall of content where it’s not clear what actually
  matters.
- Make an effort to highlight what matters and de-emphasize what doesn’t.
- Don't only use size to convey importance. Use font weights, colors, spacing, etc.
- Stay away from font weights under 400 for UI work — they can work for
  large headings but are too hard to read at smaller sizes.
- Size isn’t everything using a lighter weight to de-emphasize some text, use a lighter color or smaller font size instead.

---

- Don't use grey text on colored backgrounds. Instead use a color with the same hue and adjust saturation and brightness.
- Emphasize by de-emphasizing: Sometimes you run into the problem of trying to emphasize something that can't be any more emphasize. Then de-emphasize everything its sibling elements.
- Labels are a last resort: This isn't about forms. It's about attaching labels to information that's already clear without the label. You can also combine labels and values into a text to make it easier to read e.g. "12 left in stock" instead of "In Stock: 12".
- Sometimes you want to emphasize the labels, e.g. smartphones, depth, width etc.

---

- Don't let semantics dictate your design. h1 doesn't mean it should be big. Sometimes you can just hide it visually and still have it in the DOM because the content speaks for itself.

---

- Bold fonts are great for emphasis.
- Sometimes icons may feel like bold because of their color, a way to approach this is to lower the contrast of the icon.
- Sometimes weight e.g. increasing border width is better than darkening its color when feeling too light.

---

When designing actions:

- Primary actions should be obvious. Solid, high contrast background
  colors work great here.
- Secondary actions should be clear but not prominent. Outline styles or
  lower contrast background colors are great options.
- Tertiary actions should be discoverable but unobtrusive. Styling these
  actions like links is usually the best approach.

# Layout and spacing

- Start with too much white space. It's easier to tidy up later rather than starting with too little space.
- It's better to start by giving too much space to elements and then reduce it.
- Dense UIs have their place, but it's always good to start with more space. It's more obvious where to remove space than where to add it.
- Have a system in place for fonts and spacing. 16px is a good start. 4, 8, 12, 16, 24, 32, 48, 64, 96, 128 etc.

---

- You don't have to fill the whole screen. Keep it clean and simple.
- Start by designing for mobile. Then bring it over to desktop and adjust.
- Splitting a single column layout into two columns can make it look cleaner and more simple.
- Be pragmatic, sometimes filling up the screen is the best approach.

---

- If you've a sidebar, sometimes it's better to have a fixed with sidebar and let the main content adjust it's width as the screen shrinks. This applies to components too, don't just percentages to size something unless you actually want it to scale e.g. a profile picture on a card.
- Don't use grids.

---

- Not everything should be relative sized e.g. text and it's headline, using em unit for the headline. Don't be dogmatic about it and don't do this.
- As a general rule, elements that are large on large screens need to shrink
  faster than elements that are already fairly small
  This applies to buttons too, padding should shrink as the button shrinks.

---
