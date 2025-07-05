# pure-css.extensions

Extensions to the popular [pure.css](https://pure-css.github.io/) styles and components, including sidebars, drawers, cards and skeletons.

## Theming

The following global variables can be overridden:

```css
:root {
  /* Background colours */
  --bg-primary         /* Primary UI elements (e.g. buttons, headers) */
  --bg-secondary       /* Secondary UI elements (e.g. sidebar, footer) */
  --bg-danger          /* Background for error states */
  --bg-accent          /* Accent background (cards, highlights) */

  /* Text colours */
  --text-primary       /* Default text colour for main content */
  --text-secondary     /* Muted/secondary text */
  --text-success       /* Success state text (e.g. alerts, badges) */
  --text-warning       /* Warning text */
  --text-danger        /* Error text */

  /* Border colours */
  --border-primary     /* Default border colour */
  --border-secondary   /* Lighter border for subtle dividers */

  /* Highlight colours */
  --highlight-bg       /* Skeleton loaders or subtle highlights */
  --highlight-accent   /* Lighter highlight for shimmer effects */

  /* Spacing units */
  --spacing-1          /* Small spacing (e.g. between pills/buttons) */
  --spacing-2          /* Standard spacing for layout */
  --spacing-3          /* Large spacing (e.g. between sections) */

  /* Font sizes */
  --font-1             /* Small text (e.g. pills, meta) */
  --font-2             /* Normal body text */
  --font-3             /* Subheadings */
  --font-4             /* Headings or large labels */

  /* Border radius */
  --radius-1           /* Small rounding (e.g. buttons) */
  --radius-2           /* Medium rounding (e.g. cards) */
  --radius-3           /* Large rounding (e.g. badges, pills) */

  /* Layout */
  --sidebar-width      /* Fixed width for sidebar */
  --border-1           /* Standard border width */

  /* Font stack */
  --font-family        /* Global font family */
}
```
