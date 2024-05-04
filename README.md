# ChatGPT YouTube Transcript Chunker

## Description
**Break up YouTube transcripts and prep them to import into ChatGPT.**
If you're like me, you're on information overload. If I'm not watching videos on 2x, I prefer to use ChatGPT to summarize into nice, scannable bullet-points, and have the ability to interact with ChatGPT regarding the video content and concepts. BUT, because ChatGPT has a maximum limit on input, this can be challenging. Rather than splitting up transcripts into chunks manually, let's use some Javascript to save some time. This also adds "Remember the following part of a video transcript. More is coming. Only answer 'ok' when you're done." to each "chunk," to make sure ChatGPT shuts up until it has the complete transcript.

I realize there are GPTs out there that automate this process; however, I didn't like the idea of using someone else's GPT, and felt like making my own simple solution that didn't need any API access (for now. May improve later...) 👋

## Usage
1. Open the index.html in your favorite browser, and get a new conversation started up in ChatGPT.
2. Open up your YouTube video, and ensure the transcript is displayed (click on the "Show Transcript" button in the description area).
3. Copy the entire transcript and then paste it into the input area, then click the "Process Transcript" button.
4. Now click on the "Copy Part 1" button to copy the first transcript chunk to your clipboard.
5. Paste into your ChatGPT conversation and send the message.
6. Repeat until the entire transcript is added into your ChatGPT conversation.
7. Now, you can ask for a summary of the video transcript, and continue from there, getting more details and interacting with the content.
