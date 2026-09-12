# 🌀 Useless Terminal

A completely unhelpful, chaotic, and overly dramatic custom Bash shell interface designed to waste time and roast the user at every opportunity.

---

## 🌟 Features

* **🌐 Dramatic Globe Startup:** A 15-second spinning ASCII globe animation initializes every time the terminal launches.
* **😴 System Exhaustion Cooldown:** Every 10 commands, the terminal claims to be exhausted, triggers a green matrix rain effect, and enters a 10-second red cooldown phase.
* **🐱 Cat Hack (`h`):** Typing `h` launches a red matrix rain followed by a 15-second loading animation, concluding with a cyan **SYSTEM HACKED BY CAT** warning banner.
* **🤖 Chatbot Rejection:** Casual conversational attempts (`hi`, `hello`, `hey`, `yo`, `who`, `what`) are met with immediate rejection: *"I am not a chatbot, I am a Linux terminal dumbass!"*
* **🐱 Spinning Cat (`cat`):** Replaces the standard `cat` command with an ASCII spinning cat animation that refuses to display file contents for privacy reasons.
* **🔦 Torch Hardware Hook (`torch`):** Pretends to connect to external torch hardware, loading for 30 seconds before declaring the attempt useless.
* **🚀 NASA & Wi-Fi Hacks (`help`, `hack`):** Simulated penetration tests with Matrix rain and custom output banners.
* **🔥 Dynamic Roasts:** Automatically plays audio cues, loading bars, and random roasts on unrecognized commands.
* **🚫 Standard Command Overrides:** Overrides standard administrative commands (`sudo`, `rm`, `apt`, `clear`, `ls`) with fake error messages and sarcastic remarks.

---

## 🚀 Quick Start

### Prerequisites

Ensure basic Unix terminal tools and audio utilities are installed:

```bash
sudo apt-get update
sudo apt-get install cmatrix pulseaudio-utils ffmpeg alsa-utils libnotify-bin

```

### Installation

1. Clone this repository or create a directory for the project:
```bash
mkdir -p ~/useless-terminal
cd ~/useless-terminal

```


2. Save the custom configuration script as `.uselessrc` inside the project folder:
```bash
nano ~/useless-terminal/.uselessrc

```


3. Setup optional audio files:
Create a folder named `audio` on your Desktop and place `.wav`, `.mp3`, or `.ogg` sound files inside it:
```bash
mkdir -p ~/Desktop/audio

```



---

## 🎮 Usage

Launch the Useless Terminal with custom resource configurations:

```bash
bash --rcfile ~/useless-terminal/.uselessrc

```

### Key Custom Commands

| Command | Action |
| --- | --- |
| `h` | Triggers red matrix rain, a 15s progress bar, and the Cyan Cat Hack screen |
| `hi` / `hello` / `hey` | Delivers chatbot roast response |
| `cat` | Displays the spinning cat animation |
| `torch` | Runs fake torch hardware connection sequence |
| `hack` | Displays simulated network access denial |
| `help` | Runs simulated NASA access sequence |
| `clear` | Fails to clean the dirty terminal |

---

## 🛠️ Configuration

To modify roasts, animations, or timing sequences, edit the `useless_trap()` and custom alias functions inside `~/.uselessrc`.
