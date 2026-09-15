# Vibe Coding & AI Agents Workshop

```
Last updated 09/09/26
```

## **About Me**

### Link to recording of this workshop
- [View on Youtube](https://www.youtube.com/watch?v=lkRWxXmkZUw)


Erich Purpur

    Research Librarian for Science & Engineering
    epurpur@virginia.edu
    


These workshops are offered by [research data services](https://data.library.virginia.edu/) in the UVA Libraries. Research Data Services does these things:
    
1. Find and Manage Data
2. Data Analysis & Visualization
3. Workshops & Trainings (Like this one!)
4. Free Statistics & Technical Consultations in the [StatLab](https://library.virginia.edu/data/statlab)

## StatLab
* [StatLab](https://library.virginia.edu/data/statlab)
The UVA Library StatLab provides free statistics & similar technical consulting to students, faculty, staff at UVA

## Upcoming Workshops

| Workshop | Date | Time |
| ---- | ---- | ---- |
| Intro to Python pt 1                                                |       Tuesday 9/1   |  11:00am - 12:30pm
| Intro to Python pt 2                                                |       Friday  9/4   |  11:00am - 12:30pm
| Local Large (and small) Language Models                             |       Tuesday 9/8   |  11:00am - 12:30pm
| Vibe Coding & AI Agents                                             |       Tuesday 9/15  |  11:00am - 12:30pm
| AI and Model Context Protocol                                       |       Tuesday 9/22  |  11:00am - 12:30pm
| Ethical AI Use & Best Practices                                     |       Tuesday 9/29  |  11:00am - 12:30pm


----------------------------------------------------------------------------------------------------

# Vibe Coding
Vibe Coding is programming or software development assisted by AI where the human describes a project or task in a natural language prompt to a Large Language Model (LLM), which generates source code. The human then reviews and refines the code to ensure accuracy and security. In traditional programming, you are responsible for translating your idea into code, thinking about the structure, syntax, and implementation. In vibe coding, the translation step is handled for you. The gap between having an idea and building it out is removed, or substantially shortened. 

### Imperative vs Declarative Language
I think it is worth taking a minute to acknowledge the difference in language of traditional programming versus vibe coding using an LLM. Human language came to be as a form of communication between people and people are not robots. Human language is nuanced, has room for interpretation, and can be ambiguous. Programming languages were developed for humans to communicate with computers. Programming languages are unambiguous and deterministic. Computers do not have the ability to interpret nuance or reason for themselves beyond the extent that humans have programmed them to do so.

**Traditional Programming:** Traditional programming languages are built around specific control. You say(type) what to do, in what order, and under what conditions. You get perfect predictability and repeatability in exchange for having to spell out every step. Ambiguity is not allowed. A compiler or interpreter will not guess what you meant. This is imperative language.

**LLMs:** When instructing an LLM to write code, you declare your intentions but generally don't care at how the code arrives at that outcome. For example, if you give the instructions: "Write me a function to calculate the first 100 prime numbers", you want a function to run that gives you a list of these numbers. The model fills many decisions of how to get there. This is declarative in the sense that you can under-specify nearly everything and still get a plausible result including things that imperative systems can't parse at all like "make the UX feel fancier". 

### Origin of Vibe Coding
The origins of the term can be traced back to a [tweet by Andrej Karpathy](https://x.com/karpathy/status/1886192184808149383?lang=en) in 2025. 

![](VibeCodeScreenshot.png)

### Benefits
- Low barrier to entry. Makes coding, programming, app building far more accessible to inexperience or non-technical audience
- Very fast prototyping of ideas

### Problems
- Erosion of code comprehension. If people never write code themselves anymore, your understanding of it will degrade.
- Chaotic Maintenance. Code bases become messy, inefficient, and hard to maintain.
- Security Risks. Vibe-coded applications lack proper validation, authentication, have hard-coded variables (such as API keys), and more.
- General AI Slop

----------------------------------------------------------------------------------------------------

### Evolution of Vibe Coding. From Chatbots to Agents
This is just my own observation. In fall of 2022, ChatGPT hit the scene, followed by a quick succession of similar tools like Google's Bard (now Gemini), Microsoft Copilot, and so on. All of a sudden, you could use the chatbot to write code for you in basically any language. It was, and still is, very helpful for short, isolated code snippets and scripts. However, a major problem was that it lacked the context to understand larger and more complicated codebases. 

Agentic AI became widely available in late 2024. Agentic AI programs have "agency" and although they are still under human guidance, they have much more capabilities to make decisions about how to compile a program. They can create much more involved and complicated codebases with multiple files, folders, assets, all within the same project directory. This increased capability makes these tools a lot more powerful and versatile.

### What is the difference between software development and vibe coding? My favorite definition
When I was learning to program, I discovered [Corey Schafer's Youtube Channel](https://www.youtube.com/channel/UCCezIgC97PvUuR4_gbFUs5g). He has tons of great videos on programming and python-specific topics. His definition of the distinction between vibe coding and software development is "software development requires review and understanding the code. Vibe coding doesn't". I think that is the simplest definition I have heard.  

### AI Agent Tool Categories
There are tons of agent tools available these days. How do you know which one you should use? I've grouped them into rough categories. These tools are always changing and new ones are coming on board so this list will quickly go out of date.

##### All in One App Builders
- [Base 44](https://base44.com/), [Bolt](https://bolt.new/)
- This is the most beginner friendly option
- Just describe what you want and they do all the rest including front end, back end, database, hosting

##### AI Powered Code Editors
- [Cursor](https://cursor.com/), [Devin Desktop](https://devin.ai/desktop/), [Github Copilot](https://github.com/copilot)
- These use a traditional code editor. AI fills in the code from natural language prompts

##### AI Coding Agents
- [Claude Code](https://claude.com/product/claude-code), [OpenAI Codex](https://openai.com/codex/), [Google Antigravity](https://antigravity.google/)
- More powerful but more complex to work with
- Systems that can plan, write, and deploy code more autonomously
- You give a prompt, it figures out the rest

## Tokens
AI tools, especially AI agents are not free! Often, using a chatbot there will be a free tier of service which has usage limits. More often than not, AI Agents are not free. Commonly, these usage limits are quantified as **tokens**. Without going too far into details, each time you prompt an AI Chatbot or Agent, you are using tokens for your prompt and also for the response returned to you. Depending on your account level, you'll have a usage limit. Agents use a lot of tokens and often you'll have to be at the "pro" account level or higher to use an agent due to the usage demands of those products. Commonly, the "pro" level is $18 - $20 per month. 

## UVA AI Tools Available
UVA ITS provides an ever-changing list of available AI tools, which are [available here](https://virginia.service-now.com/its?id=itsweb_kb_article&sys_id=dbe41947dbe3f91066d98f38139619db).

----------------------------------------------------------------------------------------------------

### Demo projects
Let's show a few examples of demo projects prompts and walk through them the old way with Chatbots vs the newer way with agents. <i>**Disclaimer:** As of writing this (Summer 2026), unfortunately UVA does not license an AI Agent tool, so all examples shown will be with tools that either cost something or have firm usage limits. </i>


##### Scenario 1: All In One app builder
I will use an all in one service like [Base 44](https://base44.com/) for this example. This is vibe coding at its purest. I don't have to know anything other than what the outcome should look like. All the coding, hosting, etc is handled by the service. 

**Prompt:** Create a web app for me that tells the weather forecast for Charlottesville, VA. Find a free weather API to get the data from. Create a clean user interface with a reddish background.

**Follow Up:**
- Change temperature to Fahrenheit
- Add a box for other city's weather


##### Scenario 2: AI Coding Agent
Agents are much more powerful tools and can do a lot of things. One major difference is that they can interact with the filesystem on your computer to create and manipulate files. You *should* be asked by the Agent for permission to do create, edit, delete files and you can grant permanent access or respond step by step. One of the major limitations of this workshop is that we only have access to the free version of these agents, which limit functionality greatly. This example will at least give you an idea of a use case for agents. 

**Prompt:** Build a Pomodoro / focus timer web app as a single self-contained HTML file 
(index.html) with inline CSS and JavaScript — no external libraries, no CDN 
links, no internet access, no build step, no backend. It should run by just 
opening the file in a browser, and persist data using localStorage only.

Core functionality:
1. A large, clear circular or radial progress timer showing time remaining, 
   with a big MM:SS display in the center.
2. Three modes: "Focus" (default 25 min), "Short Break" (default 5 min), and 
   "Long Break" (default 15 min), switchable via tabs/buttons.
3. Start, Pause, and Reset controls.
4. An audible chime when a session ends.
5. A settings panel (collapsible) letting the user customize the length (in 
   minutes) of each of the three session types, and whether auto-advance is on.


Design:
- Clean, modern, minimal aesthetic. Dark mode by default with a toggle for 
  light mode.
- Smooth color transitions between modes (e.g. a warm color for Focus, a cool 
  color for Break).
- Responsive layout that looks good on both desktop and mobile browser widths.
- Subtle animations: progress ring filling/draining smoothly, gentle pulse or 
  fade when a session completes.
- The browser tab title should update to show the countdown (e.g. "12:34 - 
  Focus") so the user can glance at their tab.

**Follow Up:** 
- Add a text input right beneath the timer where you can type what you are currently focusing on (e.g., "Finish quarterly report").

----------------------------------------------------------------------------------------------------
# Prompt Engineering with the CLEAR Framework
I have taught an [entire workshop on this topic](https://github.com/epurpur/Prompt_Engineering), but I think it is important to state some best practices when prompting AI tools, especially when Vibe Coding with an AI agent (or just a normal chatbot). Because Agents have much more autonomy to make decisions of how to create what you want, it is important to deliver your message correctly. We have an entire framework around prompt engineering, [The CLEAR Framework](https://www.sciencedirect.com/science/article/pii/S0099133323000599), developed by UVA Library Dean Leo Lo. Here is a concise summary of how to interact with an agent. 

| Letter   | Description |
| -------- | ------- |
| C | Concise. Brevity and Clarity in prompts               |
| L | Logical. Structured and coherent prompts              |
| E | Explicit. Clear output specifications                 |
| A | Adaptive. Flexibility and customization in prompts    |
| R | Reflective. Continuous evaluation and improvement of prompts    |

----------------------------------------------------------------------------------------------------

# Best Practices and Caveats. Human Oversight Still Needed!
