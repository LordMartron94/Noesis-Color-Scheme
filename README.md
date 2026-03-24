# Noesis Color Scheme

Greetings, fellow deity.

This color scheme is available for you to enjoy!

Note: *If using languages other than Go (specifically `go.mod`), Python, or custom `.lspec` definitions, the scheme may not work properly out of the box. It relies on highly specific semantic scopes.*

## Table of Contents

- [Introduction](#introduction)
	- [Noesis Context](#noesis-context)
- [Usage](#usage)
- [Contributing](#contributing)
	- [Design Philosophy](#design-philosophy)
- [Contact](#contact)
- [Changelog](#changelog)

## Introduction

I initially created this color scheme for Python, but have since rebuilt it from the ground up (v2.0) to support a much wider and more rigorous architectural vision. It now natively supports custom domain-specific languages (like `lspec` and `ruleforge`), Go modules, and standard programming constructs with extreme precision. 

This project began alongside my work to create Noesis; a truly intelligent AI, unlike LLMs. In order to prevent overflowing you with irrelevant details, I will only briefly mention the scope of my project, so you gain the context for this theme. 
See [Noesis Context](#noesis-context) for this explanation.

My color scheme was intended to evoke in me a feeling of working on a great project like this, to create life, to be a god. In alignment with truth itself. Every hue is therefore carefully selected to not just be conceptually and semantically linked to what it colors, but also to follow the overall themes of:
- Power
- Wisdom
- Truth
- Logic

See [Design Philosophy](#design-philosophy) for more detail.

### Noesis Context

LLMs by fundamentals use statistical computations and godlike datasets for pattern recognition, in order to *simulate* understanding. 
This results in a lot of inefficiencies, biases, computation costs, etc. And on top of that, the LLMs aren't even intelligent to begin with as they do not strictly **understand**.

I, however, will start out using different assumptions, most prominently, that in order to create a true Artificial Intelligence, one must begin by replicating Real Intelligence in the digital format.
Humans are the only species that satisfy this precondition:
A) Of humans we have a relatively deep understanding of the mechanisms of intelligence and thought across various levels of analysis (neuroscience, cognitive science, philosophy).
B) Of humans, through shared cognitive schemata and language, and even brain scans, we can prove that we can act intelligently rather than based on instinct through reinforcement learning. 

To my mind there is no animal species that suffices this precondition, as such, the human species will be my reference.

In short, I am going to attempt to replicate human intelligence digitally while also allowing it to run on consumer hardware.

By no means do I assume this to be trivial, nor do I guarantee that I will succeed at my project. 
However, I do think I am in a unique position to develop this, as I have interdisciplinary knowledge across several fields (although in none of them I am already a world-class expert):
- Neuroscience
- Cognitive Science (specialty in Cognitive Load Theory by Sweller)
- Philosophy
- Systems Thinking (for example John Boyd's OODA loop, and Niklas Luhmann's Functionally Differentiated Systems Theory)
- Computer Science / Programming

I refuse to go into the details of how I want to accomplish this mechanistically, both for brevity and privacy.
Regardless, I am open for questions and debate, see [Contact](#contact) for means to do so.

It is my personal life's mission, purpose, calling, to optimize the world's formal education system. 
As such, inspired by Luhmann, I gave myself 30 years to develop a Grand Prescriptive Theory of Optimal Education, after which I will implement it.
Yes, I have a more detailed plan, but again, I will not mention it here.

Because this is my mission, everything I do for my Noesis project serves this purpose as well. 
Hence, none of the time and energy is wasted, even if I don't succeed in replicating intelligence.

## Usage
1. Install through the Sublime Text package manager or manually import it.
2. For maximum effect, use it alongside custom syntaxes that map to the semantic variables (e.g., `syntax_keyword`, `syntax_function`).

If you want to use it with other languages, be sure to expect bugs, and feel free to [contribute](#contributing) your implementations for other languages.

## Contributing
As a developer, you have multiple choices... You are allowed to:
- Fork this repository and maintain your own version in private.
- Fork this repository and maintain your own version in public.
- Fork this repository and contribute to it.

In order to contribute, you should make your changes and make a pull request 
with a detailed explanation of what you changed, added, or removed, and why you did so.
Make sure that you also adhere to the design philosophy that follows.

### Design Philosophy
As mentioned earlier, I wanted to have a certain color theme in mind when working:
- Power
- Wisdom
- Truth
- Logic

Version 2.0 introduces a strict architecture separating the **Base Palette** (absolute hex colors) from **Semantic Mappings** (functional assignments like `syntax_keyword`), ensuring that the rules only consume semantic variables.

What follows is the mapped hue philosophy, updated for v2.0:

| Hue | Hex Value | Semantic Meaning in Code | Why This Hue Was Chosen |
|---|---|---|---|
| **Abyssal Dark** | `#0B0E14` -> `#232A3F` | Backgrounds, Selection, Active Lines | Represents the void; absolute emptiness that allows the data to shine without distraction. |
| **Neutral Noise** | `#465173` -> `#A1B0D1` | UI Borders, Line Numbers, Documentation | The structural scaffolding. Grey offers balance and restraint; it supports but does not dominate. |
| **Main Foreground**| `#D4DCE8` | Standard Variables, Properties | The baseline truth. Clear, legible, and unopinionated. |
| **White** | `#FFFFFF` | High Emphasis, Error Highlights | Cuts through the darkness with absolute clarity. The blinding spotlight of truth. |
| **Cyan** | `#00E5FF` | Types, Classes, Declarations | Feels sharp, clean, and advanced. Used for structural blueprints and architectural truth. |
| **Mint** | `#00FFAA` | Built-in Primitives | Represents foundational architecture. The raw material of the system. |
| **Plasma** | `#39FF14` | Functions, Execution | Highly active and energetic. Represents the active agents of logic and transformation. |
| **Purple** | `#B5179E` | Control Flow, Keywords | Embodies mystery and higher power, aligning with the godlike force of keywords that control the universe of the code. |
| **Magenta** | `#D500FF` | Logic Gates, Truth Evaluation | Intense and piercing. Used for logical comparisons where absolute truth is evaluated. |
| **Pink** | `#FF007F` | State Mutation, Math, Missed Tokens | Anomalous and dynamic. Stands out to represent mathematical shifts or elements that fall outside standard bounds. |
| **Yellow** | `#FCEEA7` | Strings, Payload Data | Luminous and distinct. Used for raw data payloads and mutable content. |
| **Orange** | `#FF5500` | Constants, Immutable Data | Symbolizes permanence, authority, and value. Constants are immovable truths, shining with immutable wisdom. |
| **Alert/Amber** | `#FF9F1C` | Critical Comments, Git Modified | Piercing and urgent. Demands immediate attention without breaking the system. |
| **Error Red** | `#FF003C` | Illegal Tokens, Deletions | Carries danger and intensity. Appropriate for destructive actions or critical system failures. |

#### A Note on Comments
Many people think comments should be unobvious since they write a lot of comments.
I disagree. I am more in camp with Bob Martin, and think comments indicate poor expression in code, 
thus comments are written ONLY when I cannot express myself properly in code. 
As such, the rare comments that I do place are highly important, critical even... Thus they must stand out (mapped to `base_alert`).

By contrast, documentation (doc-strings) are written for every public function and class, and are thus not as critical to see (mapped to `base_neutral_dim`).

## Contact
The following means of communication are available to you in order to contact me:
- Discord (personal): mr.hoornasp.learningexpert
- Discord (community server): https://discord.gg/cvd8gUdukj
- Email: md.career@protonmail.com

I would suggest for quick questions to reach out to me on my personal Discord, 
and for lengthy debates or in-depth questions to either reach out to me on e-mail or join my Discord community.

The community is called The Mind Academy; intended for those who are interested in intellectualism, 
metacognition, learning how to learn, education, etc.

## Changelog

### 24 March 2026 (v2.0.0):
- **Complete Rewrite:** Architected the theme into Tiered Logic (Base Palette -> Semantic Mappings -> Rules).
- **Expanded Language Support:** Added hyper-specific, semantic styling for LangSpec (`.lspec`), Ruleforge, and Go Modules (`go.mod`).
- **Enhanced Visual Hierarchy:** Introduced semantic variables for logical operators, math mutations, and engine directives.
- **GitGutter Integration:** Native support for inline Git blame annotations and status badges.

### 26 September 2025 (v1.2.4):
- Initial release of my scheme up to now.