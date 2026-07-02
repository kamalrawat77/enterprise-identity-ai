# Day 01 - Foundations
---

## Notes
---

### 1. Claude
- Not only a chatbot but an unbiased thinking partner.
- Can help summarize, creative & collaborative content writing and coding
- Can take directions on persona and is highly steerable and collaborative
- Accessible via various tools, web, app and desktop

__Capabilities__
- Writing and content creation
- Research and Analysis
- Coding Assist
- Problem solving and reasoning
- Learning new things

---

### 2. AI Fluency
1. Delegation - SOD for AI and human
2. Description - Effectively communicating to AI
3. Discernment - Crtically Evaluating AI responses
4. Diligence - Using AI responsibly and ethically/ Evals

__Simple Eval Approach__
- Gather Examples - Task you do regularly
- Create test prompts - for AI to do those tasks
- Compare output - AI <-> Yours
- Refine - Refine until satisfaction

---

### 3. Projects
- Self contained Workspace owning project's 
    - Context
    - Memory
    - Chat History
    - Knowledge Base
    - Custom Instructuions
    - Tone, Behaviours and Output Requirements
 - Scales --> Starts with Context --> Evolves to RAG mode to 10x
 - Enables collaboration accross teams

---

### 4. Artifacts
- Outcomes of chat that can be reused (15+ lines)
    - Docs
    - Code snippets
    - HTML + UI Components
    - Images and Diagrams
- Can be shared and published

---

### 5. Skills
- Skills are packages/folder of instructions, scripts and resources to perform repeatable tasks
- Are of 2 types
    - Anthropic 
        - For Documentation (xlx, docx) etc
    - Custom
        - Specialized workflows
        - Domain specific tasks

#### Enable by 
- Settings>Capabilities>Code execution & File Creation>Toggle
- Skills>Toggle

#### Create custom skills
- New chat - to create skill
- Answer claude questions
- Upload reference materials
- Save skill

#### Project VS Skills
- Projects - Store knowledge
- Skill - Perform tasks

---

### 6. Connectors / Tools
- Transform Claude from AI Assistant to Informed Collaborator which can read information and take action on users behalf
- MCP Powered - Proxy to connect to internal/external apps
- Web & Desktop

#### Process
- Web : Find --> Connect --> Authenticate --> Grant PErmissions --> Test Connection
- Desktop : Claude Desktop --> Connect with local file system

---

### 7. Enterprise Search
- Search within your organisation (Enabled by the org admin/owner)
    - Spans across multiple sources
    - Synthesize information across organisation
- Capabilties and use
    - Getup to speed
    - Policy and process questions
    - R&A
    - Onboarding
    -Performacne & Proect tracking

---

### 8. Research mode for deep dives
- Agentic search
    - Multiple search built on top of each other
    - Explore different angles
- Delivers comprehensive answers
- Extended thinking
- Citations made easy

#### Ideal for tasks
    - Market analysis & competitive research
    - Planning complex projects, like team offsites and project launches

#### Steps
1. Cluade plans approach
2. Conducts multiple searches
3. Synthesize findings
4. Provide Citations

---

### 9. Use Cses by roles
1. __General professional use__ - These use cases apply across many roles and industries.

    - __Generate project status reports__ – Keep stakeholders informed with clear, consistent updates
    - __Analyze patterns in user feedback__ – Extract insights from customer comments and survey responses
    - __Package your brand guidelines in a skill__ – Create a reusable Claude skill that applies your brand standards

2. __Sales__ - Sales professionals can use Claude to accelerate deal preparation, create compelling materials, and stay on top of competitive intelligence.

    - __Build a battle card library__ – Create competitive intelligence resources that help your team win deals
    - __Prepare for sales deals__ – Research prospects and organize your talking points before important meetings
    - __Create sales reports__ – Turn your pipeline data into clear, actionable reports

3. __Marketing__ - Marketers can leverage Claude to analyze performance data and efficiently repurpose content across channels.

    - __Analyze campaign performance__ – Extract insights from campaign metrics to inform your strategy
    - __Adapt content across platforms__ – Efficiently repurpose content for different channels and audiences

