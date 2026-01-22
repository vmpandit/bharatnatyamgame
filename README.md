# 🕉️ Natya Shastra: The Bharatanatyam Experience

A culturally immersive rhythm and memory game based on the ancient Indian classical dance form, **Bharatanatyam**. Players step into the role of a *Shishya* (disciple), learning authentic mudras and adavus from a Guru in a sunlit temple courtyard.



## ✨ Key Features

*   **Authentic Movement Logic:**
    *   **Dynamic Formation:** Students step forward ("downstage") to listen to the Guru and step back into formation to perform.
    *   **Araimandi Posture:** Players must master the *Araimandi* (half-sit) position using the Spacebar for specific steps.
    *   **Adavus & Mudras:** Visual representation of authentic hand gestures and leg movements.
*   **Cultural Visuals:**
    *   **White Marble Nataraja:** A pristine, high-contrast statue of the Lord of Dance, Nataraja, set against a bright daytime temple sky.
    *   **Detailed Costumes:** Characters wear authentic practice sarees with proper pleats (*fan*), waistbands (*oddiyanam*), and sashes (*pallu*).
    *   **Temple Atmosphere:** Animated oil lamps (*deepams*) and a serene courtyard setting.
*   **Gameplay Mechanics:**
    *   **Call & Response:** Watch the Guru perform a sequence, memorize it, and repeat it to the beat.
    *   **Rhythm Engine:** Integrated audio feedback using Tone.js for steps and Carnatic-inspired cues.
    *   **Progression System:** Advance through 6 levels from *Alarippu* (Invocation) to *Thillana* (Finale).

## 🎮 Controls

| Key / Action | Function | Context |
| :--- | :--- | :--- |
| **Arrow Keys** | Perform Steps | Directional movements (Left, Right, Up, Down) |
| **Spacebar (Hold)** | **Araimandi** (Squat) | Hold to maintain the half-sit posture required for specific moves |
| **'S' Key** | **Bhramari** (Spin) | Perform a spin move |
| **Mouse / Touch** | UI Interaction | Navigate menus, quizzes, and on-screen D-Pad |

## 🚀 How to Run

This is a standalone HTML5 game. No server or installation is required.

1.  **Download:** Save the file `natya_shastra_marble.html`.
2.  **Open:** Double-click the file to open it in any modern web browser (Chrome, Firefox, Safari, Edge).
3.  **Play:** Click "Enter Courtyard" to begin your training.

*Note: For the best audio experience, interact with the page (click anywhere) immediately after loading to initialize the audio context.*

## 📚 Levels & Curriculum

1.  **Alarippu (Invocation):** Learn the basic standing posture (*Samapadam*).
2.  **Jatiswaram (Melody):** Introduction to *Araimandi* (half-sit).
3.  **Shabdam (Expression):** Focus on timing and rhythm.
4.  **Varnam (Masterpiece):** Complex sequences involving spins.
5.  **Padam (Devotion):** Slower, emotion-heavy movements.
6.  **Thillana (Finale):** Fast-paced, joyous rhythmic conclusion.

## 🛠️ Tech Stack

*   **HTML5 Canvas:** For all rendering, animations, and visual effects.
*   **JavaScript (ES6):** Core game logic, state management, and class-based entity system.
*   **GSAP (GreenSock):** Smooth tweening for character movements (formation changes, limb articulation).
*   **Tone.js:** Synthesized audio engine for rhythmic feedback and musical notes.

## 🎨 Art Style Details

*   **Character Design:** Vector-style geometry drawn via Canvas API. Features distinct skin tones, jewelry, and animated sari pleats that react to leg spread.
*   **Environment:** Minimalist but evocative temple setting with atmospheric lighting (daytime sun gradients).
*   **The Nataraja:** Rendered in **White Marble** style with slate-grey details to ensure high contrast against the Guru character, solving visibility issues from previous iterations.

## 📝 License

This project is open-source. Feel free to modify and learn from the code!

***

*Created for the love of Dance and Code.*
