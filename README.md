# 🎵 Melodify — An Emotive Musical Decision Tree
![UX Flowchart](Melodify/groupphoto.jpg)
## 📌 Project Overview
Melodify is an application designed to enhance midi instrument practice and improvisation through the
guidance of a midi-based decision tree. The project aims to transform these activities through ‘guided
improvisation’ where a player is given the opportunity and encouraged to experiment with alternative
harmonies and melodies as they perform a piece. Conceptually, the project can be described as a “choose
your own adventure”-type interface, where notes played on the input instrument influence the direction of
musical development.

Built using **Python, Pygame, and MIDI**, Melodify supports beginner to intermediate players, blending **music theory, gamification, UX principles, and immersive audio** into a dynamic experience.

---

## 🧭 UX Journey

Melodify was built around **Human-Computer Interaction (HCI)** and **Flow Theory**. Some UX highlights:
Melodify is designed to provide users with the most realistic and fun experience to learn piano quickly. That
is why it receives inputs from a real keyboard, which is connected to the laptop externally, through a USB or
MIDI cable. The app supports various kinds of keyboards, ranging from large e-pianos to small MIDI pianos.

<div align="center">

<table>
  <tr>
    <td align="center"><b>Flowchart of User Experience Journey</b></td>
  </tr>
  <tr>
    <td><img src="Melodify/image.png" style="object-fit: contain;"/></td>
  </tr>
</table>

</div>

Thanks to the intuitive design of the interface, the user experience is straightforward. After plugging the
keyboard into a computer, users open Melodify app. The application automatically detects the keyboard and
connects it. If many keyboards are connected, users can select the desired one on “Setting” page by pressing
“Settings” button. To begin the learning journey, users press the “Start” button, then choose a song to learn
and press the “Play” button to start the game.

<div align="center">

<table>
  <tr>
    <td align="center" colspan="2"><b>Flowchart of User Experience Journey</b></td>
  </tr>
  <tr>
    <td>
      <img src="Melodify/Notes falling.png" width="800" style="object-fit: contain;" />
    </td>
    <td style="vertical-align: top; padding-left: 20px;">
      <p>
        Once the game begins, the notes (dots) are displayed and fall vertically from the top of the screen.
        A virtual keyboard layout appears at the bottom of the app, representing the user's physical keyboard.
      </p>
      <p>
        As users press keys on their keyboard, the corresponding keys on the virtual keyboard are highlighted,
        creating an intuitive, responsive interaction. This visual feedback helps users adapt quickly and correct
        their mistakes in real-time.
      </p>
    </td>
  </tr>
</table>

</div>






---

## ✨ Key Features

- 🎶 **Branching Song Paths**: Notes split into multiple coloured branches — users choose their musical journey.
- 🎨 **Mood-based Colour Design**: Blue for calm, orange for energetic — each colour affects the music and emotion.
- 🎯 **Gamified Feedback System**: Real-time visual cues (green/red keys), scoring, and a health bar.
- 🎹 **MIDI Instrument Support**: Connect your real keyboard for tactile play.
- 📈 **Adaptive Learning Curve**: Progressive difficulty keeps learners engaged.
- 🔊 **Dynamic Audio Layering**: Music evolves as users play — layering backing tracks and melodies.

![Gameplay Screenshot - Note Branching](PLACEHOLDER_BRANCHING_NOTES_IMAGE_URL)

---


## 🚀 How It Works

### 🔁 Game Loop

- Read user input via MIDI
- Display falling notes mapped to real piano keys
- Detect hits/misses and update score/health
- Allow real-time branching choices

### 🧩 Technical Modules

- `main.py`: Launches the game and manages logging.
- `game.py`: Handles game states, MIDI input, rendering.
- `subScreens.py`: UI screens (pause, home, etc.)
- `note_data.py`: Loads branching MIDI structures.
- `player.py`: Manages background audio via `pygame.mixer`.
- `ui.py`: Renders piano roll, notes, score, progress.
- `settings.py`: Central config (BPM, health, colours).

![Code Screenshot](PLACEHOLDER_CODE_SNIPPET_IMAGE_URL)

---

## 🎧 Music & Audio Design

- Based on *Faded* by Alan Walker (vi–IV–I–V in G Major).
- 14 adaptive variations composed in **Logic Pro X**.
- Real-time decisions dynamically shift harmony, rhythm, and timbre.
- Directional and layered audio enhances immersion.

![Audio Design Diagram](PLACEHOLDER_AUDIO_DIAGRAM_IMAGE_URL)

---

## 📖 Example Use Cases

- **Emma**, a hobbyist pianist, uses Melodify to create calming or energetic variations of songs based on her mood.
- **Jonny**, a student, tracks progress via score/health and gradually improves his timing and accuracy.

---

## 🎓 Built With

- **Python 3**
- **Pygame**
- **pygame.midi**
- **Logic Pro X** (for audio composition)
- UX Principles: HCI, Flow Theory, Aesthetic-Usability, Feedback/Visibility

---

## 📽️ Demos

- 🎥 [YouTube Prototype Walkthrough](https://www.youtube.com/playlist?list=PL3NdP9cBhJqxt8QMijgVOG0K6N70bp2YM)
- 📁 [GitLab Source Code](https://projects.cs.nott.ac.uk/psybg3/musi3071-emotive-musical-decision-tree)

---

## 🧠 Future Improvements

- 🧠 ML-based generative music decisions
- 🧍‍♀️ Collaborative jamming (real-time co-play)
- 🎤 Support for microphone & voice input
- 🎵 Expanding to jazz, blues, and user-uploaded tracks

---

## 👨‍👩‍👧‍👦 Team Melodify

- Jonathan Moore  
- Christopher Wainwright  
- James Bateman  
- Benjamin Goringe  
- Cheuk Yin Tze  
- Amelia Walastyan  
- Ngoc Nguyen

---

## 📎 Appendix

- 🎓 Course: MUSI 3071 – Music & Mixed Reality  
- 🏫 University of Nottingham  
- 📅 January 2025  

---

## 📷 Image Placeholders (Replace These)

- `PLACEHOLDER_HERO_IMAGE_URL`: Mockup or splash of app
- `PLACEHOLDER_BRANCHING_NOTES_IMAGE_URL`: Screenshot showing branching notes
- `PLACEHOLDER_UX_FLOWCHART_IMAGE_URL`: UX or decision tree diagram
- `PLACEHOLDER_CODE_SNIPPET_IMAGE_URL`: Code demo (e.g., state machine or MIDI input)
- `PLACEHOLDER_AUDIO_DIAGRAM_IMAGE_URL`: Music layers / Logic Pro X project screenshot

---

## 💬 License

MIT License — Feel free to remix and build upon this for your own educational or creative use.

