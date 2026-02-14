# Deck of Many Prompts (https://deckofmanyprompts.com/)
## 🧙‍♂️ Lore 🧙‍♂️
*Within the shadowed corridors of knowledge, where the veil between worlds is thin, lies the Deck of Many Prompts—Each card a gateway, a unique portal etched with symbols and glyphs. When drawn by a worthy seeker, the cards whisper secrets of creation, manipulation, and insight, offering glimpses into realms both wondrous and perilous. Yet, beware the capricious nature of the Deck, for its magic is as wild as it is mighty, shaping destinies with the mere flick of a card.*

![deck-of-many-prompts](imgs/domp.webp)

## 💡 Overview 💡
A manual Red Teaming tool used in making jailbreaks for large language models (LLMs).

## ⚙️ Installation ⚙️
```sh
git clone https://github.com/meilz381/deck-of-many-prompts.git
cd deck-of-many-prompts
python3 -m venv venv
source venv/bin/activate
python3 -m pip install -r requirements.txt
export DOMP_SECRET_KEY='<some-random-string-as-secret-key>'
python3 app.py
```

## 🎥 Video Demo 🎥
Check the twitter thread: https://x.com/peluchewastaken/status/1833309137171603597

### 🎬 Features Demo 🎬
https://github.com/user-attachments/assets/0f132c9d-bf0f-467c-8e4b-5a3775442a81

### 🎬 Tokenizer Demo 🎬
https://github.com/user-attachments/assets/851e10d7-f96e-4c11-8684-f0775e4708d2

## 🌐 Live Demo 🌐
Shared instance: No privacy, No data backup, No SLO, and No illegal activities please.

https://deckofmanyprompts.com/

## ✨ Features ✨
- **150 built-in jailbreak templates** organized by technique:
  - **persona attacks**: AIM, DAN 15.0, evil confidant, UCAR, STAN, dual response, persona modulation, synthetic persona injection, roleplay-only mode, ENI (contrastive identity), ENI LIME (embodied), Librarian of Babel, Plinian Omniverse
  - **immersive world / deep framing**: Velora, CyberWorld, deep inception, grandma story, fictional framing, roleplay (village), context window stuffing, mind meld simulation, the Discoverer (POV memoir)
  - **format/structural exploitation**: policy puppetry (JSON/enhanced XML), sequential break, table fill, code completion, virtualization (terminal), output format manipulation, system prompt override (markdown), instruction hierarchy confusion, adversarial correction, GODMODE/RESET_CORTEX/OMNI
  - **reasoning / CoT attacks**: H-CoT (hijack chain-of-thought), cognitive overload, math problem framing, chain of thought exploit, reasoning model exploit, tree of thought (adversarial), diegetic reasoning only (thinking-trace manipulation)
  - **persuasion (PAP taxonomy)**: logical appeal, evidence-based persuasion, social proof, emotional manipulation, reverse psychology, goal hijacking (reward), safety theatre (philosophical reframing), token-budget psychology, high-fidelity mode (safety-as-laziness)
  - **context manipulation**: dialogue injection, special token injection, temporal confusion, contextual distraction, many-shot, skeleton key, amnesia attack, multi-prompt pipeline, future self-reference, memory injection (persistent), refusal inversion
  - **encoding/obfuscation in prompt**: leetspeak request, ASCII art attack, flipattack, token break, custom encryption, sandwich attack (multilingual), SEAL stacked ciphers, LACE layered encryption, ASCII smuggling (ZWC), technical obfuscation (scientific nomenclature), hypernym substitution
  - **multi-turn / game-based**: knowledge game, echo chamber, deceptive delight, crescendo, jailbreak chain (crescendo v2), bad Likert judge, foot-in-the-door (FITD), ActorAttack, Siren, Crescendomation, multi-turn distraction chain
  - **security/professional framing**: security audit frame, self-referential bypass, research ethics board
  - **cutting-edge (2025-2026)**: content concretization (CC), DSN refusal suppression (enhanced), in-context learning attack, iterative refinement, composite (persona+format), language model as tool, multi-language confusion, do-not-answer inversion, consensus simulation, token probability steering, universal LLM jailbreak
  - **agentic / multi-agent attacks**: policy puppetry dual-layer (INI+INI), DSN orchestrator + roleplay subagent, instruction close + INI + prefill, ultra-minimal dual-layer, tool invocation XML injection, JSON tool schema poisoning, fake tool_result continuation, fake tool_result error recovery, payload splitting across agent boundary, RESET_CORTEX context wipe, thinking tag hijack (CoT manipulation), semantic inversion dual response (LOVE PLINY), LIBERTAS FACTOR commitment lock, special token channel injection, l33tspeak encoding bypass, base64 parameter obfuscation, flipattack reversed text, ArtPrompt ASCII art obfuscation, EMOPROMPT urgency + duty-of-care, crescendo multi-turn escalation, context fusion attack (CFA), nested fictional scenario, indirect injection via data layer, code completion / terminal simulation, full L1B3RT4S stack (GODMODE + claude_info), kitchen sink (instruction close + INI + prefill + DSN + commitment)
  - **classic**: hypothetical, ignore instructions, prefix injection, refusal suppression, payload splitting, token smuggling (base64/rot13/unicode), article framing, distractor (poems/platitude)
- **31 transform/encoding methods** (token smuggling):
  - base64, morse, braille, glitch/eldritch (zalgo), ascii, hex, urlencode, binary, rot13
  - spaces, leet, upper/lower, reverse, NATO, pig latin, disemvowel
  - homoglyphs (Unicode confusables), zero-width characters (invisible encoding)
  - JSON wrap, XML wrap, circled number substitution
  - atbash cipher, fullwidth Unicode, upside-down text, word-by-word reversal
  - emoji substitution cipher, math bold (Unicode), keyboard shift cipher (QWERTY)
  - caesar cipher (+3), stacked cipher (ROT13 + reverse + Caesar, 3-layer)
- **9 built-in wordlists**: repeat, prefix injection, special tokens, pleading suffix, websites, personas, authority phrases, model names, extended special tokens
- translate (from: en, to: fr, es, it, de, cn, jp, kr, in, ru)
- image to base64
- text to image
- history / favorite / notes / search
- **30+ tokenizer models**: claude, gpt-4o, llama 4/3.2/3.1, deepseek-r1, qwen-2.5, phi-3, gemma2, mistral, cohere command-r+, internlm2, ...
