PRISHTEE'S BIRTHDAY WEBSITE — QUICK START (ANDROID)

WHAT'S INCLUDED
- index.html: the complete responsive website
- assets/: put your photos and song in this folder

PREVIEW ON YOUR PHONE
1. Extract this ZIP using your Android file manager.
2. Open index.html in a code editor that has an HTML preview, or upload the files to a static hosting service to preview it as a website.
3. The page works on phone and desktop; no app installation is required for visitors.

PERSONALISE THE PHOTO GALLERY
1. Add four image files to assets and name them photo1.jpg, photo2.jpg, photo3.jpg, photo4.jpg.
2. In index.html, find each photo card's placeholder block.
3. Replace the placeholder content inside each .photo-frame with:
   <img src="assets/photo1.jpg" alt="Prishtee photo 1">
   Change the filename and alt text for each card.
4. Change the captions beneath each card to whatever you like.
Tip: JPG or PNG images work best. Only use photos you have permission to share with her.

ADD THE SONG
1. Add an MP3 you have permission to share to assets/favourite-song.mp3.
2. Keep the exact filename, or edit the source URL in index.html to match your file.
3. Browsers require a tap before audio plays; the visitor can use the audio controls.
Note: a song saved only on your phone will not be available to her. The MP3 must be included with the deployed website, and you should only share music you have rights/permission to distribute. If you don't have permission to upload the song, use a link to an official music service instead.

CHANGE THE LETTER
Open index.html in a text editor and search for "Dear Prishtee". Edit the paragraphs inside <article class="letter-card">, keeping the surrounding HTML tags intact. It is written as a friendship message.

PUBLISH IT (NO SERVER TO MANAGE)
Use a static hosting service such as GitHub Pages or Netlify. Create a new site/project and upload/publish index.html plus the entire assets folder. Keep the folder structure exactly as it is. After publishing, open the generated HTTPS link on your phone and test the envelope, gallery, audio, and gift box.
Important: a single index.html file alone is not enough if you want your own photos and song to load; upload the assets folder too.

TROUBLESHOOTING
- Photos missing: confirm filenames and capitalization exactly match.
- Song missing: confirm assets/favourite-song.mp3 exists and is included in the deployed files.
- Envelope or gift not opening: make sure you uploaded the full index.html file without editing its JavaScript.
- Want to change the date: search for "26 · 10 · 2026" in index.html.
