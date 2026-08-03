# Three Years of Us - Anniversary Website

## ✅ What's Ready:
✅ Beautiful dark-themed website (red & black, easy on the eyes)
✅ All poem sections and lyrics
✅ 50+ photo gallery (vu2nd/ folder)
✅ 2 special moment videos
✅ Interactive music player with controls
✅ Voice recording playback (poem-voice.mp3)
✅ Responsive design for mobile & desktop
✅ Smooth animations & scroll effects

## 🎵 Music Integration:

### Your Voice Recording (poem-voice.mp3) ✅
- Already added! It plays during the poem section
- Shows in audio player with 🎙️ icon
- Visitors can play/pause and control volume

### Background Ambiance Music (NEW!)
The website now has an interactive music player in the bottom-left corner that plays continuously throughout the experience.

**To add background music:**

1. Download the 8 songs from these YouTube links:
   - https://youtu.be/_MVWrTgoJIk
   - https://youtu.be/CGj8uWROTFo
   - https://youtu.be/iZ9dkLr5Kv0
   - https://youtu.be/9nPMihiD1Rw
   - https://youtu.be/syFZfO_wfMQ
   - https://youtu.be/29RTLrPDJzc
   - https://youtu.be/kV6cXrevo8s
   - https://youtu.be/Vnrbdn7NLvM

2. Convert to MP3 format (use YouTube-MP3 converters or ffmpeg)

3. Merge all 8 songs into one continuous playlist using:
   - Audacity (free): Open each song, place side-by-side on tracks, export as MP3
   - FFmpeg: `ffmpeg -i "concat:song1.mp3|song2.mp3|..." output.mp3`
   - Online tools: Combine audio files online

4. Save the final merged file as `background-music.mp3`

5. Place in `/home/user/project-nine/` (same folder as index.html)

6. Refresh the website - you'll see the music player active with ▶ Play button

## 🖼️ Photo Gallery:
- Automatically loads all 50+ PNG images from `vu2nd/` folder
- Displays 1.png through 51.png
- Touch-friendly hover effects on desktop
- Responsive grid that works on all screen sizes

## 📹 Videos:
- `anniversary-video.mp4` - First special moment
- `anniversary-video2.mp4` - Second special moment
- Both display in responsive video players
- Native browser controls (play, pause, fullscreen)

## 📱 Mobile Compatibility:
- Fully responsive design
- Touch-friendly buttons and controls
- Optimized font sizes for small screens
- Smooth scrolling between sections
- Music player adapts to mobile layout

## Website Features:
- 💜❤️ Dark romance theme (minimal glows for light sensitivity)
- Smooth fade-in animations as you scroll
- Interactive gallery with zoom effects
- Auto-playing voice during poem section
- Fixed music player (always accessible)
- Rose 🌹 dividers between sections
- Purple & red accent colors
- Full mobile support

## To View:
1. Open `index.html` in a web browser on desktop or mobile
2. For local testing: `python3 -m http.server 8000`
3. Visit: http://localhost:8000/index.html (desktop)
4. For mobile: Use your computer's IP address: http://YOUR_IP:8000

## Files Included:
- `index.html` - Main website
- `poem-voice.mp3` - Your voice recording ✅
- `poem-image.jpg` - Beautiful couple portrait ✅
- `anniversary-video.mp4` & `anniversary-video2.mp4` - Special moments ✅
- `vu2nd/` folder - 50+ IMVU couple photos ✅
- `background-music.mp3` - Add once downloaded from YouTube links

---
Made with love for your 3-year anniversary 💜❤️🌹

**Tips:**
- The website is optimized for Mr. V's light sensitivity (minimal glow effects)
- Music player can be minimized/toggled with the button
- All content can be updated by replacing files with the same names
- Share the link with your boyfriend on his birthday!
