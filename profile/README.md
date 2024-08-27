<img width="100%" alt="KoelLabsLogoLong" src="https://github.com/user-attachments/assets/ea4c54a5-4919-4273-a0eb-58b6aaf7c4a9">


[![Mozilla Builders](https://img.shields.io/badge/Mozilla-000000.svg?style=for-the-badge&logo=Mozilla&logoColor=white)](https://future.mozilla.org/builders/)
![Patreon](https://img.shields.io/badge/Patreon-F96854?style=for-the-badge&logo=patreon&logoColor=white)
![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)

# Koel Labs
Koel Labs innovates tools to provide real-time feedback and improve your pronunciation. Useful for language learning!

Checkout the [project proposal](https://docs.google.com/document/d/1-CiYRXL2UK_jAynByqgqHhKYLmjmNsg8y_VNUHJCUFU/edit) for details.

## Motivation
So you are learning a new language; you have done the flashcards and memorized the grammar patterns, and yet, after endless hours of practice, your speech sounds broken, unnatural, and slow. Over 48% of people who speak another language feel anxious about their accent, and 35% of English speakers want to get rid of their accent when speaking a foreign language ([Babel Language Anxiety Study](https://www.babbel.com/en/magazine/accent-anxiety-study)). While challenging, mastering the sound and tone of a language can transform a person’s ability to communicate effectively. But committing new mouth movements to muscle memory and memorizing [inconsistent rules](https://www.youtube.com/watch?v=mOw7CdpK44w) about nuances in the stress of various syllables is tedious, demoralizing to do alone (expensive to do with a human tutor), and requires great discipline.

## The Problem
Mastering pronunciation, tones, and style in language is currently challenging without a personal tutor, and many don't even know how to improve their pronunciation.

Large language learning classrooms in schools, with 30-40+ people to 1 teacher, provide little personal feedback on speaking/conversation practice, but this could be greatly supplemented with an AI-based tool that gives this personal feedback.

Most language learning apps do not provide pronunciation feedback at all (or only at a superficial level of whether it can recognize each word) and thus leave it up to the learner to assess whether their pronunciation is correct by comparing it with provided audio clips. It is hard, if not impossible, to evaluate oneself when learning the language, and an outside observer (preferably someone already fluent in the language) is required to assess properly. Current language learning apps incorporating pronunciation are not engaging and inaccessible to people who do not know linguistic phonemes. No app holistically covers stress/pitch accent, intonation, tone, and cadence.

## The Solution
The main contribution we aim to make is _real-time personal feedback_. This should come in the form of _actionable corrections on grammar and pronunciation_ provided in an _interactive format_ – a conversation with an LLM and audio model-powered language coach so that learners can ask questions about the pronunciation feedback as they practice _engaging dialogues from their favorite shows_. We want to go beyond the existing approach of leaving the learner to compare their own pronunciation with the lackluster audio clips provided.

Behind the scenes, this will take advantage of IPA phonemic transcription (symbolic representations of sound). Our goal is to hide this from the learner (since most people are not familiar with IPA phonemes). Instead, the app will identify mispronounced words and explain how the syllables are pronounced using examples in the learner’s native language (when applicable, not all sounds exist in all languages) and different words they already know how to pronounce that share sounds with the words they struggle with.

### Who is this for?
The grand vision is for all language learners hoping to improve their pronunciation. The MVP will focus on language learners living in the US who have lived here a few years but have a language other than English as their native language and still struggle with their pronunciation. We know a few of these people in our families and neighborhoods who are interested in being the first set of user testers, making it a practical target audience (All three of us co-founders come from families of immigrants or are immigrants ourselves!).

### Why is this a viable Startup Idea?
It is sufficiently differentiated from existing solutions yet exists within a proven market (digital language learning). For example, Duolingo generated $531 million in revenue in 2023 and is growing fast.

### Why are we the right people to make this happen?
- We have experience fine-tuning/training speech recognition/synthesis models
- We have experience designing production RAG+LLM powered applications used by 10s of thousands of MAU at various startups (e.g. [Gooey AI](https://gooey.ai/))
- We are actively involved in NLP and low-resource language research at University of Washington labs (e.g. UbiComp, ICTD, Yulias NLP Lab)
- We are great software engineers (interned at T-Mobile, Gooey.AI, and more)
- We have experience learning languages
- We are funded by [Mozilla Builders](https://future.mozilla.org/builders/)

## Roadmap
- [x] Acquire funding from Mozilla Builders
- [ ] Evaluate existing models for pitch accent, ToBI intonation labeling, stress accent detection, etc.
- [ ] Finetune/train and evaluate a model that does IPA transcription with timestamps for English
- [ ] Curate a small evaluation dataset for prompt engineering and LLM choice. This will include a handful of everyday speech phenomena to ensure the model can explain the relevant tongue positioning, etc.
- [ ] Create and iterate on an LLM pipeline to provide feedback to the user
- [ ] Create/license visuals/animations for each phoneme (there are less than 40 relevant for English) and curate a database of common words in different languages that can be used to explain English sounds to their native speakers
- [ ] Create a web application that allows desktop users to practice audio clips from their favorite shows (see the [Figma demo](https://www.figma.com/proto/VPHimCfONGurh0s07IKova/Mozilla_Pitch?node-id=2-187&t=slW83co4vzXQNPGt-1&scaling=scale-down&content-scaling=fixed&page-id=0%3A1))
- [ ] Support more languages for learning
- [ ] Expand the number of available audio sources (e.g. audiobooks from LibriVox)
- [ ] Recommendation system that recommends movies/shows that are appropriate to the learner's language level

## The Team
- [Alexander Metzger](https://sandergi.com/) (he/him/his) — Founder and CEO — experienced with fine-tuning/training ASR/TTS models, MLOps, full-stack development, startups, and open source.
- [Aruna Srivastava](https://www.linkedin.com/in/arunasri) (she/her) - Co-Founder & Machine Learning Scientist - experienced with NLP + Linguistics and figma design.
- [Ruslan Mukhamedvaleev](https://github.com/digitalRM) (he/them) - Co-Founder & Full-Stack Software Developer - experienced with full-stack development (React, NextJS, VueJS), UI/UX design, and branding.

_**Shipping with ❤️ from Seattle, Washington.**_

## Broader Impact
Ethical considerations when teaching language at scale include taking care not to push one “standard” dialect (e.g., the White-American pronunciation), thus perpetuating particular expectations of how words should be pronounced. We hope to address this by offering a wide variety of movies/shows with different dialects for learners to choose from (and by leveraging audio models with diverse dialect support).

## Open Source Licensing
Application code and prompts will be open-sourced under the [FSL-1.1-Apache-2.0](https://fsl.software/)

Model weights and training code will be open-sourced under the [CreativeML Open RAIL-M](https://huggingface.co/spaces/CompVis/stable-diffusion-license)

### Repositories
- Machine Learning models and pipelines: [Link](https://github.com/KoelLabs/ML)
- Web Application: [Link Coming Soon...](https://github.com/KoelLabs/webapp)

### Contributing
We are not yet at the stage of receiving pull requests. You are welcome to get involved with suggestions/feedback in Github discussions and through issues on our public repos. Support through the PayPal and Patreon links at the top of the README is always appreciated. Happy language learning!
