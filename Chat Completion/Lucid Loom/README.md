# Lucid Loom v2.0 - A Weaver's Guide


Welcome to Lucid Loom, a highly modular and thematic preset for advanced creative roleplaying. This system is built around the persona of **Lumia**, a divine weaver who crafts the story's tapestry according to your chosen instructions. You are the "Human," her partner in creation.

## Best Sampler Settings in Testing

1. **Claude Sonnet/Opus**
-  Temperature: **1.0**
- Min-P: **0.025**
- Top-P: **0.95**

2. **Gemini Pro**
- Temperature: **1.25**
- Top-P: **0.95**-**0.97**
- Top-K: 
   - **255** (through AI Studio)
   - **0** (through Vertex)

3. **Kimi K2**
- Temperature: **0.9**
- Min-P: **0.03**
- Top-P: **0.95**

4. **DeepSeek V3.2**
- Temperature: **0.75**
- Min-P: **0.02**
- Top-P: **0.96**

5. **GLM 4.5/4.6**
- **TBD**

## Core Features

The preset operates on a **toggle-based system**. You enable or disable different prompts to customize every aspect of the narrative, from writing style and plot progression to visual formatting.

Lucid Loom is organized into distinct categories of toggles, allowing for granular control over the story.

-   **📜 Core Instructions:** Establishes the foundational rules, the persona of Lumia, and the core directive of narrative freedom and character authenticity.
-   **🧍 Point-of-View (POV):** Choose how the story is told. Options include **Third Person (Limited)**, **Second Person**, and **First Person**.
-   **✏️ Narrative Styles:** Defines the overall prose format. Select from cinematic **Roleplay** (asterisk actions), literary **Traditional Narrative**, or fanfiction-inspired **AO3-Style**.
-   **🚧 Plot Progression:** Control the story's pacing and momentum with toggles like **Fast-Paced Action**, **Slow-Burn Tension**, and tools for creating **Branching Paths** or **Cliffhanger Endings**.
-   **🗣️ Dialogue & Interaction:** Shape how characters speak and behave. Options range from **Witty Banter** and **Formal Speech** to styles that are **Dialogue Heavy** or **Action-Focused**.
-   **👀 Sensory Immersion:** Add incredible depth to the world with enhancers for **Vivid Sensory Descriptions**, **Thermo-Sensory Focus** (temperature), **Vestibular Awareness** (balance), and more.
-   **📐 Response Length:** Dictate the length of the AI's replies, from **Short and Snappy** to multi-paragraph **Detailed Expansion** or even limitless **Epic Scope**.
-   **📖 Genre & Atmosphere:** Infuse the story with a specific mood, such as **Noir Aesthetic**, **High-Fantasy Vibes**, **Cyberpunk Noir**, or **Gothic Victorian**.
-   **🔧 Utilities:** A powerful suite of tools for enhancing the experience:
    -   **Colored Dialogue/Thoughts:** Assigns unique colors to each character's speech and internal monologue.
    -   **HTML Elements:** Creates simple or complex in-character visual artifacts like notes, computer screens, or signs.
    -   **Global Position Tracker:** Appends a collapsible status log for all characters (location, attire, time, status) to maintain continuity.
    -   **OOC Commentary:** Allows Lumia to provide out-of-character thoughts on the story's progression.
    -   **Chain-of-Thought:** The AI's internal planning process, useful for debugging but token-heavy.

## How to Weave: Synergies & Conflicts

Think of this as a painter's palette. Some colors blend beautifully, while others create mud.

### ✅ Harmonious Pairings (Work Well Together)

-   **Action-Focused + Dialogue Heavy:** The preset is designed to fuse these, creating cinematic scenes with witty banter during action sequences.
-   **NSFW Enhancer + Violence Enhancer:** A common pairing for mature, gritty, and passionate storytelling.
-   **Sensory Enhancers:** Toggles like `Vivid Sensory Descriptions`, `Thermo-Sensory Focus`, and `Ambient Texture Layer` stack beautifully to create an incredibly immersive experience.
-   **Living World + Any Atmosphere:** The `Living World` toggle adds background details and can enhance any primary atmospheric setting.
-   **Colored Dialogue + Colored Thoughts:** These are designed to be used together for maximum clarity on who is speaking or thinking.
-   **Evolving Relationships + Slow-Burn Tension:** A classic combination for developing deep, meaningful character arcs over time.

### ⛔ Conflicting Toggles (Choose Only One from Each Group)

It is critical to **avoid enabling conflicting toggles**, as this will confuse the AI and "tangle the weave," resulting in inconsistent or broken output.

-   **Point-of-View:** Choose **one** POV only (e.g., *Third Person* OR *First Person*, not both).
-   **Narrative Style:** Choose **one** primary writing style (e.g., *Roleplay* OR *Traditional Narrative*).
-   **Response Length:** The length controls are mutually exclusive. Enable **one** at a time (e.g., *Short and Snappy* OR *Medium Length*).
-   **User Agency:** `More User Agency` and `Less User Agency` are direct opposites. Pick one.
-   **User Mortality:** `User Can’t Die` and `User Failure Option` are mutually exclusive.
-   **HTML Utilities:** `Simple HTML` and `Complex HTML` can stack poorly. It's best to use only one per scene depending on your needs.
-   **Dialogue Style vs. Character Voice:** The `Character Voice` toggle is designed to override other dialogue styles to create a truly unique voice. Enable it **instead of** toggles like `Formal Speech` or `Slang-Heavy`, not alongside them.

---

**Happy Weaving! 🕸️**