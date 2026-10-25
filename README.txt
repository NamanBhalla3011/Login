OUR LITTLE STORY — BIRTHDAY WEBSITE
====================================

Open index.html in a browser to preview the website. It works as a standalone page.

PERSONALIZE IT
1. Replace the photo placeholder in the hero:
   - Open index.html in a text editor.
   - Search for: "Your favourite photo goes here"
   - The pastel placeholder is intentionally built into the page. Easiest option: replace the whole <div class="photoPlaceholder"> ... </div> block with:
     <img src="photos/us.jpg" alt="Our favourite photo" style="width:100%;height:300px;object-fit:cover;border-radius:3px">
   - Create a folder called "photos" beside index.html and put your image inside as us.jpg.
2. Change "Happy Birthday, Naman!" if Naman is your name rather than hers. Search for that exact phrase in index.html and replace it with her name/nickname.
3. Edit the timeline and letter text directly in index.html to add specific memories, dates, and inside jokes.
4. You can add more pictures by duplicating the photo-frame HTML structure and changing the image path.

SHARE IT AS A LINK
Option A — Netlify Drop (easy):
1. Put index.html and your photos folder into one folder.
2. Open https://app.netlify.com/drop in your browser and sign in if prompted.
3. Drag the whole website folder onto the page. Netlify will provide a public URL.
4. Test the URL on your phone before sending it. Anyone with the URL may be able to view it, so don't include anything too private.

Option B — GitHub Pages:
1. Create a new GitHub repository.
2. Upload index.html and the photos folder.
3. In repository Settings → Pages, enable deployment from the main branch.
4. Wait for the published URL and test it on your phone.

PRIVACY NOTE
This is a static website, not password-protected. The surprise modal is playful, not real security. Use a hard-to-guess link and avoid private information you would not want someone else to see.

The page uses Google Fonts when internet access is available; it falls back to system fonts offline.

NEW INTERACTIVE EXPERIENCES INCLUDED
- Secret entrance: answer 'exam centre' (or 'exam center') to unlock.
- Our love story with playful captions and timeline.
- The Jind Meriye Awards.
- Clickable love notes.
- Three-step birthday treasure hunt.
- Final birthday surprise reveal.

The birthday heading currently says 'Jind Meriye'. If you'd prefer 'Happy Birthday, Naman' or another name, search that heading in index.html and change it.
