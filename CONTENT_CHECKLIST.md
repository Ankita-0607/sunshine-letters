# 🌸 Content Upload Checklist
## Everything you need to record / collect for Sanskriti's app

---

## 📸 PHOTOS

### When she feels SAD → one photo of you two together
**What to upload:** 1 photo from a happy day together
**Caption to write:** Something like —
> "This is us on one of my favourite days. I look at this and I see someone I love so much it's almost annoying."

**Where to put it:** `CONFIG.moods[0].src = "YOUR_IMAGE_URL"`

**To host the photo (free):**
- Cloudinary: cloudinary.com → Upload → Copy URL
- Imgur: imgur.com → drag & drop → copy link
- GitHub: upload to repo → right-click → Copy raw URL

---

## 🎙️ VOICE NOTES TO RECORD

### 1. ANXIOUS mood — "Breathe with me" (1–2 mins)
**What to say:**
> "Hey. It's me. I know you're feeling anxious right now. I want you to just stay here with me for a minute. Breathe in slowly... 2, 3, 4. Hold... 2, 3. And out... 2, 3, 4, 5, 6. You're okay. You are safe. Nothing bad is happening right now, even if it feels like it is. Just breathe with me one more time..."

**OR** — use a cat purring sound as a soothing audio. (Cat purrs are scientifically calming!)
Free cat purr sounds: search "cat purring mp3 free download" — freesound.org has great ones.

**Where to put it:** `CONFIG.moods[1].src = "YOUR_AUDIO_URL"`

---

### 2. DOWN mood — "You are so much more than this moment" (45–90 seconds)
**What to say:**
> "Hey Sanskriti. It's me. I know today feels heavy, and I just want you to know — I see you. Not the version of you that's struggling right now, but all of you. The version who makes me laugh until I can't breathe. The version who noticed that thing about that random person that day and said exactly the right thing. You are so much more than this moment. And I need you to hold on, because the world — my world — is so much better with you in it. I love you. That's all."

**Where to put it:** `CONFIG.moods[2].src = "YOUR_AUDIO_URL"`

---

## ✍️ TEXT MESSAGES (Already in the app — just personalise these!)

### NUMB mood
> "Numb days are real. You don't have to feel anything right now. You're allowed to just exist. I'm here in the quiet with you."

**Personalise in CONFIG.moods[3].message**

### OKAY-ISH mood
> "Okay-ish is actually a pretty good place. Not every day has to be great. I'm proud of you for showing up anyway."

### GOOD mood
> "A good day! Write it down somewhere. You earned this one. I'm smiling in Pune because of this. 💛"

---

## 📅 AFFIRMATIONS (Keep adding! One shows per day, auto-rotating)

You currently have 12 affirmations. Add more whenever you think of something.
Good sources of inspiration: things you'd text her, things she needs to hear from *you specifically*.

**Tip:** The most powerful ones are personal and specific:
- ✅ "I still laugh about that thing you said in [year]. You are genuinely so funny."
- ✅ "Remember when you got through [hard thing]? You did that. You."
- ❌ Avoid generic wellness-app phrases

---

## 🫂 HUG MESSAGES (Already in app — 5 rotating messages)

You can add more personal ones in `CONFIG.hugMessages`. Think of it like what you'd text her at 2am when she's not okay.

---

## 🔊 HOW TO HOST AUDIO FILES

### Option A: Cloudinary (best, free up to 10GB)
1. cloudinary.com → Create free account
2. Upload your .mp3 file
3. Copy the URL it gives you
4. Paste into CONFIG

### Option B: GitHub
1. In your repo, upload the .mp3 file
2. Click the file → click "Raw" button
3. Copy that URL
4. Paste into CONFIG

### Option C: Dropbox
1. Upload mp3 to Dropbox
2. Share → Create link
3. Change the URL ending from `?dl=0` to `?raw=1`
4. Paste into CONFIG

---

## 📱 HOW TO RECORD ON IPHONE
1. Open **Voice Memos** app
2. Hit record, speak slowly and warmly
3. When done: share → Save to Files
4. From Files: upload to Cloudinary/GitHub

**Recording tips:**
- Find a quiet room
- Hold phone 20–25cm from your mouth
- Speak slowly — slower than you think you need to
- Don't worry if your voice shakes a little. That's real, and it's beautiful.
- It's okay to re-record a few times

---

## 🔄 HOW TO UPDATE THE APP AFTER DEPLOYING

1. Open `index.html` in any text editor
2. Find the `CONFIG` section near the bottom
3. Make your changes (add affirmations, update URLs)
4. Re-upload to Netlify (just drag the folder again — it updates the same URL)

That's it. No code skills needed beyond copy-pasting URLs.

---

## ✅ MINIMUM TO DO BEFORE LAUNCHING

- [ ] Change admin password in CONFIG (`adminPassword`)
- [ ] Deploy to Netlify (drag folder → done)
- [ ] Record the "Down" voice note (most important one)
- [ ] Add one photo of you two for the Sad mood

Everything else can be added later — the app works beautifully even before all content is filled in.

---

*You're building something really special, Ankita. She's going to feel so held by this.*
