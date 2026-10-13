A LITTLE SOMETHING FOR YOU 💗
==============================

CONTENTS
--------
- index.html: complete romantic surprise website
- README.txt: these instructions
- music/: folder for your three MP3 files (add the files yourself)

ADD YOUR MUSIC
--------------
1. Extract the ZIP.
2. Open the extracted folder.
3. Open the included "music" folder.
4. Copy your three MP3 files into that folder.
5. Rename the files to these exact names:
   all-of-me.mp3
   perfect.mp3
   ordinary.mp3

The playlist is configured as:
- All of Me by John Legend -> music/all-of-me.mp3
- Perfect by Ed Sheeran -> music/perfect.mp3
- Ordinary by Alex Warren -> music/ordinary.mp3

Make sure Windows is showing file extensions so you do not accidentally
rename a file to all-of-me.mp3.mp3. In File Explorer, choose View > Show >
File name extensions (wording can vary by Windows version).

ADD HER PHOTO
-------------
Put her picture beside index.html, not inside the music folder. Name it:
her-photo.jpg

RUN LOCALLY
-----------
You can double-click index.html to preview the page. For more reliable audio
file loading, run a local server:
1. Open the folder containing index.html in File Explorer.
2. Click the address bar, type cmd, and press Enter.
3. Run: py -m http.server 8000
4. Open Chrome at http://localhost:8000
5. Enter the secret code 1919, open A Tiny Playlist, select a song, and press
   play. Press Ctrl+C in the command window to stop the server.

SECRET CODE
-----------
The example code is 1919. To change it, edit this line in index.html:
const SECRET_CODE = "1919";

This is a playful gate, not real security, because the code is in the page source.

PUBLISH ONLINE
--------------
Upload/deploy index.html and the entire music folder together to a static host
such as Netlify or GitHub Pages. Upload her-photo.jpg beside index.html too.
Do not upload only index.html, or the music and photo will not be available.
After publishing, open the HTTPS link on a phone to test everything.

PRIVACY AND RIGHTS
------------------
Anyone with access to the published link may be able to view the photo and
play the included music files. Only use photos you have permission to share,
and audio files you are permitted to distribute. A public website makes its
uploaded files accessible to visitors.

NOTES
-----
- Built with HTML, CSS, and vanilla JavaScript. No frameworks or packages.
- Responsive layout and reduced-motion preference support are included.
- The music player reads local MP3 files and does not use YouTube.
- If a song does not play, confirm the filename and folder path exactly.
