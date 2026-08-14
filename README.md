# Vibe Coding & AI Agents Workshop

```
Last updated 08/15/26
```

## **About Me**

### Link to recording of this workshop
- [View on PanOpto](https://nordvpn.com/link-checker/?srsltid=AfmBOopGtI-Joz1fRqE3V95zwog7rcU8HOFdvsICTwQM3tMMqkyYSTWo)
- [View on Youtube](https://nordvpn.com/link-checker/?srsltid=AfmBOopGtI-Joz1fRqE3V95zwog7rcU8HOFdvsICTwQM3tMMqkyYSTWo)


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
Vibe Coding is programming or software development assisted by AI where the human describes a project or task in a prompt to a Large Language Model (LLM), which generates source code. The human then reviews and refines the code to ensure accuracy and security. In traditional programming, you are responsible for translating your idea into code, thinking about the structure, syntax, and implementation. In vibe coding, the translation step is handled for you. The gap between having an idea and building it out is removed, or substantially shortened. 

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

### My favorite definition
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
- Systems tha tcan plan, write, and deploy code more autonomously
- You give a prompt, it figures out the rest

## Tokens
AI tools, especially AI agents are not free! Often, using a chatbot there will be a free tier of service which has usage limits. More often than not, AI Agents are not free. Commonly, these usage limits are quantified as **tokens**. Without going too far into details, each time you prompt an AI Chatbot or Agent, you are using tokens for your prompt and also for the response returned to you. Depending on your account level, you'll have a usage limit. Agents use a lot of tokens and often you'll have to be at the "pro" account level or higher to use an agent due to the usage demands of those products. Commonly, the "pro" level is $18 - $20 per month. 

----------------------------------------------------------------------------------------------------

### Demo projects
Let's show a few examples of demo projects prompts and walk through them the old way with Chatbots vs the newer way with agents. **Disclaimer:** As of writing this (Summer 2026), unfortunately UVA does not license an AI Agent tool, so all examples shown will be with tools that either cost something or have firm usage limits. 

##### Sample Prompts
- I am a reference librarian at the University of Virginia. In the reference desk virtual chat, I routinely answer common questions that are easily googled and am hoping to offload some of that to a bot so that I can focus my efforts on more time consuming reference questions which require deep research. Create a chatbot feature to answer common questions such as "When is the library open?", "Can I use the library even if I am not a student?", "When are my books due?". Use the [UVA Library website](https://library.virginia.edu/) as your source of documentation for these answers. For the UI features, I want to use a [University of Virginia color scheme](https://brand.virginia.edu/design-assets/colors). 
- I want to create an affordable housing dashboard for the City of Charlottesville. I have [this](https://opendata.charlottesville.org/datasets/320d465ddf0d498796da6491e21f6dde_43/explore) dataset for tax parcels in the city and [this](https://opendata.charlottesville.org/datasets/c371ad0b81024822bad1147ff6bb24c4_50/explore?location=38.029000%2C-78.477000%2C12) data for city neighborhoods. I want a dashboard with median property value prices by neighborhood. I also want an interactive feature where you can input your yearly income and will determine which neighborhoods you can live in the city. Let's use a simple calculation for home affordability of 3x your annual income for a home. For the UI features, I want to use a [University of Virginia color scheme](https://brand.virginia.edu/design-assets/colors). 
- I like to go to the gym and want to create a workout tracker to log my workouts and also to help me predict what my next workout should be based on previous workouts and other related data points. In this app, I first want a section that allows me to input my workout and record sets, reps, weights, and any other relevant notes. Then I want a section each day to include my other data like general recovery, sleep, stress levels, and diet. The diet section should have inputs for the 3 major macronutrients: Carbohydrates, Protein, Fats. Find information sources that help calculate workout recover time. Tell me what those sources are and let me verify them. Based on all the information I have entered, predict my recovery level for the next day, which will help me determine when to work out again. For the UI, use a clean looking library such as [GetUIKit](https://getuikit.com/).

----------------------------------------------------------------------------------------------------
# Prompt Engineering with the CLEAR Framework
I have taught an [entire workshop on this topic](https://github.com/epurpur/Prompt_Engineering), but I think it is important to state some best practices when prompting AI tools, especially agents. Because Agents have much more autonomy to make decisions of how to create what you want, it is important to deliver your message correctly. We have an entire framework around prompt engineering, [The CLEAR Framework](https://www.sciencedirect.com/science/article/pii/S0099133323000599), developed by UVA Library Dean Leo Lo. Here is a concise summary of how to interact with an agent. 

| Letter   | Description |
| -------- | ------- |
| C | Concise. Brevity and Clarity in prompts               |
| L | Logical. Structured and coherent prompts              |
| E | Explicit. Clear output specifications                 |
| A | Adaptive. Flexibility and customization in prompts    |
| R | Reflective. Continuous evaluation and improvement of prompts    |

----------------------------------------------------------------------------------------------------

# Best Practices and Caveats. Human Oversight Still Needed!
