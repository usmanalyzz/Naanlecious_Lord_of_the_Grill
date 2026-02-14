# Naanlecious & Lord of the Grill — Digital Menu

A mobile-first, QR-code-ready menu page with 3D effects. Place the URL on QR codes at each table so customers can scan and browse your menu.

## Features
- **3D card effects** — Cards tilt and lift on hover/touch
- **Two brands in one** — Naanlecious & Lord of the Grill sections
- **Mobile optimized** — Perfect for phone screens when scanning QR
- **Easy to update** — Edit `index.html` to change prices or items
- **No server required** — Works as a static file

## How to Use

1. **Preview locally** — Open `index.html` in your browser
2. **Deploy** — Upload the folder to any web host (Netlify, Vercel, GitHub Pages, or your restaurant website)
3. **QR codes** — Generate QR codes pointing to your live URL (e.g. `https://yoursite.com/menu` or `https://yoursite.com/`)
4. **Print & place** — Put QR codes on table stands or menus

## Add Menu Images

1. Add photos to the `images/` folder
2. Use the filenames listed in `images/IMAGES_GUIDE.md`
3. Recommended: 400×400px or larger, JPG or PNG

## Customize the Menu

Edit `index.html` and look for:
- **Menu items** — Inside each `<section id="...">`
- **Prices** — Update the `<span class="item-price">Rs. XXX</span>` values
- **Descriptions** — Edit the `<p class="item-desc">` text
- **Add items** — Copy a `<div class="menu-item">...</div>` block and paste where needed. Include an `<img src="images/your-image.jpg" alt="Item Name">` inside the `item-image` div.

## Contact
Liberty Market, Opposite Jinnah Stadium, Gujranwala  
📞 055 3821416
