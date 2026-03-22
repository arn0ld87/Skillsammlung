# Typography Scale Template

Nutze diese Vorlage für konsistente Typografie in deinem Projekt.

## CSS-Variablen

```css
:root {
  /* Font Families */
  --font-display: 'Playfair Display', Georgia, serif;
  --font-body: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
  --font-mono: 'JetBrains Mono', 'Fira Code', monospace;

  /* Type Scale - Major Third (1.25) */
  --text-2xs: 0.625rem;    /* 10px */
  --text-xs: 0.75rem;      /* 12px */
  --text-sm: 0.875rem;     /* 14px */
  --text-base: 1rem;       /* 16px */
  --text-lg: 1.125rem;     /* 18px */
  --text-xl: 1.25rem;      /* 20px */
  --text-2xl: 1.5rem;      /* 24px */
  --text-3xl: 1.875rem;    /* 30px */
  --text-4xl: 2.25rem;     /* 36px */
  --text-5xl: 3rem;        /* 48px */
  --text-6xl: 3.75rem;     /* 60px */

  /* Font Weights */
  --font-normal: 400;
  --font-medium: 500;
  --font-semibold: 600;
  --font-bold: 700;

  /* Line Heights */
  --leading-none: 1;
  --leading-tight: 1.25;
  --leading-snug: 1.375;
  --leading-normal: 1.5;
  --leading-relaxed: 1.625;
  --leading-loose: 2;

  /* Letter Spacing */
  --tracking-tighter: -0.05em;
  --tracking-tight: -0.025em;
  --tracking-normal: 0;
  --tracking-wide: 0.025em;
  --tracking-wider: 0.05em;
  --tracking-widest: 0.1em;
}
```

## Komplette Typografie-Definition

| Element | Größe | Gewicht | Zeilenhöhe | Tracking | Schrift |
|---------|-------|---------|------------|----------|---------|
| Display | 3.75rem (60px) | 700 | 1.1 | -0.02em | Display |
| H1 | 3rem (48px) | 700 | 1.2 | -0.02em | Display |
| H2 | 1.875rem (30px) | 600 | 1.3 | -0.01em | Display |
| H3 | 1.5rem (24px) | 600 | 1.4 | 0 | Body |
| H4 | 1.25rem (20px) | 600 | 1.4 | 0 | Body |
| H5 | 1.125rem (18px) | 600 | 1.5 | 0 | Body |
| H6 | 1rem (16px) | 600 | 1.5 | 0.025em | Body |
| Body Large | 1.125rem (18px) | 400 | 1.6 | 0 | Body |
| Body | 1rem (16px) | 400 | 1.6 | 0 | Body |
| Body Small | 0.875rem (14px) | 400 | 1.5 | 0 | Body |
| Caption | 0.75rem (12px) | 400 | 1.5 | 0.025em | Body |
| Overline | 0.75rem (12px) | 600 | 1.5 | 0.1em | Body |
| Label | 0.875rem (14px) | 500 | 1.25 | 0.025em | Body |
| Mono | 0.875rem (14px) | 400 | 1.5 | 0 | Mono |

## Tailwind CSS Config

```javascript
// tailwind.config.js
module.exports = {
  theme: {
    fontFamily: {
      display: ['Playfair Display', 'Georgia', 'serif'],
      body: ['Inter', '-apple-system', 'BlinkMacSystemFont', 'sans-serif'],
      mono: ['JetBrains Mono', 'Fira Code', 'monospace'],
    },
    fontSize: {
      '2xs': ['0.625rem', { lineHeight: '1.5' }],
      'xs': ['0.75rem', { lineHeight: '1.5' }],
      'sm': ['0.875rem', { lineHeight: '1.5' }],
      'base': ['1rem', { lineHeight: '1.6' }],
      'lg': ['1.125rem', { lineHeight: '1.6' }],
      'xl': ['1.25rem', { lineHeight: '1.4' }],
      '2xl': ['1.5rem', { lineHeight: '1.3' }],
      '3xl': ['1.875rem', { lineHeight: '1.2' }],
      '4xl': ['2.25rem', { lineHeight: '1.2' }],
      '5xl': ['3rem', { lineHeight: '1.1' }],
      '6xl': ['3.75rem', { lineHeight: '1.1' }],
    },
  },
};
```

