# Cascabel.ai Website Structure

## 📁 File Organization

### ✅ **PRODUCTION FILES** (Use these)

```
cascabel-website/
├── index.html              ← HOMEPAGE (main landing page)
├── case-sentinel.html      ← Case Study: Sentinel (Predictive Maintenance)
├── case-mercado.html       ← Case Study: Mercado (Materials Management)
└── case-concilia.html      ← Case Study: Concilia (Real Estate Reconciliation)
```

### ❌ **DUPLICATE FILES** (Do NOT use - these are duplicates/old versions)

**From your upload:**
- `Cascabel_io_Fwd__Cascabel_io_website_case-manufacturing.html` - Old version (Grupo Metálicos)
- `Cascabel_io_Fwd__Cascabel_io_website_case-manufacturing_1.html` - Old version (Automotriz)
- `Cascabel_io_Fwd__Cascabel_io_website_case-manufacturing_3.html` - Duplicate of Sentinel
- `Cascabel_io_Fwd__Cascabel_io_website_case-realestate.html` - Old version (Patrimonial Lomas)
- `Cascabel_io_Fwd__Cascabel_io_website_case-realestate_1.html` - Old version

**These were older iterations and should be deleted.**

---

## 🏠 Website Structure

### **Homepage** - `index.html`
- **Title:** "cascabel.ai — Servicios"
- **Purpose:** Main landing page with services overview
- **Navigation:** Links to case studies

### **Case Studies**

#### 1. **Sentinel** - `case-sentinel.html`
- **Title:** "Manufactura — Sentinel · cascabel.ai"
- **Industry:** Manufacturing (Steel plant)
- **Product:** Predictive maintenance with IoT + ML
- **Key Metrics:**
  - ~70% reduction in unplanned failures
  - +12pt OEE above industry benchmark
  - ~3× ROI in first year
  - 48-72h advance warning window

#### 2. **Mercado** - `case-mercado.html`
- **Title:** "Gestión de Materiales — Mercado · cascabel.ai"
- **Industry:** Industrial Manufacturing (North Mexico)
- **Product:** Materials management & pricing intelligence
- **Key Metrics:**
  - ~25% reduction in effective material prices
  - -40% immobilized inventory
  - 3-5 week price increase anticipation window
  - <5 months ROI

#### 3. **Concilia** - `case-concilia.html`
- **Title:** "Administración Inmobiliaria — Concilia · cascabel.ai"
- **Industry:** Real Estate Management (200+ units, CDMX)
- **Product:** Payment reconciliation platform
- **Key Metrics:**
  - ~65% less time in monthly closing
  - -90% errors in account statements
  - >90% owner satisfaction with punctuality
  - 3 months to recover investment

---

## 🔗 Navigation Structure

All case study pages have:
- **Back link:** `← Casos de éxito` → links to `index.html`
- **Logo:** `cascabel.ai` → links to `index.html`
- **Footer CTA:** `Hablar con un experto →` → `mailto:contacto@cascabel.ai`

---

## 🎨 Design System

### **Color Palette**
```css
--ink:     #1A1008  /* Dark background */
--chile:   #C4521A  /* Primary accent (red-orange) */
--terra:   #E8743B  /* Secondary accent (lighter orange) */
--maguey:  #B8845A  /* Muted tan */
--masa:    #FAEEDA  /* Cream/beige */
--smoke:   #888780  /* Gray */
```

### **Typography**
- **Serif:** Cormorant Garamond (headings, metrics)
- **Sans:** DM Sans (body text)

### **Layout**
- Fixed navigation bar
- Hero section with 2-column grid (intro + metrics)
- 3-column content grid (Problem → Solution → Impact)
- Responsive breakpoint at 768px

---

## 🚀 Deployment Checklist

1. **Upload these 4 files to your web server:**
   - [ ] `index.html`
   - [ ] `case-sentinel.html`
   - [ ] `case-mercado.html`
   - [ ] `case-concilia.html`

2. **Delete old/duplicate files from server** (if previously uploaded)

3. **Test navigation:**
   - [ ] Homepage loads at root URL
   - [ ] All "← Casos de éxito" links return to homepage
   - [ ] Logo clicks return to homepage
   - [ ] Email links work: `contacto@cascabel.ai`

4. **Test responsive design:**
   - [ ] Desktop (>768px)
   - [ ] Mobile (<768px)

---

## 📝 Content Updates

### To add a new case study:
1. Copy `case-sentinel.html` as a template
2. Update these sections:
   - `<title>` tag
   - Hero tags, client name, headline
   - Metrics (4 cards)
   - 3 columns: Problem → Solution → Impact
   - Quotes (optional)
3. Save as `case-[product-name].html`
4. Add link to homepage `index.html`

### To update homepage:
- Edit `index.html`
- Main sections are clearly commented in the HTML

---

## 🐛 Known Issues / Notes

- All files currently link to `index.html` for the back button
- Google Fonts are loaded from CDN (requires internet)
- Fade-in animations use Intersection Observer (modern browsers only)
- Email contact is `contacto@cascabel.ai` (ensure this email exists)

---

## 📧 Contact
- **Email:** contacto@cascabel.ai
- **Location:** Ciudad de México
- **Copyright:** © 2025 cascabel.ai
