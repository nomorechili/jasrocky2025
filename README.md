# jasrock2025 — Wedding Invite + FAQ

This project contains multiple versions of our **single-page wedding invitation and FAQ website**, designed to be mobile-friendly, easy to share, and joyful in tone. It includes details about our wedding at *The French Farmhouse*, schedule, food, dress code, gifts, and FAQs.

We’re storing versions here to experiment with layouts and wording. Each version is a complete `index.html` file inside `/versions/`.

---

## ✨ Features
- **Sticky header navigation** — quick links to all sections (When & Where, Schedule, Food & Drinks, Dress Code, Gifts, FAQ, Contact).
- **Clean card layout** — modern design with soft colors (sage, dusty blue, champagne, ivory) and rounded corners.
- **Responsive** — works beautifully on phones, tablets, and desktops.
- **FAQ accordion** — collapsible Q&A (arrival time, venue indoors/outdoors, accommodations, plus-ones).
- **Gift QR code placeholder** — swap with our actual registry QR image.
- **Accessible** — semantic HTML with clear headings and labels.
- **Multiple versions** — experiment with simple, cocktail attire, or expanded FAQ versions.

---

## 📂 File Structure
jasrock2025/
├─ versions/
│   ├─ v1-simple/
│   │   └─ index.html
│   ├─ v2-cocktail/
│   │   └─ index.html
│   ├─ v3-expanded/
│   │   └─ index.html
├─ assets/
│   ├─ hero.jpg          # 3:2 hero image
│   └─ registry-qr.png   # QR code for gifts/registry
└─ README.md

---

## 🚀 How to Use
1. Clone or download this repo.
2. Pick a version folder (`v1-simple`, `v2-cocktail`, or `v3-expanded`).
3. Open `index.html` in your browser (double-click or drag into Chrome/Safari).
4. Update content as needed:
   - Venue: The French Farmhouse (verify TX vs VA address).
   - Food: Buffet dinner with vegetarian & allergy-friendly options.
   - Dress code: Cocktail Attire (no sneakers/flip-flops).
   - Schedule: October 3, 2025 · 6–9 PM (arrive 5:45 PM).
   - Gifts: Replace QR placeholder with actual QR image + link.
   - Contact: Update phone/email.

---

## 🌐 Hosting Options
We’re **not currently hosting**, just storing versions here.  
If we decide to host, these are options:

- **Netlify Drop**: Drag & drop `index.html` to get a `.netlify.app` URL.
- **Vercel**: Import the project and get a `.vercel.app` URL.
- **GitHub Pages**: Enable Pages in repo settings (not enabled by default here).

---

## 🎨 Customization
- **Colors & Styling**: Edit CSS variables at the top of `<style>`.
- **Hero Image**: Replace `assets/hero.jpg` with our wedding photo.
- **Registry QR**: Replace `assets/registry-qr.png` with our real code.
- **Schedule**: Edit timeline under `#schedule`.
- **FAQs**: Add or remove `<details>` blocks under `#faq`.

---

## 🛠️ Next Steps
- Confirm the final venue details (TX vs VA address, phone number).
- Add our names to the hero and header branding.
- Replace placeholder images (hero + QR).
- Verify dress code wording.
- Optionally connect a custom domain if we host.

---

## 📜 License
This project is free to use, customize, and share for our wedding and personal events.