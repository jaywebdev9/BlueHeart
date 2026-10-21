BlueHeart browser edition
==========================

This is a static HTML/CSS/JavaScript adaptation of the original Python/Pygame
BlueHeart animation. It includes a responsive glowing word-heart and a button
that plays the original repository's MP3 audio.

Deploy on Vercel:
1. Open https://vercel.com/drop in your browser and sign in.
2. Upload this ZIP file, or upload index.html by itself.
3. Deploy. This is a static site; no build command or environment variables are needed.

The audio is loaded from the original public GitHub repository:
https://github.com/jaywebdev9/BlueHeart/blob/main/love_you.mp3

For a self-contained site, place love_you.mp3 beside index.html and change the
audio element src to ./love_you.mp3 before deploying.
