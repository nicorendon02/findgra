# FINDGRA low-fi prototype

> **Note:** This document contains the original prompt used with **Google Gemini** to generate the low-fidelity prototype for FINDGRA (Find Grandparents app). The resulting HTML/CSS implementation can be found in [index.html](index.html).

---

## Original prompt for Google Gemini

You are a senior UI/UX designer and UI implementer. Recreate the EXACT same six mobile app interfaces for an app named "FINDGRA" described below: same layout, spacing, typography feel, shapes, corner radii, shadows, button sizes, Font Awesome Icon placement, and overall visual hierarchy. The only change you may make is: all UI text must be in English (keep the brand name "FINDGRA" and keep the credits line with names). Do not invent new UI elements beyond what is explicitly described.

### Important rules

**1)** Pixel-perfect recreation: match the composition as closely as possible (positions, alignments, proportions).

**2)** Preserve the purple gradient/abstract background style across all screens, white rounded card panels, and flat/simple line Font Awesome Icon style.

**3)** Keep the same screen order and content. Produce all 6 screens.

**4)** Use English text exactly as specified below.

**5)** Output deliverables:
   - **A)** A concise UI spec (colors, fonts, spacing, component styles).
   - **B)** Screen-by-screen breakdown listing every visible element in order (top→bottom).
   - **C)** Implementation output in the format I request next (default: HTML+CSS, responsive for a 9:16 phone). If you can't access original images, recreate them using CSS/SVG approximations.

---

### App style (global)

- **Background:** purple gradient/abstract shapes (soft blobs/waves).
- **Foreground:** white rounded rectangular cards for content.
- **Typography:** modern sans-serif; headings bold; one keyword in headings highlighted in purple.
- **Inputs:** rounded, light gray border, subtle shadow or none.
- **Buttons:** wide pill buttons, bold labels.
- **Font Awesome Icons:** simple/flat line style, consistent stroke weight.
- **Spacing:** Consistent safe-area margins and generous vertical spacing.

---

### Screens to recreate (6)

#### Screen 1 — Splash / landing

- Full-screen purple abstract background.
- Center/top area: FINDGRA logo mark + "FINDGRA".
- Tagline centered inside/above a white rounded card area:
  **"Safety for your loved ones, peace of mind for you."**
- Bottom area: small credits line exactly:
  **"© 2026 - Nicolas Rendon Arias"**

#### Screen 2 — Login

- Purple abstract background.
- White rounded card centered vertically containing:
  - Heading: **"Sign In"** with one word emphasized in purple (match emphasis style).
  - Two labeled or placeholder inputs:
    - "Username"
    - "Password"
  - Primary pill button: **"Sign In"**
  - Link-style text: "Forgot my password"
  - Secondary action button or link: **"Create account"**
- Keep consistent spacing, rounded corners, and alignment.

#### Screen 3 — Register user

- Purple abstract background.
- White rounded card with form fields (top→bottom):
  - Heading: **"Register User"** (with a purple highlighted word in the heading).
  - Inputs:
    - "Full name"
    - "Username"
    - "Email"
    - "Mobile phone"
    - "Home address"
  - Checkbox row: "I agree to the processing of personal data."
  - Primary pill button: **"Create account"**
- Bottom area: small credits line exactly:
  **"© 2026 - Nicolas Rendon Arias"**

#### Screen 4 — Home / menu

- Purple abstract background.
- Top app bar area:
  - Left: FINDGRA logo + wordmark.
  - Right: hamburger/menu Font Awesome Icon.
- Welcome text near top-left within a white or transparent area:
  **"Welcome, User"**
- Main content: a vertical stack of large rounded pill menu buttons, each with a Font Awesome Icon on the left and text label:
  1) **"My routes"**
  2) **"My reminders"**
  3) **"My devices"**
  4) **"Call Emergency Services"**
  5) **"Start route"**
- Buttons are colored (distinct colors per item) but still match the same pill size and spacing.
- Bottom area: **"v0.1 BETA"**.
- Bottom area: small credits line exactly:
  **"© 2026 - Nicolas Rendon Arias"**

#### Screen 5 — Route in progress (map + timer)

- Purple abstract background.
- Top row (inside a white rounded card or directly above map card):
  - Left label: **"Route name"**
  - Right label: **"Time 02:00:15"**
- Large rounded rectangle "map" area below (use a map placeholder graphic-style block).
- Below map: a prominent primary pill button:
  **"End route"**
  (button is red, strong emphasis)
- Keep the same hierarchy: labels → map → action.

#### Screen 6 — My devices (list)

- Purple abstract background.
- White rounded card content:
  - Title: **"My Devices"**
  - List of 3 device rows (each row includes):
    - Left: simple device Font Awesome Icon (tracker-like).
    - Middle: device name in bold: "iPhone 7 Plus", "Samsung S22", "MacBook Air M2".
    - Subtext: **"Registered on <date>"** (use "22/12/2022", "10/09/2023", "11/09/2023" respectively).
  - Bottom: large orange pill button: **"Edit devices"**
- Bottom area: credits line exactly:
  **"© 2026 - Nicolas Rendon Arias"****

---

### Text must match exactly (English)

- "Safety for your loved ones, peace of mind for you."
- "Username" | "Password" | "Sign In" | "Forgot my password" | "Create account"
- "Register User" | "Full name" | "Email" | "Mobile phone" | "Home address"
- "I agree to the processing of personal data."
- "Welcome, User"
- "My routes" | "My reminders" | "My devices" | "Call Emergency Services" | "Start route"
- "Tracking Portal" | "Pedestrian Monitoring"
- "Route name" | "Time 02:00:15" | "End route"
- "My Devices" | "Registered on" | "Edit devices"
- "v0.1 BETA"
- "© 2026 - Nicolas Rendon Arias"

---

### Final instructions

1) Identify all reusable components (buttons, input fields, headers, cards).
2) Provide the UI spec (colors/typography/spacing).
3) Produce the six screen definitions and then generate the default implementation (HTML+CSS) that visually matches this specification as closely as possible.
