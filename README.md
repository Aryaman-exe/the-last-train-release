# the-last-train-release
# 🚆 THE LAST TRAIN

> **The clock stopped at 11:47 PM. The train didn't.**

**THE LAST TRAIN** is a psychological mystery / interactive narrative game set aboard a train that never seems to reach its destination.

You wake up at **11:47 PM**.

Five strangers are sitting inside the carriage.

Nobody remembers getting on.

The train won't stop.

And then the voice begins.

---

## 🎮 About The Game

**THE LAST TRAIN** is a text-driven psychological mystery inspired by games such as *Undertale*, *Deltarune*, and narrative mystery experiences.

Rather than focusing on combat or exploration, the game focuses on:

- Dialogue
- Character interaction
- Player decisions
- Psychological tension
- Environmental storytelling
- Mystery and deduction
- Consequences
- Atmospheric presentation

The player interacts with five passengers, learns their stories, investigates the train, and eventually faces a series of increasingly disturbing trials.

Every conversation can reveal something.

Every choice can matter.

And sometimes, the most important information is what **isn't** said.

---

# 📖 Story

You open your eyes.

Darkness.

The sound of metal moving against metal fills the carriage.

**Click.**

**Click.**

**Click.**

You don't remember falling asleep.

You don't remember getting on the train.

You look around.

There are five other passengers.

None of them look familiar.

You reach for your phone.

> **NO SIGNAL.**

You look at the clock.

> **11:47 PM**

You wait.

> **11:47 PM**

The clock isn't moving.

Then the train speaks.

> **"ATTENTION, PASSENGERS."**

Your journey begins.

---

# 👥 The Passengers

Five strangers occupy the carriage.

### Karube

Practical, frustrated, and focused on escape.

He's already trying to figure out how the train doors work.

> *"Do you know how to open this thing?"*

### Chōta

Nervous and uncertain.

His memories seem fragmented, and some of the things he remembers don't quite line up.

> *"Do you know where we're going?"*

### Mira

Calm and analytical.

She's already examined parts of the train and seems more observant than she initially lets on.

> *"Don't bother. I've already tried."*

### Ann

Quiet and intensely focused.

Something about the frozen clock has caught her attention.

> *"Has the time moved?"*

### Niragi

Strangely calm.

While everyone else is trying to understand what is happening, he seems almost comfortable with it.

> *"We're probably dead already."*

---

# 🚨 THE TRIALS

The train doesn't simply transport its passengers.

It tests them.

## TRIAL 01 — THE MISSING TICKET

Five passengers.

Five tickets.

One of them is wrong.

The player must inspect the tickets, question the passengers, identify inconsistencies, and determine who is carrying the wrong ticket.

The trial introduces the game's core mechanic:

> **Observe. Question. Decide.**

But the answer may reveal something much more disturbing than a simple mistake.

---

## TRIAL 02 — THE PASSENGER COUNT

The train announces:

> **CURRENT PASSENGER COUNT: 6**

Five passengers.

And you.

**Six.**

The count is correct.

Then someone disappears.

The display still says:

> **CURRENT PASSENGER COUNT: 6**

Someone else disappears.

Still:

> **6**

The train insists the number is correct.

Eventually, the player must answer one question:

> **Who should leave?**

---

# 🧠 Psychological Mystery

THE LAST TRAIN intentionally avoids explaining everything.

The game uses ambiguity as part of its storytelling.

Players are encouraged to question:

- Who are the passengers?
- Why can't anyone remember boarding?
- Why is the clock frozen?
- Who is controlling the train?
- Why do the trials exist?
- Why does the passenger count never change?
- What exactly is the train testing?
- And why does the train seem to know things that the passengers don't?

Not every mystery is meant to receive an immediate answer.

Some are meant to remain with you.

---

# 🖥️ NORTHLINE INTERFACE

The main menu contains:

```text
> BOARD
  NORTHLINE INTERFACE
  EXIT
```

**NORTHLINE INTERFACE** is an in-universe railway computer/archive system.

It provides access to information that exists outside the main story.

### Available systems

- **TV DATABASE**
- **PASSENGER RECORDS**
- **TRAIN RECORDS**
- **INCIDENT REPORTS**
- **INTERNAL LOGS**
- **??? [LOCKED]**

---

## 📺 TV DATABASE — TVMaze Integration

The NORTHLINE INTERFACE connects to the **TVMaze public API** to retrieve real television data.

Players can search for television shows directly from the game's railway terminal.

The system supports:

- Live show searching
- Show information
- Genres
- Premiere dates
- Status
- Networks
- Summaries
- Episode information
- Show artwork where available

