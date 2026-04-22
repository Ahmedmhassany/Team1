# Team Showcase Project

This project contains a premium web gallery and a high-fidelity poster for showcasing your team members.

## Files Included
- `index.html`: The main gallery page displaying all team members with their names and IDs.
- `style.css`: Modern styling for the gallery with glassmorphism and animations.
- `poster.html`: A professional poster design featuring a QR code.
- `poster_bg.png`: A high-resolution abstract background for the poster.
- `Images`: The original image files are used directly in the gallery.

## How to use
1. **Gallery**: Open `index.html` in any browser to view the team gallery.
2. **Poster**: Open `poster.html` to view the poster. It is designed at an A4 aspect ratio.
3. **Updating the Link**:
   - Once you host the gallery (e.g., on GitHub Pages or Netlify), you will get a public URL.
   - Open `poster.html` in a text editor.
   - Find the `<img>` tag for the QR code:
     ```html
     <img src="https://api.qrserver.com/v1/create-qr-code/?size=250x250&data=https://team-images-gallery.vercel.app" alt="QR Code">
     ```
   - Replace `https://team-images-gallery.vercel.app` with your actual public URL. The QR code will update automatically.

## Team Members Extracted
The following members were extracted from your image filenames:
- Dina Hamdy (ID: 225105349)
- Fatma Wahba (ID: 225129596)
- Habiba Nagy (ID: 224118836)
- Hesham Yasser (ID: 223100667)
- Kareem Eslam (ID: 223200121)
- Mai Nabih (ID: 224200262)
- Menna Abdelrazek (ID: 225113348)
- Mohamed (ID: 225129596)
- Shahd Hassany (ID: 225122807)
- Yousef Azzam (ID: 224127280)
