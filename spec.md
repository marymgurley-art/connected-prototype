# Connected — Prototype Spec

## What We're Building
A five-screen clickable prototype showing the family member experience of the Connected app. This is not the full product — it is a specific snapshot of one moment in one family's day, designed to demonstrate the emotional core of the product.

## The Scenario
**Sarah** is a daughter in her mid-30s. She lives nearby but has a full-time job and small children. She hasn't visited her mom in two weeks. It's a Tuesday afternoon. She has five minutes between meetings and opens the app.

Her mom is **Judy**, early 80s, lives on the 4th floor of a memory care facility. Judy knows who her family is but has difficulty with conversation, following directions, and experiences paranoia and some depression. Before her diagnosis she loved watercolor painting, golf, playing cards, and investing in stocks.

Sarah's son **Jake** just had his first day of kindergarten yesterday.

The emotional job of this app: **help Sarah feel connected to her mom's daily life, reducing the guilt of not being able to visit more often.**

---

## The Five Screens

### Screen 1 — Today's Feed (Home Screen)
Sarah's home screen when she opens the app. A warm, scrollable timeline of Judy's day as it unfolds.

**What's on it:**
- Header: "Judy's Day — Tuesday, May 13" with Judy's photo (warm, personal)
- A live timeline of updates posted by staff, working top to bottom through the day:
  - 8:00 AM — "Judy had breakfast — scrambled eggs and toast. She was in good spirits this morning."
  - 10:00 AM — "Exercise class on the 4th floor. Judy participated for about 15 minutes."
  - 11:30 AM — "Judy joined the lunch outing to Teresa's Mexican Grill! She ordered the enchiladas."
  - 2:00 PM — ⭐ HIGHLIGHTED CARD: "Watercolor Painting — Judy was really engaged today. She stayed for the whole session." + photo of Judy at the table with a brush in her hand, paint on the page.
- At the bottom: a prominent button — **"Send a Moment to Mom"**
- Bottom navigation: Feed | Calendar | Mom's Profile | Send

**Design notes:**
- Warm, soft color palette — not clinical. Think peach, warm white, sage green.
- The watercolor card should feel special — slightly elevated, maybe a soft border or highlight, because it connects directly to who Judy was before her diagnosis.
- Mobile-first. Works on any phone.

---

### Screen 2 — Today's Calendar
What's happening on the 4th floor today, pulled from the facility's specialty care calendar.

**What's on it:**
- Header: "Today's Schedule — Tuesday, May 13"
- A clean list of today's activities with times and locations:
  - 8:00 AM — Breakfast (4th Floor Dining Room)
  - 9:30 AM — Greet the day with Gary! (4th Floor)
  - 10:00 AM — Drumming (North Living Room)
  - 11:30 AM — Lunch outing to Teresa's Mexican Grill (meet in lobby)
  - 12:00 PM — Lunch (4th Floor Dining Room)
  - 1:00 PM — Fill Your Vase! (4th Floor South Dining Room)
  - 2:00 PM — Walking Group with Gary (4th Floor North Hallway)
  - 3:00 PM — Community Choir (Wellbeing Studio)
  - 5:00 PM — Dinner (4th Floor Dining Room)
  - 7:30 PM — Wind Down with Calm Connect (4th Floor North Living Room)
- Activities Judy actually attended should appear highlighted or checked off as the day progresses
- A small note at the top: "Times and events are subject to change"

**Design notes:**
- Simple, clean list view
- Color code or tag activity types: meals, exercise, social, creative, spiritual
- "Watercolor Painting" (when it appears on other days) should be tagged as a favorite activity based on Judy's profile

---

### Screen 3 — Judy's Profile
The heart of the personalization feature. Who Judy is — filled in by her family to help staff connect with her.

**What's on it:**
- Judy's photo, full name, room number (Room 412)
- **Her Story** — a short paragraph written by Sarah:
  *"Mom grew up in Minnesota and raised three kids. She was a self-taught watercolor painter — her work hung in our living room for as long as I can remember. She loved golf, playing cards with her friends on Thursday nights, and had a real mind for investing. She followed the stock market every morning with her coffee. She still lights up when she hears Patsy Cline."*
- **Judy Loves:**
  - Watercolor painting
  - Golf
  - Card games
  - Patsy Cline
  - The stock market / investing
  - Coffee in the morning
- **Helpful to Know:**
  - She can feel anxious in loud or unfamiliar situations
  - She responds well to one-on-one conversation
  - She loves looking at family photos
  - Using her name and making eye contact helps her feel calm
- **Family:**
  - Sarah (daughter) — primary contact
  - Jake (grandson, age 5) — she lights up when she sees him

**Design notes:**
- This screen should feel like a scrapbook, not a medical form
- Warm typography, maybe a soft background
- A small "Edit Profile" button for families to update it

---

### Screen 4 — Moment from Today (Watercolor Card, expanded)
When Sarah taps the highlighted watercolor card in the feed, it opens to a fuller view.

**What's on it:**
- The photo of Judy at the table, larger
- Staff note: *"Judy was really engaged in watercolor painting today — she stayed for the whole session and worked on a painting of flowers. It was a great afternoon."*
- Time stamp: 2:47 PM
- A small heart/reaction button for Sarah to respond (she can tap a heart to let staff know she saw it)
- Below the photo: **"Send a Moment Back"** button that takes her to Screen 5

**Design notes:**
- This is the emotional peak of the prototype — design it to feel warm and meaningful
- The photo should feel like a real candid, not a stock photo

---

### Screen 5 — Send a Moment
Sarah records and sends a video message and photo to her mom.

**What's on it:**
- Header: "Send a Moment to Mom"
- A large camera/video toggle — photo or video, simple switch
- A big round record/capture button in the center
- Below the button, a preview area showing what's been captured
- A short text field: "Add a note..." 
  - Pre-filled example: *"Hi Mom! Jake started kindergarten today — he was so brave. We're thinking about you. See you soon! Love, Sarah"*
- A photo attachment option (for the kindergarten photo — Jake in his backpack at the front door)
- A prominent **Send to Mom** button
- Small note below: "A staff member will share this with Judy at a good moment in her day"

**Design notes:**
- This screen should feel easy and warm — not like a form
- The "Send to Mom" button should be the most prominent element
- Reassure Sarah that the message will be delivered thoughtfully by staff

---

## Design Direction
- **Palette:** Warm whites, soft peach, sage green, warm gray. Nothing clinical or cold.
- **Typography:** Friendly but not childish. Clean and readable.
- **Tone:** This app should feel like a warm hug, not a monitoring dashboard.
- **Mobile-first:** Designed for a phone screen. Works on any device.
- **No login screen needed for prototype** — open straight to Screen 1 (Today's Feed)

---

## What Success Looks Like
Someone looking at this prototype should feel: *"I would want this if my parent were in memory care."* The watercolor moment and the kindergarten video send should both land emotionally. If those two moments work, the concept works.

---

## What This Prototype Does NOT Need
- Real backend or database
- Actual photo upload functionality
- Login / authentication
- Staff-facing screens (future prototype)
- Full month calendar view (just today's schedule)
