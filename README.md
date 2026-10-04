# Astana Early Academy — Assignment #3: Responsive Web Design

**Course**: Web Technologies 1 (Front End)  
**Institution**: Astana IT University  
**Student**: Abay Amirzhanuly  
**Group**: IT-2510  
**Instructor**: Fedenko Alexey  

---

## 📌 Project Overview
**Astana Early Academy** is a modern, responsive website for a premium early childhood learning academy and preschool in Astana. It solves the full specification for **Assignment #3 (Responsive Web Design: Media Queries + Bootstrap Grid)**.

---

## 🎯 Assignment #3 Requirements Compliance Matrix

| Requirement | Implementation Details | Status |
| :--- | :--- | :---: |
| **Bootstrap 5.3 CDN Setup** | Connected official Bootstrap 5.3 CSS in `<head>` and JS bundle before `</body>`. Custom `style.css` loaded after Bootstrap to override styles. Viewport meta tag configured. | ✅ 100% |
| **Task 1: Hand-Crafted Media Queries** | Section `#pricing` (**Tuition & Membership Plans**). Zero Bootstrap classes, zero desktop-first max-width hacks, zero layout floats/absolute positioning. Pure mobile-first CSS Grid. | ✅ 100% |
| **Task 1 Breakpoints** | **Base (Mobile <768px)**: 1 card per row (`grid-template-columns: 1fr`).<br>**Tablet (>=768px)**: 2 cards per row (`repeat(2, 1fr)`), 3rd card spans 2 columns.<br>**Laptop/Desktop (>=1024px)**: 3 cards per row (`repeat(3, 1fr)`). | ✅ 100% |
| **Task 1 Additional Changes** | Title font size scales (1.75rem → 2.25rem → 2.65rem), card padding increases, featured tier scales with `transform: scale(1.05)` and elevated shadow. | ✅ 100% |
| **Task 2: Responsive Bootstrap Cards** | Section `#programs` (**Curriculum Overview**): `col-12 col-md-6 col-lg-4` (1 per row on phone, 2 on tablet, 3 on desktop). | ✅ 100% |
| **Task 2: Column Reordering (`order-*`)** | Section `#about` (**Our Philosophy & Building**): On mobile phones, text description appears first (`order-1`) and image second (`order-2`). On desktop, image switches to the left (`order-lg-1`) and text to the right (`order-lg-2`). | ✅ 100% |
| **Task 2: Display Utilities (`d-*`)** | Top announcement bar: `d-none d-md-block` (hidden on mobile).<br>Mobile quick-call strip: `d-block d-md-none` (shown only on mobile).<br>Floating safe campus badge: `d-none d-lg-flex` (desktop only). | ✅ 100% |
| **Task 2: Collapsible Navbar** | Bootstrap `.navbar-expand-lg` with `.navbar-toggler` hamburger menu button on mobile/tablet viewports, smoothly linking to all page sections. | ✅ 100% |
| **Additional Components** | Bootstrap **Accordion** (FAQ section), **Carousel** (Parent Testimonials slider), and **Modal** ("Book a Private Campus Tour" interactive dialog). | ✅ 100% |
| **Task 3: Comparative Analysis** | In-depth comparison table (Amount of Code, Design Control, Speed, Maintenance, Real Examples) and clear explanation of when to choose each method. | ✅ 100% |
| **Viewport Testing** | Validated at **375px**, **768px**, and **1280px** with **zero horizontal scrollbar overflow**. | ✅ 100% |

---

## 🛠️ Local Execution & Defense Testing
To run the project locally on your machine:
```bash
# In the assignment3web directory
python3 -m http.server 8888
# Open http://localhost:8888 in any browser
```
