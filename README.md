# make-audio-microlearnings
Blueprints & instructions

Sends timely micro-lessons via email and Whatsapp for on the go study. Originally created under the execuse of supporting my kid in AP Euro preparation
- Micro learnings were pre-processed into a Google sheets (previous version would create lessons each run, but it had higher repetition, and costed more tokens)
- It picks a micro-lesson from a Google Sheet at a time
- Creates narration and stores in a drive
- Sends out Whatsapp message and email copy at scheduled time

Requires
- Make.com account
- Elevenlabs API Key
- Whatsable API Key
- Google Drive & Gmail

Instruction
- Import the JSON blueprint in Make.com
- Create a Google sheet with 3 columnes (title, lesson, status)
- Store source training material in Drive
- Configure connections and APIs in Make
- Configure drive, Whatsapp component in Make
- Use the prompt in the file prompt.txt in this repo directly in Gemini (or other), and uploading the PDF of the book to be used
