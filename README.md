# AI DOC MAGIC 📄 ✨

AI DOC MAGIC 📄 ✨ is a script for Google Docs that utilizes the OpenAI API to generate text based outputs based on user prompts and selected text within the document. The script adds a dropdown menu called "AI MAGIC" to your Google Docs interface, with various options for generating text.

# Feature Examples  🤖
The AI DOC MAGIC creates a add on that allows you to create a simple way to use prompts and GPT3 generated written outputs in docs by creating functions with specific prompts. You can create add a function that prompts GPT3 to perform specific completions some ideas could be:

- General: generates text based on a general prompt in doc.
`var prompt = "Generate" + selectedText;`
- Blog Ideas: generates 3 ideas for a blog post about the selected text
`var prompt = "You are a {insert profession}. Generate 3 different blog ideas about" + selectedText;`
- Summarize: generates a summary of the selected text
`var prompt = "Summarize into a short paragraphy with 5 bullet points:" + selectedText;`
- Expand: generates a 1500-word blog post about the selected text
`var prompt = "You are a {insert profession}. Write a 1000 word blog post about" + selectedText;`
- Alternatives: generates alternative tone phrases (Positive, Neutral, Persuasive) for the selected text
`var prompt = "You are {insert profession}. Provide 3 alternative tones for" + selectedText + "Neutral, Simplified, Persuasive"`
- Mission Doc: generates a mission statement for a company related to the selected text
` var prompt = "You are a startup founder of an Edtech compnay Mindjoy. This is your Mission Doc format: Mission (Aim to convince the reader that this problem is important. Why is this problem relevant?), Goals (set a goal for this mission. Your goals are something you have control over for example: Improve website copy or create a template), Deliveralbles (The deliverables are the outputs or assets that are created to move the mission forward or as a result of the mission), Stakeholders (Think about all the people or teams that would need to offer mindshare to help you solve the problem or grab the opportunity), Mission Road Map (Use this section to flesh out the key steps that need to occur in order to reach your mission goal include a deadline for each step), Success Metrics (To set up success metrics, think about the outcomes that you would like to achieve and how you measure them). Write a mission doc using the above format about" + selectedText;`

# Setup 🚧 
- Make sure you have a Google account and are logged in.
- Open App Scripts:
<img width="620" alt="Screenshot 2023-01-21 at 12 06 12" src="https://user-images.githubusercontent.com/84702635/213862053-b87c7da2-bfcd-4833-8686-cc30942c5a0f.png">

- Paste Scripts:
<img width="779" alt="Screenshot 2023-01-21 at 12 14 01" src="https://user-images.githubusercontent.com/84702635/213862375-e3b9fc8b-0c95-442a-8f9f-b6af0bf20f34.png">

- Add your OPENAI API KEY
<img width="486" alt="Screenshot 2023-01-21 at 12 16 46" src="https://user-images.githubusercontent.com/84702635/213862476-6125e610-f0e8-4df2-a01d-a45eab54b136.png">

- Functions: Remember for every function you add, add  `.addItem("xxxx", "generatexxx")` to the menu function. 

- Prompts: Modify your prompts and function names according to what the desired completions.
<img width="441" alt="Screenshot 2023-01-21 at 12 17 29" src="https://user-images.githubusercontent.com/84702635/213862490-d5b6b202-1970-4379-bc4f-cd8c3839a3be.png">

- Get Writing: return to google docs, write input text, highlight and select prompt to run script and generate completion.
<img width="989" alt="Screenshot 2023-01-21 at 12 30 22" src="https://user-images.githubusercontent.com/84702635/213862951-554c59e2-7961-4f4f-9930-1005f0d0f216.png">