4. __Finance__ - Finance professionals can use Claude to build models, draft documents, and make sense of complex spreadsheets.

    - __Build financial models__ – Create and refine financial projections with Claude's help
    - __Draft investment memos__ – Structure and write investment analyses more efficiently
    - __Understand and extend an inherited spreadsheet__ – Decode complex spreadsheets and add new functionality

5. __HR__ - HR teams can use Claude to create better onboarding experiences and documentation.

    - __Create new hire onboarding guides__ – Develop comprehensive onboarding materials tailored to different roles

6. __Legal__ - Legal professionals can use Claude to track complex timelines and manage discovery processes.

    - __Track discovery timelines and analyze patterns__ – Organize case timelines and identify key patterns in legal documents

7. __Research__ - Researchers can use Claude to plan literature reviews and verify data analysis.

    - __Plan your literature review__ – Organize your approach to reviewing academic sources
    - __Verify statistics from raw data__ – Double-check calculations and statistical analyses

---

### 10. Other Tools

| Tool | Best for | Where it runs
|-----------|----------|-------------|
| Claude.ai |	General tasks, research, writing, analysis, file creation |	Web, desktop, and mobile apps|
|Claude Code |	Software development, codebase navigation, git workflows	| Terminal/command line, IDE, or your browser|
|Claude Cowork|	Complex, multi-step tasks: research briefs, document creation, file organization, data analysis|	Desktop (and mobile apps via Dispatch)|
|Claude/Claude Code in Slack|	Team collaboration, meeting prep, quick answers in context|	Slack workspace|
|Claude for Excel|	Spreadsheet analysis, financial modeling, formula debugging	|Microsoft Excel sidebar|
|Claude for PowerPoint|	Slide creation, presentation editing, formatting and design	|Microsoft PowerPoint sidebar|
|Claude for Chrome	|Web research, email management, browser automation	|Chrome browser sidebar|
---

## Questions
---
### What Claude is designed to do.

Claude is Anthropics AI entity powered by powerfull LLM models like Opus and Sonnet, have capabilities to connect with external systems and perform external actions using tool calling and MCP, and connect to external knowledge base using RAG. These capability allow Claude to create AI agents than can perform below tasks:
1. Recieve an action from user
2. Investigate and plan for the actions to be taken by reasoning and breaking down the tasks in smaller chunks.
3. Gather additional evidences or informations by connecting to RAG to make better plan and decision or Call external tools to gather data. This can be performed in loop to reach final plan.
4. Call external tools or MCP to execute the plan.
5. Create seperate Agent for planning or each subtask to implement things in parallel.

---
## What "enterprise AI" means.

Enterprise AI is to use Artificial Intelligence to solve buisness problems. Not a public library but private library built just for the organisation.

### Use Cases
1. Smart helpers
2. Agentic AI
3. Spot fakes
4. Predicting future

## How Claude differs from a simple chatbot.
- Not only a chatbot but an unbiased thinking partner.
- Can help summarize, creative & collaborative content writing and coding
- Can take directions on persona and is highly steerable and collaborative
- Accessible via various tools, web, app and desktop

__Capabilities__
- Writing and content creation
- Research and Analysis
- Coding Assist
- Problem solving and reasoning
- Learning new things

## What a "context window" is.

It is AI's short term memory, amount of tokens a model can remember at one time/chat session. This is a space that holds the prompts, chat history, system rules and AI replies.

## Why safety and reliability matter.

Safety and reliability are required so AI systems do not
- cause harms
- spread false facts
- fail at critical tasks. 
    
Unchecked AI can cost costly real world mistakes, like a chatbot giving bad legal advice.

__What These Terms Mean__
- Safety: The AI follows ethical rules, keeps private data secure, and avoids generating toxic or hateful content. Think of this as the "conscience" of the bot.
- Reliability: The AI gives the same correct answer every time you ask. It does not make things up (hallucinate).

__Why They Matter__
- Trust: People will not use AI if they think it will lie to them or ruin their work.
- Money and Law: Mistakes in fields like medicine, law, or banking can lead to lawsuits or large money losses.
- Hacker Protection: Safe AI stops bad actors from tricking the model into doing illegal things

__How We Fix It__
- Guardrails: These are filters that block bad questions before the AI sees them.
- Checking Facts (RAG): The AI searches a real database for facts instead of guessing from memory.
- Human Training (RLHF): Humans reward the AI when it acts well and correct it when it makes a mistake.