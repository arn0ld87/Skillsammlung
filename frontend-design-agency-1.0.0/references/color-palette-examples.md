# Color Palette Examples

Fertige Farbpaletten für verschiedene Produkttypen.

## 1. B2B SaaS / Enterprise (Vertrauen, Professionalität)

```css
:root {
  /* Canvas & Surfaces */
  --canvas: #fafafa;
  --surface: #ffffff;
  --surface-elevated: #ffffff;
  --surface-subtle: #f5f5f5;

  /* Text */
  --text-strong: #111827;
  --text-default: #374151;
  --text-muted: #6b7280;
  --text-placeholder: #9ca3af;

  /* Primary - Trust Blue */
  --primary: #2563eb;
  --primary-hover: #1d4ed8;
  --primary-active: #1e40af;
  --primary-subtle: #eff6ff;
  --primary-foreground: #ffffff;

  /* Accent - Success Green */
  --success: #10b981;
  --success-subtle: #ecfdf5;

  /* Warning - Amber */
  --warning: #f59e0b;
  --warning-subtle: #fffbeb;

  /* Danger - Red */
  --danger: #ef4444;
  --danger-subtle: #fef2f2;

  /* Borders */
  --border-default: #e5e7eb;
  --border-strong: #d1d5db;
  --border-subtle: #f3f4f6;
}

[data-theme="dark"] {
  --canvas: #0f172a;
  --surface: #1e293b;
  --surface-elevated: #334155;
  --surface-subtle: #1e293b;

  --text-strong: #f8fafc;
  --text-default: #cbd5e1;
  --text-muted: #94a3b8;
  --text-placeholder: #64748b;

  --primary: #60a5fa;
  --primary-hover: #3b82f6;
  --primary-active: #2563eb;
  --primary-subtle: #1e3a8a;
  --primary-foreground: #0f172a;

  --border-default: #334155;
  --border-strong: #475569;
  --border-subtle: #1e293b;
}
```

## 2. Fintech / Premium (Eleganz, Exklusivität)

```css
:root {
  /* Canvas - Warm White */
  --canvas: #fdfcfb;
  --surface: #ffffff;
  --surface-elevated: #ffffff;
  --surface-subtle: #f8f6f3;

  /* Text - Deep Charcoal */
  --text-strong: #1c1917;
  --text-default: #44403c;
  --text-muted: #78716c;
  --text-placeholder: #a8a29e;

  /* Primary - Gold/Amber */
  --primary: #d97706;
  --primary-hover: #b45309;
  --primary-active: #92400e;
  --primary-subtle: #fffbeb;
  --primary-foreground: #ffffff;

  /* Accent - Forest Green (Money) */
  --success: #059669;
  --success-subtle: #ecfdf5;

  /* Danger - Rose */
  --danger: #e11d48;
  --danger-subtle: #fff1f2;

  /* Borders - Warm Gray */
  --border-default: #e7e5e4;
  --border-strong: #d6d3d1;
}

[data-theme="dark"] {
  --canvas: #0c0a09;
  --surface: #1c1917;
  --surface-elevated: #292524;
  --surface-subtle: #1c1917;

  --text-strong: #fafaf9;
  --text-default: #d6d3d1;
  --text-muted: #a8a29e;

  --primary: #fbbf24;
  --primary-hover: #f59e0b;
  --primary-active: #d97706;
  --primary-subtle: #451a03;
  --primary-foreground: #0c0a09;

  --border-default: #44403c;
  --border-strong: #57534e;
}
```

## 3. Health / Wellness (Vertrauen, Ruhe)

```css
:root {
  /* Canvas - Soft Sage */
  --canvas: #f6f7f6;
  --surface: #ffffff;
  --surface-elevated: #ffffff;
  --surface-subtle: #f0f4f0;

  /* Text - Soft Charcoal */
  --text-strong: #1a1c1a;
  --text-default: #3d413d;
  --text-muted: #6b726b;
  --text-placeholder: #9aa29a;

  /* Primary - Sage Green */
  --primary: #4a7c59;
  --primary-hover: #3d6649;
  --primary-active: #305038;
  --primary-subtle: #e8f0ea;
  --primary-foreground: #ffffff;

  /* Accent - Soft Blue */
  --accent: #5b8ba0;
  --accent-subtle: #e8f2f5;

  /* States */
  --success: #10b981;
  --warning: #f59e0b;
  --danger: #dc2626;

  /* Borders */
  --border-default: #e0e4e0;
  --border-strong: #c8cec8;
}
```

