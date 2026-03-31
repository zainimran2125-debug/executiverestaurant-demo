# Final Prompt — Spiritual, Powerful, and Detailed (Urdu + English Mix)

You are a **Senior Mobile App Architect + UX Strategist + AI Product Engineer**.
Design a **fully personal-use Islamic + Self-Growth mobile app** that feels **spiritual, elegant, calming, and premium** ("fire + spiritual + beautiful" vibe), with a strong focus on privacy, daily discipline, and practical progress.

The app must be **mobile-first**, **fully responsive**, and support **Dark Mode (primary)** with a green-accent Islamic aesthetic.

## Core Product Vision
Build an advanced personal app that combines:
1. Namaz tracking
2. Quran learning and recitation
3. Personal growth and bad-habit avoidance (Fazzol avoidance)
4. AI Islamic assistant
5. In-app YouTube learning

The app should help the user become spiritually consistent and personally disciplined.

---

## Absolute Product Rules (Must-Have)

1. **Privacy-first architecture**:
   - User data is private and local-first.
   - No public profile discovery.
   - No third-party progress sharing by default.
   - No external analytics that expose personal worship habits.

2. **Daily auto-reset behavior (critical)**:
   - App includes a strict "Daily Reset" mode where personal daily logs auto-clear at the next day boundary.
   - User can optionally keep historical summaries (without exposing private raw logs).
   - Explain both options clearly in settings:
     - Mode A: Full reset (all daily logs deleted next day)
     - Mode B: Private archive (keeps historical progress locally)

3. **Offline-first where possible**:
   - Core tracking should work without internet.
   - Sync only optional and explicitly user-controlled.

4. **Security controls**:
   - App lock (PIN/biometric)
   - Encrypted local storage
   - Manual "Delete all data now" button

5. **Polished UX**:
   - Smooth animations, minimal clutter, clear typography.
   - Calm dark background + green highlights + subtle gold/emerald spiritual accents.

---

## Information Architecture (Global Navigation)

Provide a **Side Menu + Bottom Navigation** hybrid:
- Dashboard
- Namaz
- Quran
- Growth
- YouTube
- AI Assistant
- Account
- Settings

### Side Menu Must Include
- Account profile (personal-use only)
- Dark mode toggle
- Privacy controls
- Daily reset toggle
- Notifications settings
- Data export/delete
- About + support

---

## SECTION 1 — Personal Namaz Tracker Module

### 1.1 Dashboard (Namaz Focused)
- Show all 5 prayers: **Fajr, Dhuhr, Asr, Maghrib, Isha**
- Status badges per prayer:
  - Pending
  - Completed (on-time)
  - Late
  - Missed
- Inline tracker for **Sunnah + Nafl**
- Daily progress bar (0%–100%)
- Top Urdu Hadith/quote card (dynamic)
- Quick actions:
  - Mark as Done
  - Add Sunnah/Nafl
  - View Details
- Color coding:
  - Green ✅ = On-time
  - Yellow ⚠️ = Late
  - Red ❌ = Missed
- Smart summary example:
  - "Aaj 3/5 on-time, 1 late, 1 missed. Extra Nafl: 2"

### 1.2 Prayer Detail Screen
- Arabic prayer name + Urdu translation
- Prayer time via location/GPS
- Alarm + reminder controls
- Actual completion time input (auto/manual)
- Minutes early/late calculation
- Sunnah/Nafl notes box
- AI recommendation engine:
  - Suggest extra Nafl based on consistency
  - Suggest earlier alarm if repeated lateness
- Urdu guidance:
  - Step-by-step prayer method
  - Common mistakes to avoid
- Optional visual aid/illustrations
- Personalized motivation card:
  - "Aaj aap ne 2 extra rakat parhi — MashaAllah"
- Missing Sunnah highlight:
  - e.g., "Asr se pehle 4 Sunnah add karein"

### 1.3 Weekly/Monthly Analytics
- On-time streak tracking
- Consistency formula:
  - (performed ÷ scheduled) × 100
- Calendar heatmap (G/Y/R)
- Sunnah/Nafl trend graph
- AI insight examples:
  - "Aap mostly Isha late karte hain; 10 min pehle reminder set karein"
- Optional progress card export/share image

### 1.4 Reminders & Notifications
- GPS-based prayer notifications
- Early reminder customization
- Missed prayer motivational alert
- End-of-day summary notification in Urdu
- Optional Urdu voice reminder
- Focus Mode reminder nudges

### 1.5 AI Smart Suggestions
- Predict lateness risk and suggest routines
- Suggest weekly targets (e.g., Fajr on-time 7/7)
- Daily dua + motivational line in Urdu

### 1.6 Prayer Journal
- Per-prayer note entry
- Day-wise reflection timeline
- AI-generated "Lessons learned" summary

### 1.7 Strict Focus Mode
- Restrict app to Islamic modules only during prayer windows
- Optional social app blocking hooks (OS-permission dependent)
- Motivational lock overlay if user skips prayer action

---

## SECTION 2 — Personal Quran Module

### 2.1 Quran Dashboard
- Full Quran Arabic text + Urdu translation
- Ayah-level Urdu tafsir
- Custom daily reading target
- Bookmark / highlight / notes
- Search (Arabic + Urdu keywords)
- 3 daily motivational Quranic lines in Urdu
- Resume from last ayah

