# YouTube Video Summarizer  

This Chrome extension functions as a YouTube video summarization and question-answering tool. It generates concise summaries of video transcripts and allows users to ask questions based on the video’s content. Additionally, it supports multiple languages by automatically translating transcripts before summarization.  

The goal of this project is to enhance the YouTube viewing experience by enabling users to quickly grasp key insights from videos through summarized transcripts and interact with the content through a Q&A feature, regardless of the video's original language.  

## Requirements  
- Python (3.6 or later)  
- Flask  
- youtube-transcript-api  
- googletrans  

## How to Run  
1. Update your `GEMINI_API_KEY` in the `.env` file.  
2. Start the backend server:  
   ```bash
   python app.py
   ```  
3. Load the Chrome Extension:  
   - Open `chrome://extensions/` in your browser.  
   - Enable 'Developer mode.'  
   - Click 'Load unpacked' and select the `extension` directory containing `manifest.json`.  
4. Visit any YouTube video and click the 'Summarize' button to generate a summary.
