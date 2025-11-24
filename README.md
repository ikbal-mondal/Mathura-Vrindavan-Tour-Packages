# Mathura Vrindavan Tour Packages – Website

A fully responsive, SEO-friendly travel website for Mathura–Vrindavan tour packages, built using **pure HTML5 + Tailwind CSS (CDN)**.  
The project includes multiple pages such as tour listings, bus packages, payment flow, enquiry forms, and booking status — all with a modern UI and mobile-first design.

---

## 🔗 Live Link

View the project online:  
[**Mathura Vrindavan Tour Packages — Live Site**](https://mathura-vrindavan-tour-pakage.netlify.app/)

---

## 📁 Project Structure & Pages

Each HTML file represents a specific page or section of the website.  
All pages are:

- Fully responsive (desktop, tablet, mobile)
- Tailwind CSS–based UI
- SEO-friendly (semantic HTML, proper heading structure, meaningful content)

---

### **1️⃣ `index.html` – Home Page**

Main homepage containing:

- Hero banner with premium tour highlight
- Top navigation bar with:
  - Desktop mega menu (hover dropdowns: Tour From Delhi / Agra / Mathura / Bus Packages)
  - Mobile accordion menu with hamburger toggle (built using Tailwind `peer` classes, no JavaScript for accordion logic)
- Intro sections for:
  - Popular Mathura–Vrindavan tours
  - Happy Guests section with image slider look & tour description
  - Blog highlights and Taxi Service info
- Multiple content blocks:
  - Holi Festival & Braj Yatra information sections
  - Forests of Braj & Mathura Vrindavan Packages overview
- Modern layout using cards, grids and responsive typography

---

### **2️⃣ `tour-packages.html` – Tours From Delhi**

General tour packages listing with starting point **from Delhi**:

- Detailed list of Mathura–Vrindavan tour plans:
  - 1 Day, 2 Days, 3 Days, 4 Days packages
  - 84 Kosh Yatra multi-day packages
  - Mixed tours including Agra, Haridwar, Bharatpur, Jaipur etc.
- Clean list + card-style layout using Tailwind
- CTA links to contact or enquire
- Designed to be easily extended with more packages

---

### **3️⃣ `tour-from-agra.html` – Tours From Agra**

Tour plan page for **travel starting from Agra**:

- Dropdown/mega menu items like:
  - Same Day Mathura Tour From Agra
  - Same Day Barsana Tour From Agra
  - Same Day Barsana & Vrindavan Tour From Agra
  - Overnight Mathura Tour From Agra
  - 3 Days Complete Brij Darshan Tour From Agra
- Well-structured section layout with:
  - Day-wise plan description
  - Inclusions & Exclusions
  - Special notes & terms
- Right-side booking form design (pure Tailwind)
- FAQ accordion style created using Tailwind classes only

---

### **4️⃣ `Tour-From-Mathura.html` – Tours From Mathura**

Tour plan page for **travel starting from Mathura**:

- Packages such as:
  - Mathura–Vrindavan 1 Day Tour
  - 2 Days Mathura–Barsana Tour
  - 3 Days Complete Brij Darshan Tour
  - 3 Night 4 Days Complete Mathura Tour
- Card + detail sections following the same premium layout
- Tailwind typography for clear day-wise itinerary
- Responsive booking form and side sections

---

### **5️⃣ `Bus-Tour-Packages.html` – Bus Tour Packages**

Dedicated page for **bus-based tour packages**:

- Packages like:
  - Mathura Vrindavan Tour by Bus
  - 2 Days Mathura Vrindavan Tour by Bus
  - 3 Days Complete Brij Darshan by Bus
- Premium modern cards with:
  - Tour title, duration, short description
  - Buttons (View Detail / Call Us)
- Hover image zoom animation using Tailwind utility classes
- Full responsiveness for small and large devices

---

### **6️⃣ `Online-Payment-Modes.html` – Payment Options**

Modern payment page showing all ways to pay:

- Left side: **Saving Account Details**:
  - Account holder name
  - Account number
  - IFSC code
  - Full bank address
  - Google Pay, PhonePe, PayPal, UPI ID
- Right side:
  - Recommended online methods card (GPay, PhonePe, PayPal, UPI)
  - Prominent CTA button: **“Confirm I’ve Made the Payment”**
- Extra cards (if added): other units / branches / help information
- Clean table-style layout built with Tailwind, fully responsive

---

### **7️⃣ `Quick-Enquiry.html` – Enquiry Form**

Beautifully designed enquiry form:

- Inputs for:
  - First Name, Last Name
  - Email address
  - Phone number
  - Travel date
  - Number of travellers (optional)
  - Message / requirements box
- Proper labels, placeholders, and focus states
- Tailwind form design with good spacing, rounded borders, and responsive grid
- Ready to be hooked to a backend or form-handler service

---

### **8️⃣ `payment-confirmation.html` – Confirm Payment Details**

Page opened when user clicks **“Confirm I’ve Made the Payment”**:

- Top header with:
  - “Back to Home” link
  - Page title “Confirm Your Payment”
  - Breadcrumb: Home / Payments / Confirmation
- Main form collects all payment details:
  - Full Name
  - Mobile Number
  - Payment Method (Google Pay, PhonePe, PayPal, UPI, Bank Transfer, etc.)
  - Transaction / UTR Number
  - Amount Paid & Payment Date
  - Optional payment screenshot upload (file input)
  - Additional note/message box for the accounts team
- Right side summary cards:
  - Recommended online methods with numbers & IDs
  - Bank account summary (HDFC account details)
  - Help card with WhatsApp / call support info
- On submit, form can redirect to `payment-success.html`

---

### **9️⃣ `payment-success.html` – Payment Submitted Success Page**

Thank-you / success screen after payment confirmation form:

- Big success icon & success heading:
  - “Payment Details Submitted Successfully!”
- Text explaining:
  - Payment will be verified within 1–4 working hours
  - Confirmation will be shared via WhatsApp & Email
- Support box with:
  - WhatsApp number
  - Phone call number
  - Email address
- CTA buttons:
  - **Back to Home** (`index.html`)
  - **View Booking Status** (`view-booking-status.html`)
- Minimal, focused layout meant for user reassurance and next steps

---

### **🔟 `view-booking-status.html` – View Booking Status**

Page for users to track their booking after payment:

- Top header:
  - Back to Home link
  - Page title “Check Booking Status”
  - Short description about entering Booking ID
- Main content:
  - Search card with Booking ID input + “Check Status” button
  - Example booking status result card (static demo, ready to be connected to backend):
    - Payment status (e.g., Payment Verified)
    - Booking ID
    - Customer Name
    - Tour Package name
    - Journey Date
    - Payment & confirmation status
  - Buttons:
    - Back to Home
    - Download Receipt (future integration)
- “Need Help?” section with support contact details

---

### **1️⃣1️⃣ Other Section Templates Inside Pages**

Within the main pages (especially `index.html` and tour pages), several reusable Tailwind-based sections are designed:

- **Holi Festival & Braj Yatra Sections**  
  Long-form content blocks with headings, paragraphs, and highlighted sub-titles describing:

  - Holi in Mathura / Vrindavan / Barsana / Nandgaon
  - Braj Chaurasi Kos Yatra
  - Forests of Braj, Rasleela places, and devotional narratives

- **Popular Tours Grid**  
  Responsive grid of tour cards with:

  - Hero images
  - Duration badges (e.g., “4 Days”)
  - Tour titles & car info
  - Buttons: View Detail / Call Us  
    Includes hover zoom animation on images.

- **Happy Guests Section**  
  Two-column layout:

  - Left: content about guest experiences and tour quality
  - Right: image carousel style (CSS-animated slides) showing happy guests

- **Blog & Taxi Service Section**

  - Two blog cards with images and “View More” buttons
  - Below: “Taxi Service in Mathura” heading and descriptive paragraphs about taxi services, benefits, and features

- **Advanced Navigation**
  - Desktop: sticky white navbar with logo, mega-menu style dropdowns on hover
  - Mobile: dark accordion navigation using Tailwind `peer` and `max-h` transitions with:
    - Hamburger / close icon toggle
    - Nested accordions for each tour group (Delhi / Agra / Mathura / Bus Tour Packages)

All these sections are built with semantic HTML and Tailwind classes for maximum clarity and reusability.

---

## 🛠️ Technologies Used

- **HTML5** – semantic structure, SEO-friendly tags
- **Tailwind CSS (CDN)** – utility-first styling for all layouts
- **Font Awesome / icon fonts** – for icons in nav, sections & call-to-action buttons
- **Responsive Web Design** – mobile-first approach for all pages
- **No JavaScript frameworks** – fast loading, easy to deploy on static hosting

---

## 🎯 Key Features

- ✅ Fully responsive across phones, tablets, and desktops
- ✅ Modern, premium UI using Tailwind utility classes
- ✅ Fast loading static pages (no heavy frameworks or build steps)
- ✅ Professional layout for tour packages, blogs, and taxi services
- ✅ Complete **payment flow**:
  - Online payment modes
  - Confirm payment details
  - Payment success acknowledgment
  - Booking status checking page
- ✅ Beautiful enquiry and contact forms
- ✅ Mega-menu navigation with mobile accordion version
- ✅ SEO-friendly structure (proper headings, readable content, clean URLs)
- ✅ Easy to extend with more pages or backend functionality later