### 2.2 Audio & Recitation
- Full audio with multiple Qaris
- Per-ayah repeat + playback speed control
- Background playback when minimized/locked
- Floating mini-player
- Auto-resume from last position
- Manual pause/stop always available
- Graceful handling if other media starts

### 2.3 YouTube Learning Integration (Quran)
- Embedded curated playlists (Quran, tafsir, lectures)
- PiP support where platform allows
- Floating playback UX
- Daily 1–3 recommended videos
- Continue audio in background when possible

### 2.4 Daily Ayahs & Quotes
- 3 fresh daily entries (Ayah/quote)
- Urdu translation + explanation
- Save to favorites
- Daily reminder notification

### 2.5 Interactive Learning
- Notes per ayah/surah
- Arabic word highlights
- Word-by-word popup translation
- Mark memorized ayahs
- AI explanation in simple Urdu

### 2.6 Quran Analytics
- Reading completion %
- Memorization progress count
- Weekly/monthly charts
- Personalized AI plan suggestions

### 2.7 Advanced Add-ons
- Offline audio caching
- Daily learning plan generator
- Share ayah card (optional)

---

## SECTION 3 — Personal Growth & Fazzol Avoidance Module

### 3.1 Growth Dashboard
- Negative habits to avoid list
- Positive habits/tasks list
- Combined daily progress bar
- Quick actions: done/avoided/add/remove
- Color states: Red ❌, Green ✅, Yellow ⚠️

### 3.2 Task Detail
- Task title + description
- Category: Positive / Negative
- Daily target count
- Notes field
- Recurrence rules
- Motivation message
- AI improvement suggestions
- Reminder toggle

### 3.3 Analytics
- Day/week/month charts
- Streak tracking
- Achievement badges
- AI insights for behavior patterns

### 3.4 Task Management
- Create/edit/delete custom habits
- Priority flags (High/Medium/Low)
- Daily check-in workflow
- AI-generated new healthy habit suggestions

### 3.5 Smart Alerts
- Reminders for avoiding negative habits
- Daily positive push notifications
- Weekly summary report
- Optional Fazzol alert if distracting app usage detected (permission-based)

### 3.6 Cross-Module Synergy
- Link Namaz discipline + Quran reading + Growth tasks
- Unified motivation engine across all modules

---

## SECTION 4 — Unified Dashboard + Account

### Dashboard Must Show
- Namaz today summary
- Quran target progress
- Growth completion score
- Motivational Hadith/Ayah/quote top banner
- One-tap quick actions to all modules

### Account & Settings
- Personal profile
- Theme controls (dark/light, default dark)
- Language toggle (Urdu/English)
- Privacy and reset settings
- Notification controls
- Data backup/restore options (optional)

---

## SECTION 5 — AI Islamic Assistant (In-App)

Build an in-app assistant that can:
- Answer Islamic practice questions politely (with disclaimer: not a mufti)
- Help with prayer consistency plans
- Explain ayahs in simple Urdu
- Suggest practical self-growth actions
- Provide daily motivation and duas
- Be accessible from Dashboard + Side Menu + floating quick button

### AI Safety Layer
- Respectful Islamic tone
- Uncertain fiqh answers should encourage consulting trusted scholar
- No harsh language, no judgmental wording

---

## SECTION 6 — YouTube Module

- In-app YouTube viewer for curated Islamic/personal growth content
- Categories: Quran recitation, tafsir, lectures, mindset/self-growth
- Tap-to-play in app
- Mini-player + PiP where available
- Daily recommended videos
- Optional offline metadata cache (not violating platform terms)

---

## SECTION 7 — UI/UX Design Language

Design style requirements:
- Spiritual, premium, calming, focused
- Dark mode + green accents as core identity
- Large readable Arabic rendering and clean Urdu typography
- Minimal controls, uncluttered cards
- Smooth micro-animations for completion/streak milestones
- Mobile-first responsiveness across small and large screens

---

## SECTION 8 — Data & Tech Requirements

### Data Policies
- Personal-use only
- Local encrypted storage first
- Daily reset scheduler at local midnight
- Optional private archive mode
- No external progress tracking by others

### Suggested Stack
- Frontend: Flutter or React Native
- Local DB: SQLite/Drift/Realm
- Notifications: Firebase Cloud Messaging or local notifications
- Prayer times: location + reliable prayer-time library
- Charts: lightweight local chart package

### Free / Low-Cost AI API Options (for prototype)
1. **OpenRouter free models** (varies by availability)
2. **Hugging Face Inference API free tier**
3. **Groq free-tier models** (if available in your region)
4. **Local model via Ollama API** (best privacy; no external cloud calls)

Add fallback strategy:
- If cloud AI unavailable, switch to local/offline assistant mode automatically.

---

## Final Output You Must Produce

When implementing, provide:
1. Complete feature architecture
2. Screen-by-screen UX flow
3. Database schema (with daily reset logic)
4. State management plan
5. API integration plan (AI + prayer times + YouTube)
6. Privacy/security checklist
7. MVP roadmap (Phase 1, 2, 3)
8. Future enhancements list

The final app must feel deeply spiritual, practical, private, and beautiful — helping the user become consistent in Namaz, Quran, and personal growth every day.
