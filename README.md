# ui/ux

## UI/UX Fix Checklist (Actionable for Dev)

### 🔐 1. Login Page – Visual Consistency

- [ ]  Redesign the **login page UI** to visually match the **Bot Page theme**
- [ ]  Align **colors, typography, spacing, and shadows** with Bot Page design system
- [ ]  Ensure button styles, inputs, and hover states match existing Bot UI
- [ ]  Remove any legacy or mismatched styling

---

### 📌 2. Sidebar (Bot Page) – Profile & Settings Behavior

- [ ]  When **sidebar is expanded**:
    - [ ]  Profile section remains at the **bottom** (no change)
- [ ]  When **sidebar is collapsed**:
    - [ ]  Move the **profile icon to the bottom**, not the top
    - [ ]  Replace the profile icon with a **Settings icon**
    - [ ]  Clicking Settings opens the existing **settings popup**
- [ ]  Ensure smooth transition/animation between expanded ↔ collapsed states

---

### 📱 3. Responsive Design (All Screens)

- [ ]  Ensure full responsiveness for:
    - [ ]  Mobile
    - [ ]  Tablet
    - [ ]  Laptop
    - [ ]  Large / high-resolution displays
- [ ]  Verify layout consistency for:
    - [ ]  Sidebar
    - [ ]  Toolbars
    - [ ]  Viewers
    - [ ]  Tables & grids
- [ ]  No overflow, clipped content, or broken alignment at any breakpoint

---

### 🐞 4. Defect Page – Initial Load Bug

- [ ]  On initial load of **Defect module**:
    - [ ]  Default view page should render first
    - [ ]  Filter panel should **NOT** auto-load or block the view
- [ ]  Filters should load **only after user interaction**
- [ ]  Confirm correct default state handling

---

### 📊 5. Defect Log – Grid & Theme Alignment

- [ ]  Add **grid lines** to the defect log table
- [ ]  Grid lines must:
    - [ ]  Match the **Bot Page color theme**
    - [ ]  Be subtle (not visually noisy)
- [ ]  Ensure row/column alignment is consistent across screen sizes
- [ ]  Maintain readability in both light/dark (if applicable)

---

### 🎨 6. Viewer Background Color (Library)

Applies to:

- Image Viewer
- PDF Viewer
- DOCX Viewer

Checklist:

- [ ]  Change viewer background color to align with **overall app theme**
- [ ]  Avoid harsh white/black backgrounds unless theme demands it
- [ ]  Ensure annotations, toolbars, and content remain clearly visible
- [ ]  Background should be consistent across all viewer types

---

### 📂 7. Folder List Visibility Issue

- [ ]  Fix issue where **list folders are not displaying**
- [ ]  Verify:
    - [ ]  Folder rendering logic
    - [ ]  State updates after create/delete/move
    - [ ]  API or local data sync
- [ ]  Ensure folders appear correctly in:
    - [ ]  Root view
    - [ ]  Nested views
- [ ]  Confirm UI updates without manual refresh

---

### ✅ Final Verification (Must Pass)

- [ ]  No existing logic or features are broken
- [ ]  UI behavior matches expected UX flow
- [ ]  Visual consistency maintained across modules
- [ ]  Tested on multiple screen sizes