API:

https://www.tvmaze.com/api

TVMaze attribution is included within the interface.

---

# 🎨 Visual Style

THE LAST TRAIN uses a deliberately minimal visual language.

### Aesthetic

- Monochrome pixel art
- Black-and-white visuals
- CRT/terminal-inspired interfaces
- Sparse environments
- Glitch effects
- Dark railway interiors
- Pixelated character portraits
- Typewriter-style dialogue
- Slow transitions
- Minimal UI

The goal isn't to overwhelm the player with visual effects.

It's to make the player stare at an otherwise empty screen and wonder:

> **"Why does this feel wrong?"**

---

# 🔊 Audio

Audio is designed around subtle repetition rather than traditional game music.

The experience uses:

- Ambient train sounds
- Mechanical clicking
- Typewriter-style dialogue sounds
- Atmospheric transitions
- Sparse horror ambience
- Silence

The recurring **click** of the train is particularly important.

It becomes part of the game's identity.

---

# 💬 Dialogue System

THE LAST TRAIN features an interactive dialogue system rather than simple linear text.

Players can:

1. Select a passenger
2. Start a conversation
3. Choose dialogue options
4. Receive different responses
5. Discover clues
6. Affect character trust and suspicion
7. Return to the passenger selection
8. Continue investigating

Different passengers respond differently depending on how the player interacts with them.

The game uses controlled branching rather than creating enormous dialogue trees.

This allows choices to feel meaningful while keeping the narrative focused.

---

# 🧩 Game State & Consequences

The game keeps track of important information such as:

```text
Passenger conversations
Player choices
Trust
Suspicion
Discovered clues
Trial progress
Passenger states
```

This allows earlier interactions to influence later conversations and events.

The player isn't simply choosing dialogue.

They're building a version of the story.

---

# 👁️ The Ending

The final sequence deliberately leaves room for interpretation.

After everything is over, the player exits the train.

They turn around.

The passengers are still there.

Sitting inside.

Watching.

Then something begins to change.

Their faces glitch.

One by one.

The portraits stop resembling the people you remember.

They become something familiar.

Something much closer to home.

The final display reads:

```text
PASSENGER COUNT: 1

11:48 PM

It always was.
```

The game never explicitly tells the player what this means.

**You decide.**

---

# 🛠️ Technology

THE LAST TRAIN is built primarily using web technologies.

### Core

- **HTML5**
- **CSS3**
- **JavaScript**

### APIs

- **TVMaze API** — television database integration

### Visuals

- Pixel-art assets
- Atmospheric artwork
- Deterministic character avatars
- CSS-based effects and transitions

### Audio

- HTML5 Audio
- Web Audio API

The project is designed to run directly in a modern web browser without requiring a traditional game engine.

---

# 🎮 Controls

| Input | Action |
|---|---|
| **Mouse Click** | Select / interact |
| **Arrow Keys** | Navigate |
| **W / A / S / D** | Navigate menus |
| **Enter** | Confirm |
| **Space** | Advance dialogue |
| **ESC** | Back / exit current interface |

---

# 🔮 Future Development

Potential additions include:

- More trials
- Expanded passenger records
- Additional train records
- Incident reports
- Internal railway logs
- More branching dialogue
- Additional endings
- More environmental storytelling
- Hidden records
- More corrupted/locked NORTHLINE files
- Expanded TV database functionality
- Additional visual glitches and effects
- More sound design
- Deeper passenger relationships
- More clues connecting the trials

The goal is to gradually expand the train's mystery without explaining everything too quickly.

---

# 🎯 Design Philosophy

THE LAST TRAIN follows a simple principle:

> **The less the game tells you, the more you start looking.**

There are no giant tutorials explaining the world.

No quest markers telling you what to think.

No exposition dump explaining the mystery.

Instead, the player is given:

**A train.**

**Six passengers.**

**A frozen clock.**

**A voice.**

**And a choice.**

---

# 📜 Credits & Attribution

### TVMaze

Television data is provided by **TVMaze** through its public API.

https://www.tvmaze.com

https://www.tvmaze.com/api

All third-party assets, audio, imagery, fonts, and libraries should be credited according to their respective licenses.

---

# ⚠️ Status

**THE LAST TRAIN — In Development 🚧**

This project is actively being developed and may contain unfinished content, placeholder records, experimental mechanics, and changing story elements.

---

<div align="center">

### **THE TRAIN IS STILL MOVING.**

### **11:47 PM**

### **Are you getting off?**

</div>

