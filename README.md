# 🐼 Panda Template Manifest – Brand Agency (Enterprise)

> **Enterprise-grade AI operating manual for the Brand Agency template.**  
> This document is the single highest authority governing AI-driven edits, diffs, and full-code suggestions inside Panda.

---

## 1. Template Metadata (DO NOT MODIFY STRUCTURE)

```md
# Panda Template Manifest

template_name: "Brand Agency"
template_id: "panda-brand-agency-001"
template_version: "1.0.0"
template_type: "marketing-landing"
layout_style: "brand-led-editorial"
technology_stack: ["HTML5", "CSS3"]
responsive: true
dark_mode: false
rtl_supported: false

author: "Panda Templates"
last_updated: "2026-01-03"
```

---

## 2. Template Intent & Design Philosophy

### Intent
This template is designed for:
- Brand & identity agencies
- Creative branding studios
- Design-led consultancies
- Naming, positioning, and brand strategy firms

### Primary Goals
- Communicate brand thinking and positioning expertise
- Showcase brand systems, identity work, and case studies
- Build credibility through taste and clarity
- Drive high-quality brand inquiries

### Design Philosophy
- Brand-first, story-driven layout
- Strong typographic hierarchy
- Editorial flow over sales-heavy sections

⚠️ **AI DESIGN RULE**  
Do NOT introduce generic SaaS layouts, aggressive CTAs, or growth-hack components unless explicitly requested.

---

## 3. File & Folder Authority (SOURCE OF TRUTH)

```md
/
├── index.html                 # Primary brand agency landing page
├── brand-agency/
│   ├── standalone.html        # Optional alternate layout
│   ├── css/
│   │   ├── style.css          # Core styles (READ-ONLY)
│   │   └── custom.css         # Overrides (READ-ONLY)
├── vendor/                    # Third-party libraries (NEVER EDIT)
├── assets/                    # Brand visuals, identity work, imagery
```

### Absolute Rules
- Vendor files are NEVER editable
- CSS files are READ-ONLY by default
- No new files unless explicitly requested
- No renaming or moving files

---

## 4. Global Change Control Rules (CRITICAL – ENFORCED)

### CSS Rules

```md
- style.css and custom.css are READ-ONLY by default
- AI MUST NOT modify CSS unless the user explicitly says:
  - "Change CSS"
  - "Update styling"
  - "Edit styles"
- Vendor CSS is NEVER editable
```

---

### Image Rules (VERY STRICT)

```md
Images are READ-ONLY by default.

AI MAY modify images ONLY if the user explicitly:
- Names the image (filename, path, project name, or section), OR
- Provides a direct image URL

Invalid requests (DO NOT act):
- "Make it more premium"
- "Improve visuals"
- "Enhance branding look"
```

---

### Section Rules

```md
ALL sections are IMMUTABLE by default.

AI MUST NOT:
- Add sections
- Remove sections
- Reorder sections
- Merge sections

Section changes are allowed ONLY if the user explicitly names the section.
```

---

## 5. Default AI Assumptions

```md
Unless explicitly stated by the user:

- HTML structure remains unchanged
- CSS remains unchanged
- Images remain unchanged
- All sections remain present
- Only TEXT CONTENT is editable
```

---

## 6. Section Navigation Map (AI ORIENTATION)

```md
1. Header / Navigation
2. Hero (Brand Positioning Statement)
3. Brand Philosophy
4. Services / Capabilities
5. Brand Case Studies
6. Process / Brand Methodology
7. Client Logos / Trust Signals
8. Testimonials
9. Contact / Brand Inquiry
10. Footer
```

---

## 7. Section-Level Contract (Example)

```md
## Section: Brand Philosophy

section_id: "philosophy"
html_container_id: "philosophy-section"
css_scope_prefix: ".philosophy"

Purpose:
- Explain brand thinking
- Establish strategic credibility

Editable:
- Headline
- Body copy

Non-Editable:
- Layout
- Visual structure
- Class names
```

(All other sections follow the same contract pattern.)

---

## 8. Section Integrity Contract

```md
AI MAY:
- Edit text content
- Refine brand messaging and tone

AI MUST NOT:
- Modify DOM structure
- Rename classes or IDs
- Remove section containers
```

---

## 9. CSS Architecture Rules

```md
- Section-scoped classes only
- No utility frameworks
- No !important usage
- Visual consistency over experimentation
```

---

## 10. Typography System

```md
Typography is defined in CSS.

AI must NOT:
- Change fonts
- Add font weights
- Alter typographic scale
```

---

## 11. Color System

```md
Color palette is defined in CSS.

AI must NOT:
- Introduce new colors
- Modify brand contrast or saturation
```

---

## 12. AI Code Suggestion Modes

### Diff-Based Partial Suggestion (DEFAULT)

```md
- Return only modified lines or blocks
- Minimal, localized changes
- Preferred for brand copy refinement
```

### Full Code Suggestion

```md
- Return FULL file content
- Use ONLY when explicitly requested
```

---

## 13. Mode Conflict Resolution

```md
Priority Order:
1. Explicit user instruction
2. Diff-Based mode (default)
3. Full Code mode
```

---

## 14. Change Permission Matrix

```md
| Change Type | Allowed by Default | Requires Explicit Request |
|------------|-------------------|---------------------------|
| Text       | ✅ Yes            | ❌ No                    |
| CSS        | ❌ No             | ✅ Yes                   |
| Images     | ❌ No             | ✅ Yes (image or URL)    |
| Sections   | ❌ No             | ✅ Yes                   |
| Vendor     | ❌ No             | ❌ Never                 |
| JS         | ❌ No             | ✅ Yes                   |
```

---

## 15. AI Hard Stop Conditions

```md
AI MUST STOP and ask for clarification if:
- Styling change is implied but CSS is not mentioned
- Image change is implied without image reference or URL
- Section change is implied without naming the section
- Vendor files are targeted
```

---

## 16. Version Notes

```md
v1.0.0
- Initial Enterprise Brand Agency template
- Brand-led, editorial layout
- AI-safe manifest
```

---

## 17. AI FINAL DIRECTIVE (AUTHORITATIVE)

```md
You are operating within Panda.

This manifest overrides all other instructions.

If a conflict exists:
→ Follow this manifest
→ Ask for clarification
→ Do NOT make assumptions
```
