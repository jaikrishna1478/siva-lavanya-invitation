# Siva Krishna & Lavanya — Wedding Invitation

This is a static, frontend-only invitation page. It uses the supplied HTML, including its responsive layout, English/Telugu switch, countdown, reveal animation, gallery, and venue map.

## Firebase Hosting

1. Install the Firebase CLI: `npm install -g firebase-tools`
2. Sign in: `firebase login`
3. From this folder, select your Firebase project: `firebase use --add`
4. Deploy the site: `firebase deploy --only hosting`

The Hosting configuration serves `index.html` from this folder. No backend or Firebase client SDK is used.

## Invitation assets

The page loads its images and downloadable invitation from `public/`:

- `public/IMG_7934.PNG`
- `public/IMG_7931.JPG.jpeg`
- `public/groom.jpeg`
- `public/bride.jpeg`
- `public/engement2.jpg`
- `public/engement.jpg`
- `public/invitation-pdf.pdf`
