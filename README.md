# AI Language Data Projects — Sinhala

A collection of practical AI language-data projects focused on **Sinhala localization, speech transcription, linguistic annotation, and data quality**.

These projects demonstrate practical experience in preparing structured language data that can support AI assistants, localization systems, speech technologies, and multilingual AI applications.

---

## Projects

### 01 — Sinhala AI Localization Dataset

A manually created English-to-Sinhala localization dataset containing **50 examples** covering common user interactions in digital products and AI-powered applications.

The dataset focuses not only on direct translation, but also on making Sinhala text sound **natural, clear, and appropriate for the intended context**.

#### Dataset includes

* English source text
* Sinhala localization
* Context
* Tone
* Register
* Localization decision
* Linguistic/localization notes

#### Categories

* Login & Authentication
* Account & Profile
* Payments
* Shopping
* Errors & System Messages
* Notifications
* AI Assistant
* Education
* Privacy & Security
* Help & Support

#### Annotation approach

Each example was reviewed according to:

* **Tone** — Neutral, Friendly, Helpful, Apologetic
* **Register** — Formal, Standard, Casual
* **Localization Decision** — Direct translation, Natural adaptation, Cultural adaptation, Keep English term
* **Notes** — Explanation of important localization choices

**Dataset:** `01-sinhala-ai-localization/Sinhala_AI_Localization_Dataset.xlsx`

---

### 02 — Sinhala Speech Transcription & Annotation Dataset

A manually transcribed and annotated Sinhala speech dataset created from a publicly available Sinhala-language YouTube video.

The project focuses on converting spoken Sinhala into structured data and adding useful linguistic and audio-related annotations.

#### Dataset includes

* Segment ID
* Timestamp
* Sinhala transcription
* Speech quality
* Speaker
* Emotion

#### Annotation approach

Speech segments were manually reviewed and annotated for:

* **Transcription** — What was actually spoken in the audio
* **Quality** — Whether the speech was clear or difficult to understand
* **Speaker** — Speaker identification based on the available audio
* **Emotion** — Perceived emotional characteristics of the speech

#### Source

The speech was transcribed from a publicly available YouTube video:

**YouTube source:**
https://www.youtube.com/watch?v=19DEiYppZow

The original audio/video is **not included in this repository**. Only the manually created transcription and annotation data are provided.

**Dataset:** `02-sinhala-speech-annotation/Sinhala_Speech_Annotation_Dataset.xlsx`

---

## Repository Structure

```text
ai-language-data-projects/
│
├── README.md
│
├── 01-sinhala-ai-localization/
│   └── Sinhala_AI_Localization_Dataset.xlsx
│
└── 02-sinhala-speech-annotation/
    └── Sinhala_Speech_Annotation_Dataset.xlsx
```

---

## Skills Demonstrated

### Language & Localization

* English → Sinhala localization
* Natural language adaptation
* Sinhala linguistic judgment
* Tone and register classification
* Context-aware translation
* Cultural adaptation
* Terminology decisions

### Speech & Linguistic Data

* Sinhala speech transcription
* Audio segmentation
* Timestamp annotation
* Speaker labeling
* Emotion annotation
* Speech quality assessment
* Structured dataset creation

### AI Data Preparation

* Data annotation
* Label design
* Dataset structuring
* Quality checking
* Consistent annotation
* Human-reviewed language data

### Tools

* Microsoft Excel
* YouTube
* Manual transcription and annotation

---

## Why These Projects?

Sinhala is a relatively low-resource language compared with languages such as English.

Creating high-quality Sinhala language data requires more than simply translating or transcribing text. Human judgment is important for understanding:

* Natural Sinhala phrasing
* Context
* Tone
* Formality
* Cultural meaning
* Spoken-language patterns
* Ambiguous or unclear speech

These projects were created to demonstrate practical experience with the type of **human-reviewed language data preparation and annotation** that can support multilingual AI systems.

---

## Data Quality Approach

The datasets were manually reviewed with a focus on:

1. **Accuracy** — Capturing the intended language or spoken content.
2. **Consistency** — Applying annotation labels consistently.
3. **Naturalness** — Using Sinhala that sounds appropriate to native speakers.
4. **Context** — Considering the situation in which the language is used.
5. **Clarity** — Avoiding unnecessary complexity.
6. **Transparency** — Recording important localization or annotation decisions.

---

## Project Status

| Project                                   | Status    |                            Samples |
| ----------------------------------------- | --------- | ---------------------------------: |
| Sinhala AI Localization Dataset           | Completed |                                 50 |
| Sinhala Speech Transcription & Annotation | Completed | Manually annotated speech segments |

---

## Intended Applications

The techniques demonstrated in these projects can be relevant to:

* AI assistants
* Multilingual chatbots
* Sinhala localization
* Speech recognition
* Text-to-speech systems
* Conversational AI
* AI training datasets
* Language evaluation
* Human-in-the-loop AI systems
* Data quality and annotation workflows

---

## Disclaimer

The datasets in this repository were created for **portfolio and demonstration purposes**.

The original audio/video used for Project 02 belongs to its respective rights holder and is not redistributed in this repository. The repository contains only the author's manually created transcription and annotation data.

---

## Author

**Kavidu Lakshan**

Technology Management | AI & Data | Business & Technology

GitHub: [Kavidu23](https://github.com/Kavidu23)
