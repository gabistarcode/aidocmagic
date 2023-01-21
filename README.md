# AI DOC MAGIC 📄 ✨

AI DOC MAGIC 📄 ✨ is a script for Google Docs that utilizes the OpenAI API to generate text based outputs based on user prompts and selected text within the document. The script adds a dropdown menu called "AI MAGIC" to your Google Docs interface, with various options for generating text.

# Features 🤖
The AI DOC MAGIC creates a add on that allows you to create a simple way to use prompts and GPT3 generated written outputs in docs by creating functions with specific prompts. You can create add a function that prompts GPT3 to perform specific completions some ideas could be:

- General: generates text based on a general prompt in doc.
- Blog Ideas: generates 3 ideas for a blog post about the selected text
- Summarize: generates a summary of the selected text
- Expand: generates a 1500-word blog post about the selected text
- Alternatives: generates alternative tone phrases (Positive, Neutral, Persuasive) for the selected text
- Mission Doc: generates a mission statement for a company related to the selected text
- Script: generates a script for a video or audio production related to the selected text.

# Setup 🚧 
- Make sure you have a Google account and are logged in.
- Open App Scripts:
<img width="620" alt="Screenshot 2023-01-21 at 12 06 12" src="https://user-images.githubusercontent.com/84702635/213862053-b87c7da2-bfcd-4833-8686-cc30942c5a0f.png">

- Paste Scripts:
<img width="779" alt="Screenshot 2023-01-21 at 12 14 01" src="https://user-images.githubusercontent.com/84702635/213862375-e3b9fc8b-0c95-442a-8f9f-b6af0bf20f34.png">

- Add your OPENAI API KEY
<img width="486" alt="Screenshot 2023-01-21 at 12 16 46" src="https://user-images.githubusercontent.com/84702635/213862476-6125e610-f0e8-4df2-a01d-a45eab54b136.png">

- Functions: Remember for every function you add, add  `.addItem("Item", "generateIten")` to the menu function. 

- Prompts: Modify your prompts and function names according to what the desired completions.
<img width="441" alt="Screenshot 2023-01-21 at 12 17 29" src="https://user-images.githubusercontent.com/84702635/213862490-d5b6b202-1970-4379-bc4f-cd8c3839a3be.png">

- Get Writing: return to google docs, write input text, highlight and select prompt to run script and generate completion.
<img width="989" alt="Screenshot 2023-01-21 at 12 30 22" src="https://user-images.githubusercontent.com/84702635/213862951-554c59e2-7961-4f4f-9930-1005f0d0f216.png">

