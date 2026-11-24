# વ્હાલમ આવો ને (Vhaalam Aavo Ne) • Digital Proposal Gift Experience 💍

A romantic, minimalist, and dignified mobile-first single-file web application (`index.html`) created as a surprise gift experience for an arranged marriage proposal ("Jal / Chandlo" ceremony).

---

## 🌟 Features Included

1. **Pure-Black OLED Luxury Theme:**
   - Deep `#000000` background with soft warm gold accents (`#E5C158`), frosted glass cards (`#111113`), and subtle ambient golden stardust particles drifting at 60fps.
   - Clean typography using Google Fonts (`Inter`, `Poppins`, `Noto Sans Gujarati`) with crisp Gujarati character rendering.

2. **Time-Aware Gujarati Greeting:**
   - Automatically detects current time and displays:
     - 🌅 સવાર: `શુભ સવાર`
     - ☀️ બપોર: `શુભ બપોર`
     - 🌇 સાંજ: `શુભ સાંજ`
     - 🌙 રાત્રિ: `શુભ રાત્રિ`

3. **Centerpiece Breathing Play Button:**
   - Circular tactile golden play button with concentric breathing rings and earbud prompt:
     `🎧 ઈયરબડ્સ લગાવીને નીચેનું બટન દબાવો...`

4. **Pre-Music Emotional Reveal (0.0s – 5.2s):**
   - **0.0s – 2.5s:** `"આપણા આ નવા અને સુંદર સફરની શરૂઆત..."`
   - **2.5s – 5.0s:** `"મારા તરફથી તમારા માટે એક નાનકડી ભેટ."`
   - **5.2s:** Smoothly transitions into the music player and starts playing `./vhaalam-aavo-ne.mp3`.
   - *Note on mobile browsers:* User tap on the play button immediately unlocks audio permissions so iOS Safari and Android Chrome play seamlessly without autoplay blocks.

5. **LRC-Style Synced Gujarati Lyrics Engine:**
   - Complete 45-line Gujarati lyrics with all STT/grammatical mistakes corrected (e.g. `છોડી ોડીને` → `છોડીને`, `મેલનની` → `મિલનની`, `વાત/વાર` → `વાટ`, `નિ ભાવો` → `નિભાવો`).
   - Smooth auto-scrolling to keep the current active line vertically centered.
   - Active line expands slightly (`scale(1.08)`), glows in warm gold & white, while inactive lines softly dim with subtle blur for depth.
   - Iconic lines have `highlight: true` with shimmering stardust ` ✨ ` and a warm golden glow.
   - **Tap to Seek:** She can tap directly on any lyric line to jump to that moment in the song.

6. **Full Audio Controls:**
   - Interactive touch/drag scrubber bar, current and total time display (`4:53`), rewind 10s, play/pause toggle, and forward 10s.

7. **Post-Song Surprise Card (onended event):**
   - Automatically reveals when the song ends:
     - Heartfelt message:
       `"આશા છે કે તમને 'વ્હાલમ આવો ને' ગીત અને આ નાનકડું સરપ્રાઈઝ ગમ્યું હશે. હવે આપણા આવનારા દરેક સૂર આ ગીત જેવા જ મીઠા અને સુમધુર રહેશે."`
     - **WhatsApp Button:** Sends a pre-filled reply:
       `"ગીત અને આ સરપ્રાઈઝ ખૂબ જ સરસ હતું! 😊"`
     - **Replay Button:** Restarts the song and returns to the player.

8. **Gift Box Easter Egg:**
   - Discreetly visible at the bottom:
     `"🧸 તમારા ગિફ્ટ બોક્સમાં રહેલા પેલા નાનકડા મિત્ર તરફથી પણ હેલો!"`

---

## 🚀 How to Deploy on GitHub Pages (Free & Easy)

1. Create a new repository on [GitHub](https://github.com) (e.g. `chandlo-gift` or `vhaalam`).
2. Upload these files to the repository:
   - `index.html`
   - `vhaalam-aavo-ne.mp3`
3. Go to **Settings** > **Pages** in your repository.
4. Under **Branch**, select `main` (or `master`) and folder `/ (root)`, then click **Save**.
5. Your website will be live in ~60 seconds at:
   `https://<your-username>.github.io/<repo-name>/`

---

## 📱 How to Generate the QR Code

Once your GitHub Pages link is live:
1. Go to any free, clean QR code generator such as [qr-code-generator.com](https://www.qr-code-generator.com/) or [me-qr.com](https://me-qr.com/).
2. Paste your GitHub Pages URL: `https://<your-username>.github.io/<repo-name>/`.
3. Choose a sleek Black / Gold color or print it on a small luxury card.
4. Place the QR card inside her gift box alongside the small teddy bear/gift! 🧸✨

---

## ⏱️ How to Fine-Tune Lyric Timestamps

If you ever want to adjust the timing of any line:
1. Open [index.html](file:///c:/Users/QP1K/Desktop/M2/PROJECT%20EB/index.html) in any text editor.
2. Find `const LYRICS_DATA = [...]` near line 450.
3. Simply adjust the `time: seconds` number for that line.
