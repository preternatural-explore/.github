## Hi there 👋

Welcome to @PreternaturalAI's collection of real-world examples of what you can build with our frameworks.

# Table of Contents

1. [MLX Swift Chat: Run LLM models locally with MLX!](#mlx-swift-chat-run-llm-models-locally-with-mlx)
2. [Movie Search: Semantic search for movies using text-embeddings.](#movie-search-semantic-search-for-movies-using-text-embeddings)
3. [Voice Recorder: Transcribe your voice recordings with Whisper.](#voice-recorder-transcribe-your-voice-recordings-with-whisper)
4. [Poem Generator: Personalized poetry, anytime, any topic!](#poem-generator-personalized-poetry-anytime-any-topic)
5. [NarratorBot: Transform Image into Audio](#narratorbot-transform-image-into-audio)
6. [HealthApp: Nutritional Insight from Food Photos](#healthapp-nutritional-insight-from-food-photos)
7. [PhotoTranslator: Generate Creative Sentences in a Foreign Language from a Photo](#phototranslator-generate-creative-sentences-in-a-foreign-language-from-a-photo)
8. [Swift Code Generator: Generate Sample Code on Demand](#swift-code-generator-generate-sample-code-on-demand)

## [MLX Swift Chat: Run LLM models locally with MLX!](https://github.com/preternatural-explore/mlx-swift-chat)
This project is a fully native SwiftUI app that allows you to run local LLMs (e.g. Llama, Mistral) on Apple silicon in real-time using MLX.

https://github.com/preternatural-explore/.github/assets/1157147/03caee96-224b-4e52-99db-f47a023083a7



## [Movie Search: Semantic search for movies using text-embeddings.](https://github.com/preternatural-explore/AIMovieSearch)
The MovieSearch app enables users to search for movies using natural language queries, providing a more intuitive and efficient search experience. This app demonstrates working with the OpenAI API, structuring training data, implementing Retrieval-Augmented Generation (RAG), and using text embeddings to add semantic search to any application.

<img width="1280" alt="export533D506A-68B5-47FE-B166-9DE02C94AB6F" src="https://github.com/preternatural-explore/.github/assets/1157147/9ac8ec1f-c409-41a4-b42a-fda0eeaf9e05">

## [Voice Recorder: Transcribe your voice recordings with Whisper.](https://github.com/preternatural-explore/VoicePilot)
VoicePilot demonstrates how to enhance the recording experience by not only capturing audio but also offering intelligent transcription and analysis. Upon creating a recording, VoicePilot utilizes OpenAI’s Whisper API to deliver precise transcriptions, complete with timestamped segments for easy navigation. Moreover, it automatically generates a descriptive name, a concise summary, and highlights the key points for each recording, streamlining the customer’s review process and making information retrieval straightforward.


<img width="1280" alt="voicemoc" src="https://github.com/preternatural-explore/.github/assets/1157147/bfc1aa14-bc55-40ae-b148-c9fdee10d7f7">

## [Poem Generator: Personalized poetry, anytime, any topic!](https://github.com/preternatural-explore/PoemWriter)
PoemWriter is a simple demonstration of the LLM completions API. The user enters a poem topic and the LLM generates a full poem about the topic. Here is a poem generated for WWDC!
<img width="688" alt="poemwriterscreenshot" src="https://github.com/preternatural-explore/.github/assets/1157147/2306adf3-39a4-4100-aede-25d82e6a0853">

## [NarratorBot: Transform Image into Audio](https://github.com/preternatural-explore/narrator-bot)
A bot that narrates what it sees in front of it, in the style of a BBC nature documentary with the voice of Sir David Attenborough. Uses GPT-4o for image understanding and ElevenLabs for Audio Generation.

https://github.com/preternatural-explore/NarratorBot/blob/main/286146979-29be0f4d-1673-4e74-af31-66f21b046008.mp4

## [HealthApp: Nutritional Insight from Food Photos](https://github.com/preternatural-explore/health-app/)
A simple app to upload an image to OpenAI Vision for analysis. If the item is food we will gather the pros, cons, type & overall summary about the food.

https://github.com/preternatural-explore/health-app/blob/main/313036265-c294c3e1-ec6b-4118-9ac1-cdedeaef074b.mov

## [PhotoTranslator: Generate Creative Sentences in a Foreign Language from a Photo](https://github.com/preternatural-explore/photo-translator)
The PhotoTranslator app leverages OpenAI's Vision API to bring translations into the user's surroundings seamlessly. Users can simply take a photo, and the app, using an on-device YOLO model, identifies objects within the image. Then, creative sentences in the target language are generated about the picture in general and each object specifically along with the foreign language audio using ElevenLabs API, making learning a new language an engaging and immersive experience.<br/>
<img width="413" alt="phototranslationdescription" src="https://github.com/preternatural-explore/.github/assets/1157147/5204b5ab-fe06-4241-b55f-d07cb0e2daf7">
<img width="413" alt="exportA25BFD02-B306-4936-87A7-FB421D9F21F1" src="https://github.com/preternatural-explore/.github/assets/1157147/4bbfaeb7-385f-46ee-9039-58685ad68873">

## [Swift Code Generator: Generate Sample Code on Demand](https://github.com/preternatural-explore/swift-code-generator)
The Swift Code Generator is a demo app that allows users to input natural language descriptions of desired Swift functionality and receive corresponding Swift code snippets. The app demonstrates the use of a clever prompting technique: leveraging the Claude 3.5 Sonnet model, it initiates the assistant's response with a code block marker and employs a stop sequence to ensure only the relevant code is returned. This method effectively filters out explanatory text, focusing solely on the generated Swift code - a technique which can be further applied to other use-cases.

<img width="426" alt="smartcode" src="https://github.com/user-attachments/assets/26854973-6727-4bb2-a7f4-39b5262d88e5">