## CSS Utility Classes

```css
/* Display */
.text-display {
  font-family: var(--font-display);
  font-size: var(--text-6xl);
  font-weight: var(--font-bold);
  line-height: var(--leading-none);
  letter-spacing: var(--tracking-tight);
}

/* Headings */
.text-h1 {
  font-family: var(--font-display);
  font-size: var(--text-5xl);
  font-weight: var(--font-bold);
  line-height: var(--leading-tight);
  letter-spacing: var(--tracking-tight);
}

.text-h2 {
  font-family: var(--font-display);
  font-size: var(--text-3xl);
  font-weight: var(--font-semibold);
  line-height: var(--leading-snug);
  letter-spacing: var(--tracking-tight);
}

.text-h3 {
  font-size: var(--text-2xl);
  font-weight: var(--font-semibold);
  line-height: var(--leading-snug);
}

.text-h4 {
  font-size: var(--text-xl);
  font-weight: var(--font-semibold);
  line-height: var(--leading-snug);
}

/* Body */
.text-body-lg {
  font-size: var(--text-lg);
  line-height: var(--leading-relaxed);
}

.text-body {
  font-size: var(--text-base);
  line-height: var(--leading-relaxed);
}

.text-body-sm {
  font-size: var(--text-sm);
  line-height: var(--leading-normal);
}

/* UI Text */
.text-label {
  font-size: var(--text-sm);
  font-weight: var(--font-medium);
  line-height: var(--leading-tight);
  letter-spacing: var(--tracking-wide);
  text-transform: uppercase;
}

.text-caption {
  font-size: var(--text-xs);
  line-height: var(--leading-normal);
  color: var(--text-muted);
}

.text-mono {
  font-family: var(--font-mono);
  font-size: var(--text-sm);
}
```

## Anwendungsbeispiele

### Landing Page Hero
```html
<h1 class="text-display">Elegante Lösungen für komplexe Probleme</h1>
<p class="text-body-lg">Entdecke die Zukunft des digitalen Designs.</p>
```

### Dashboard Header
```html
<h2 class="text-h2">Übersicht</h2>
<p class="text-body-sm text-muted">Letzte Aktualisierung: vor 5 Minuten</p>
```

### Form Labels
```html
<label class="text-label">E-Mail-Adresse</label>
<input type="email" class="text-body" placeholder="name@beispiel.de" />
<p class="text-caption">Wir senden dir eine Bestätigungsmail.</p>
```

### Data Table
```html
<th class="text-label">Status</th>
<td class="text-body-sm">
  <code class="text-mono">user_8f3d2a9</code>
</td>
```

## Responsive Skalierung

Für mobile Geräte reduziere Display-Größen:

```css
@media (max-width: 768px) {
  :root {
    --text-6xl: 2.25rem;  /* 36px statt 60px */
    --text-5xl: 1.875rem; /* 30px statt 48px */
    --text-4xl: 1.5rem;   /* 24px statt 36px */
  }
}
```

## Font Pairing Empfehlungen

| Stil | Display | Body |
|------|---------|------|
| **Klassisch/Elegant** | Playfair Display | Inter |
| **Modern/Technisch** | Space Grotesk | Inter |
| **Freundlich/Warm** | DM Serif | DM Sans |
| **Mutig/Dramatisch** | Oswald | Source Sans Pro |
| **Minimal/Swiss** | Switzer | Inter |

## Checkliste

- [ ] Font-Families ausgewählt und geladen?
- [ ] Type Scale definiert?
- [ ] Line Heights angepasst?
- [ ] Font Weights konsistent?
- [ ] Responsive Breakpoints berücksichtigt?
- [ ] Font Loading optimiert (swap)?
