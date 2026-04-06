WILLOUGHBY LAW FIRM — PHOTO REPLACEMENT GUIDE
==============================================

Replace these background-image URLs in each index.html to swap in your photos.

SEARCH FOR THESE STRINGS in any text editor (VS Code, Notepad++, etc.):

HERO BACKGROUND:
  photo-1589829545856-d10d557cf95f  → Replace with: your MidJourney Hero A/B/C output
  photo-1521791136064-7986c2920216  → Replace with: your MidJourney Hero C output

ATTORNEY PORTRAIT:
  photo-1556157382-97eda2d62296    → Replace with: Josh's real headshot or MidJourney Portrait A/B

HOW TO REPLACE:
  Option 1 (easiest): Upload your photo to your web host, then replace the full
  Unsplash URL with your image path, e.g.:
    url('../images/josh-willoughby.jpg')

  Option 2: Use an image CDN like Cloudinary or Imgix and paste in the CDN URL.

PHOTO FILE PLACEMENT:
  Put your images in /images/ next to each index.html
  Then reference them as: url('../images/filename.jpg')

See photo-prompts.html for the full MidJourney prompt list.
