# quiet_team

The Quiet Team is a project that explores how AI can detect alignment—and exclusion—within multi-speaker conversations.

Starting from raw audio (MP3), the pipeline performs:

🎧 Audio preprocessing and speaker diarization (pyannote.audio)

✍️ Transcription with Whisper

🧠 Semantic similarity analysis using SentenceTransformers

🌐 Graph construction in Neo4j

🔍 Natural language querying with LangChain

🧍‍♂️ Optional speaker identification via voice matching (Resemblyzer)

This repo includes all the steps to turn speech into structure—making hidden group dynamics visible through code.

🔬 Inspired by a fictional debate on Trump’s tariffs.
Not all voices carry the same weight. AI knows.
