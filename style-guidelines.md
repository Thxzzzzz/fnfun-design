# Style Guidelines

> Visual style rules for the WeighBetter app: use them to judge whether a design is heading in the right direction, and as a checklist during review.
>
> The rules can only filter out designs that go the wrong way; they don't guarantee that what's left looks good. Whether a design holds up still has to be judged on the canvas.

## 1. Principles

**It should feel like an object on a desk, something you can read clearly and almost touch, not a glowing screen.**

- **Solid**: opaque content with clear edges. Depth comes mainly from strokes, color blocks and solid shadows. Transparency and blur aren't off-limits, but they stay restrained and in harmony with the whole; the design must never depend on them.
- **Warm**: light, warm backgrounds. There is a single accent color, used only for status and actions.
- **Grounded**: graphics borrow how an everyday object is read, or carry visible traces of being made by hand. Playfulness comes from "made by a person", not "lit up by a machine".
- **Baseline**: weight and body fat are readable at a glance. Decoration never competes with the numbers.

## 2. Rules by dimension

### 2.1 Surfaces and depth

- **Do**: use opaque surfaces for content (cards, the main graphic, lists), with clear edges between them: a stroke, a color difference, or a solid shadow with a consistent direction. Shadows can be hard offsets with no blur, or soft shadows that imitate a physical part raised or pressed in. Either way the light source stays consistent, and the shadow reads as "this piece sticks out" or "this piece is pressed down".
- **Allowed, with restraint**: glass, translucency and background blur on a few elements that float above the content, such as a Liquid Glass tab bar and top buttons following iOS 26 conventions. Restraint means using it sparingly and only on that floating layer. Harmony means its corners, strokes and shadows speak the same language as everything else, text stays clear when content shows through, and a theme without glass loses nothing when it's removed.
- **Don't**: let glass and light play the lead: content cards or the main graphic made of glass, large translucent layers, diffuse light blobs, outer glow, neon strokes.
- **Test**: set every opacity to 100% and remove all blur and glow. Is the design's character still there? If it is, and the glass only makes the floating layer feel lighter, that's restraint. If not, it relies on glass and light, and it's off-direction.

### 2.2 Color

- **Do**: default to light, warm backgrounds (paper, cream, warm gray, light aluminum). There is a single accent color; it covers a small area and appears only on status, anomalies and tappable actions. Warm accents (orange, yellow) are the most common. A cool primary color also works as long as it harmonizes with the whole, such as Spectrum 2's blue, with orange stepping back to status.
- **Allowed**: the colors an object metaphor naturally has. Paint the object in the colors it really comes in, even if they are more saturated than the theme or there are several of them. Playful directions may use saturated flat color blocks, as long as the background stays light and text contrast stays sufficient.
- **Don't**: cold, serious combinations such as cool gray, desaturated palettes, or black-white-red. Dark backgrounds with neon, fluorescent or acid colors.
- **Dark is not the default**: if a design must be dark, its character has to come from the graphic structure itself (a dot matrix, for example), never from glow.

### 2.3 Type and numbers

- **Do**: sans-serif by default. Key numbers are either heavy enough or large enough; thin weights are only acceptable at very large sizes.
- **Minimum sizes**: on the home screen, weight at 56–64pt and body fat at no less than 30pt. Body text 15–17pt, captions no smaller than 12pt. Buttons and tap targets no smaller than 44pt.
- **Don't**: typography where thin serifs play the lead, the "premium" look of magazines, luxury brands and apothecary labels.
- **Exception**: a serif can appear as one material among others, such as in a collage, but never as the face for body text or key numbers.
- **No extremes with numbers**: don't hide the numbers behind graphics, and don't let a single number fill half the screen. Metrics other than weight and body fat show a graphic first and a value second, so secondary numbers never flood the screen.

### 2.4 Graphic language: one object tells one thing (the main route)

- **Do**: carry data on the structure of an everyday object: a scale with ticks, a needle, a liquid level, a grid, a page, a key, a label, a stamp. Map weight, trend and goal onto the way that object is naturally read. Length is read off ticks, accumulation off cells and stamps, dates off a calendar, highs and lows off a liquid level.
- **Priority**: object metaphors > abstract metaphors with a sense of space (a horizon or a sea level, things that speak through position) > generic charts (rings, color bands, line charts in cards). Generic charts may appear, but only in a supporting role.
- **Draw objects in their own materials and colors**: don't fade an object to the theme's single color or warm gray just to make it fit a theme. When borrowing from a theme, borrow its structure and layout (for example, "a huge number + one trend line"), not its palette painted over the object.
- **Choosing an object**:
  1. Ordinary people recognize it and can read it without being taught.
  2. The way it is naturally read matches the quantity it represents, rather than being forced onto it.
  3. One screen has exactly one main graphic; everything else serves it. No side-by-side charts.
  4. The key number has a clear place inside the metaphor and isn't swallowed by it.

### 2.5 Playfulness and the hand-made

- **Do**: playfulness is welcome when it comes from craft and physical things: bold strokes, flat fills, hand-drawn lines, pixel or dot-matrix units, cut-paper collage, stickers, stamps.
- **Don't**: playfulness that comes from tech aesthetics or era filters: chrome, holographic effects, cyberpunk, glitch, acid graphics, Y2K.
- **Test**: could this effect be made with a pen, paper, scissors, a stamp or a plastic part, or only by a glowing screen? The first is fine; the second is not.

### 2.6 Texture

- **Do**: crisp and clean. Flat fills, or the feel of hard materials such as paper, plastic and aluminum.
- **Don't**: soft, puffy clay looks. Grain or noise covering whole surfaces.
- **Where the line is**: shadows on raised parts have clear edges and firm forms. Once the edges go fuzzy and the form looks like squeezed soft rubber, it has gone too far.

### 2.7 Borrowing an established design system

- **Allowed**: adopt the structure of a mature design system outright: white cards, one primary color, a clear hierarchy, controls at standard sizes.
- **Don't**: let it look too much like a system skin. If it's instantly recognizable as a phone maker's OS, an enterprise back office, or a particular company's product page, the product's own personality has been swallowed.
- **Test**: cover the logo and show it to someone. Would they say "that's the settings screen of such-and-such system"? If so, it has gone too far.

### 2.8 Whitespace and density

- **Allowed**: very quiet layouts with almost no frames, and a sentence in place of a numeric comparison.
- **Condition**: quiet doesn't mean hiding information. Key numbers still meet §2.3 and stay readable at a glance.

## 3. Review checklist

Go through these one by one when reviewing a new design:

1. With transparency, blur and glow removed, is the design's character still there? Is any glass limited to a few floating elements and in harmony with the rest? (§2.1)
2. Is the background light and warm? Is there a single accent, used only for status and actions? (§2.2)
3. Are key numbers sans-serif, heavy or large enough, and above the minimum sizes? Neither hidden nor filling half the screen? (§2.3)
4. Does the screen have one object or spatial metaphor as its only main graphic? Does the way it's read match the data? (§2.4)
5. Does the object keep its own colors and materials? (§2.4)
6. Does the playfulness come from craft rather than glow and filters? (§2.5)
7. Is the texture crisp, neither soft nor grainy? (§2.6)
8. With the logo covered, does it look like an existing system's skin? (§2.7)