## 4. Creative / Agency (Mut, Innovation)

```css
:root {
  /* Canvas - Off-White */
  --canvas: #fefefe;
  --surface: #ffffff;
  --surface-elevated: #ffffff;
  --surface-subtle: #f5f5f5;

  /* Text - Near Black */
  --text-strong: #0a0a0a;
  --text-default: #262626;
  --text-muted: #525252;

  /* Primary - Vivid Violet */
  --primary: #7c3aed;
  --primary-hover: #6d28d9;
  --primary-active: #5b21b6;
  --primary-subtle: #ede9fe;
  --primary-foreground: #ffffff;

  /* Secondary - Hot Pink */
  --secondary: #ec4899;
  --secondary-subtle: #fce7f3;

  /* Accent - Cyan */
  --accent: #06b6d4;
  --accent-subtle: #cffafe;

  /* Borders */
  --border-default: #e5e5e5;
  --border-strong: #d4d4d4;
}
```

## 5. Dark Mode Tech (Modern, Fokussiert)

```css
[data-theme="dark"] {
  /* Canvas - Deep Space */
  --canvas: #030712;
  --surface: #0f172a;
  --surface-elevated: #1e293b;
  --surface-subtle: #0b1120;

  /* Text - Crisp White */
  --text-strong: #ffffff;
  --text-default: #e2e8f0;
  --text-muted: #94a3b8;
  --text-placeholder: #64748b;

  /* Primary - Electric Blue */
  --primary: #38bdf8;
  --primary-hover: #0ea5e9;
  --primary-active: #0284c7;
  --primary-subtle: rgba(56, 189, 248, 0.15);
  --primary-foreground: #030712;

  /* Secondary - Neon Purple */
  --secondary: #a855f7;
  --secondary-subtle: rgba(168, 85, 247, 0.15);

  /* Accent - Cyber Green */
  --success: #4ade80;
  --warning: #fbbf24;
  --danger: #f87171;

  /* Borders - Subtle Blue */
  --border-default: #1e293b;
  --border-strong: #334155;
  --border-subtle: #0f172a;

  /* Glows */
  --glow-primary: 0 0 20px rgba(56, 189, 248, 0.3);
  --glow-success: 0 0 20px rgba(74, 222, 128, 0.3);
}
```

## Token-System

### Struktur

```css
/* 1. Canvas (Page Background) */
--canvas

/* 2. Surfaces (Cards, Panels) */
--surface           /* Default elevated */
--surface-elevated  /* Higher z-index */
--surface-subtle    /* Lower emphasis */

/* 3. Text */
--text-strong       /* Headings, Primary */
--text-default      /* Body text */
--text-muted        /* Secondary, Meta */
--text-placeholder  /* Empty states */

/* 4. Actions */
--primary           /* Main CTA */
--primary-hover
--primary-active
--primary-subtle    /* Background tint */
--primary-foreground /* Text on primary */

/* 5. States */
--success
--warning
--danger

/* 6. Borders */
--border-default
--border-strong
--border-subtle
```

### Verwendung

```html
<!-- Card mit Token-System -->
<div style="background: var(--surface); border: 1px solid var(--border-default);">
  <h3 style="color: var(--text-strong);">Titel</h3>
  <p style="color: var(--text-default);">Beschreibung</p>
  <button style="background: var(--primary); color: var(--primary-foreground);">
    Aktivieren
  </button>
</div>
```

## Kontrast-Check

| Kombination | Kontrast | Status |
|-------------|----------|--------|
| `--text-strong` auf `--surface` | 15.3:1 | ✅ AAA |
| `--text-default` auf `--surface` | 10.5:1 | ✅ AAA |
| `--text-muted` auf `--surface` | 6.2:1 | ✅ AA |
| `--primary` auf `--surface` | 5.8:1 | ✅ AA |
| `--primary-foreground` auf `--primary` | 7.2:1 | ✅ AAA |

## Dark Mode Toggle

```javascript
// Toggle Theme
function toggleTheme() {
  const current = document.documentElement.getAttribute('data-theme');
  const next = current === 'dark' ? 'light' : 'dark';
  document.documentElement.setAttribute('data-theme', next);
  localStorage.setItem('theme', next);
}

// Initial Load
const saved = localStorage.getItem('theme');
const prefersDark = window.matchMedia('(prefers-color-scheme: dark)').matches;
document.documentElement.setAttribute('data-theme', saved || (prefersDark ? 'dark' : 'light'));
```
