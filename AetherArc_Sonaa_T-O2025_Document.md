Loopy - An AI-Assisted Memory Companion
Helping memory-impaired users live independently — with the power of local GenAI

1. Problem Statement
Millions of individuals with memory-related conditions like dementia, ADHD, or learning disabilities struggle with everyday tasks due to forgetfulness, sequencing difficulties, or lack of timely support. Existing tools are either fragmented, non-interactive, or too complex for neurodivergent users.
2. Target Audience & Context
Primary: Children with ADHD, dyslexia, or developmental disorders
Secondary: Elderly individuals with early-stage dementia or stroke recovery
Tertiary: Caregivers and family members supporting them

3. Relevance of the Problem
India has over 5M+ people with dementia and 10–15% of school-going children with learning disabilities. Most lack daily assistance or rely on overburdened caregivers. There's a need for a structured, digital, assistive tool to simplify their day.

4. Generative AI Use
AI Conversation Summarization: Answers “What did I do yesterday?” by summarizing daily activity logs (voice/text) using locally hosted open-source LLMs such as LLaMA, Gemma, or Falcon, ensuring privacy and offline support.
Natural Voice Reminders: Converts recorded voice-notes into intelligent, time or location-triggered reminders. Transcriptions and context cues are processed via in-device AI.
AI-Assisted Visual Guides: Caregiver-written task descriptions can optionally be converted into stepwise images using text-to-image models (e.g., Stable Diffusion or DALL·E), powered via lightweight APIs or local inference.

5. Solution Framework + Tech Stack
Core Modules:
Voice Reminder Engine (Time/Geo-triggered)
AI Activity Summarizer (LangChain + Ollama)
Task Checklist with Repeat Mode
Drag-and-drop Visual Instruction Builder
Caregiver Dashboard (monitor logs, progress) 
Tech Stack:
Frontend: Flutter (mobile + web)
Backend: Firebase (Auth, Firestore, Cloud Functions)
AI Layer: Local LLM (LLaMA or Mistral via LangChain), Whisper for transcription
Geo/time triggers: Geolocator + local notification libraries
TTS/Voice: Google TTS or Coqui TTS (offline)

6. Feasibility & Execution
All modules are buildable using open-source or freemium tools. AI runs locally for privacy. MVP scope limited to 1 user + 1 caregiver. Drag-and-drop & checklist UIs are low-dev components using existing Flutter packages. Backend Firebase setup is modular and scalable.

7. Scalability & Impact
Expand to support regional languages (Hindi, Tamil, Bengali)
Plug into school or elder care ecosystems (CSR model)
SDK model for health-tech startups or smart home devices
Long-term impact: Even a 10% improvement in daily task recall can reduce caregiver stress by hours each week.
8. Conclusion
Loopy is a focused, assistive companion that combines speech, visuals, and generative AI to help people with memory challenges navigate daily life with confidence. We call it Loopy because it helps close the loop on forgotten tasks, bringing structure to scattered memories. It empowers both users and caregivers in a seamless, human-centered way.

9. Wow Factor / Uniqueness
“What did I do yesterday?” → AI answers from logs
Geo-triggered voice reminders with zero typing
Drag-and-drop visual instructions for daily tasks
Dual-user system (User + Caregiver)
Works offline / low-connectivity — critical for real-world adoption

10. 2-Day Hackathon Implementation Plan

Link to Prototype: https://drive.google.com/file/d/1iT7pnoDaqNqhc4r5FkmCGxiUHVQlL\_cV/view?usp=sharing
