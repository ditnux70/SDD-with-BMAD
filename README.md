<a href="https://www.packtpub.com/en-us/unlock"><img src="https://drive.google.com/uc?export=view&id=1lQCTQQ8iV5pGuPA1n5wuds-3pwJi0OD_"></a>
<h1 align="center">
Spec-Driven Development with BMAD, First Edition</h1>
<p align="center">This is the code repository for <a href ="https://www.packtpub.com/en-us/product/spec-driven-development-with-bmad-first-edition/9781808086076"> Spec-Driven Development with BMAD, First Edition</a>, published by Packt.
</p>

<h2 align="center">
Master Agentic Workflows using Cursor, BMAD, and Context Engineering
</h2>
<p align="center">
Marlon Vidal Ferreira</p>

<p align="center">
  <a href="https://packt.link/free-ebook/9781808086076"><img width="32px" alt="Free PDF" title="Free PDF" src="https://cdn-icons-png.flaticon.com/512/4726/4726010.png"/></a>
 &#8287;&#8287;&#8287;&#8287;&#8287;
  <a href="https://packt.link/gbp/9781808086076"><img width="32px" alt="Graphic Bundle" title="Graphic Bundle" src="https://cdn-icons-png.flaticon.com/512/2659/2659360.png"/></a>
  &#8287;&#8287;&#8287;&#8287;&#8287;
   <a href="https://www.amazon.com/Spec-Driven-Development-BMAD-Workflows-Engineering/dp/1808086074/"><img width="32px" alt="Amazon" title="Get your copy" src="https://cdn-icons-png.flaticon.com/512/15466/15466027.png"/></a>
  &#8287;&#8287;&#8287;&#8287;&#8287;
</p>
<details open> 
  <summary><h2>About the book</summary>
<a href="https://www.packtpub.com/en-us/product/spec-driven-development-with-bmad-first-edition/9781808086076">
<img src="https://content.packt.com/B39292/cover_image_small.jpg" alt="Spec-Driven Development with BMAD, First Edition" height="256px" align="right">
</a>

Most developers using AI assistants struggle not because of the tool, but because of poor context. When agents receive vague instructions, they produce unreliable code. Spec-Driven Development (SDD) solves this by requiring structured specifications before a single line of code is written.

BMAD is an open-source agentic framework that organizes development into two phases: upstream (analysis, planning, and solutioning) and downstream (implementation and testing). Each phase is handled by specialized AI agents working in sequence, with clear inputs and outputs.

You'll learn how BMAD v6 extends earlier versions through concepts such as Progressive Disclosure, improved context management, TEA integration, and the project-context.md file, which provides a persistent source of truth throughout development. You'll build complete features by orchestrating multiple agents and workflows, applying BMAD to both existing codebases and greenfield projects while running full sprint cycles from planning through implementation and retrospective.

By the end, you'll have a repeatable, structured process for building software with AI that produces consistent, production-ready results regardless of project size or complexity.
</details>

<details open> 
  <summary><h2>Key learnings</summary>
<ul>

<li>Master BMAD's upstream-to-downstream agentic workflow</li>

<li>Use Analyst, PM, and Architect agents to create specs</li>

<li>Implement and test code using the Dev and QA agents</li>

<li>Plan sprints and perform retrospectives with the Scrum Master agent</li>

<li>Build new projects end-to-end using the full BMAD cycle</li>

<li>Work with existing codebases for small and complex features</li>

<li>Engineer AI context with architecture docs and project-context.md</li>

<li>Run ATDD, Automate and Test Design using TEA module</li>

</ul>

  </details>

  <details open> 
  <summary><h2>Chapters</summary>
     <img src="https://cliply.co/wp-content/uploads/2020/02/372002150_DOCUMENTS_400px.gif" alt="Unity Cookbook, Fifth Edition" height="556px" align="right">
<ol>

  <li>Introducing Spec Driven Development and BMAD Method</li>

  <li>Upstream Phase: Analysis, Planning and Solutioning</li>

  <li>Downstream Phase: Implementing and Sprinting</li>

  <li>Applying BMAD to an Existing Project</li>

  <li>Applying BMAD to a New Project</li>

  <li>BMAD in Practice: Answers to Real-World Questions</li>

</ol>

</details>

<details open> 
  <summary><h2>Requirements for this book</summary>

The examples in this book use Cursor as the primary AI-powered IDE. Cursor was chosen because it offers tight integration between the editor and the model, and because it reflects how many developers are currently working with AI tools in practice. If you prefer a different environment, the method translates directly. VS Code, Windsurf, or any other AI-native editor will work. The BMAD artifacts are plain-text files. The agents are prompts. The process does not depend on any particular tool.</br>
Software engineering experience is helpful but not required. You will encounter code in the implementation chapters, and familiarity with at least one programming language will help you follow along more closely. That said, the core of what BMAD teaches happens before the
code is written: how to define the problem, how to structure the solution, and how to give an AI model the context it needs to do useful work. Those skills transfer regardless of your technical background.</br>
Before you start, you will need access to an AI-powered IDE and an active subscription or API key for a capable model, such as Anthropic Claude, OpenAI GPT, or Cursor Composer. The book does not cover model selection in depth, but any model capable of maintaining context and
generating code will be sufficient.

# Welcome to your Lovable project

## Project info

**URL**: https://hour-zen-board.lovable.app/

## How can I edit this code?

There are several ways of editing your application.

**Use Lovable**

Simply visit the [Lovable Project](https://lovable.dev/projects/REPLACE_WITH_PROJECT_ID) and start prompting.

Changes made via Lovable will be committed automatically to this repo.

**Use your preferred IDE**

If you want to work locally using your own IDE, you can clone this repo and push changes. Pushed changes will also be reflected in Lovable.

The only requirement is having Node.js & npm installed - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

Follow these steps:

```sh
# Step 1: Clone the repository using the project's Git URL.
git clone <YOUR_GIT_URL>

# Step 2: Navigate to the project directory.
cd <YOUR_PROJECT_NAME>

# Step 3: Install the necessary dependencies.
npm i

# Step 4: Start the development server with auto-reloading and an instant preview.
npm run dev
```

**Edit a file directly in GitHub**

- Navigate to the desired file(s).
- Click the "Edit" button (pencil icon) at the top right of the file view.
- Make your changes and commit the changes.

**Use GitHub Codespaces**

- Navigate to the main page of your repository.
- Click on the "Code" button (green button) near the top right.
- Select the "Codespaces" tab.
- Click on "New codespace" to launch a new Codespace environment.
- Edit files directly within the Codespace and commit and push your changes once you're done.

## What technologies are used for this project?

This project is built with:

- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS

## How can I deploy this project?

Simply open [Lovable](https://lovable.dev/projects/REPLACE_WITH_PROJECT_ID) and click on Share -> Publish.

## Can I connect a custom domain to my Lovable project?

Yes, you can!

To connect a domain, navigate to Project > Settings > Domains and click Connect Domain.

Read more here: [Setting up a custom domain](https://docs.lovable.dev/features/custom-domain#custom-domain)
</details>

<details> 
  <summary><h2>Get to know the author</h2></summary>

_Marlon Vidal Ferreira_ is a technology executive with a 15-year career and more than 7 years of experience in digital marketing, a unique combination of technical expertise and business vision. He is currently an Engineering Manager at TELUS Digital, an official Cursor
Ambassador in Brazil for the cities of Belo Horizonte, MG, and Porto Alegre, RS, and the owner of a digital marketing agency focused on online advertising.</br>
His career includes stints at companies such as Banco BS2, Avenue Code, Gap, Fanatics, BMG Money, Grupo Fácil, Minds Digital, and Grupo Boticário, progressing from developer to Head of Technology. Along the way, he also founded two companies, further strengthening his
entrepreneurial vision.
</details>

<details> 
  <summary><h2>Other related books</h2></summary>
<ul>

  <li><a href="https://www.packtpub.com/en-us/product/agentic-coding-with-claude-code-first-edition/9781806022595">Agentic Coding with Claude Code, First Edition</a></li>

  <li><a href="https://www.packtpub.com/en-us/product/web-dev-with-an-ai-sidekick-first-edition/9781806111251">Web Dev with an AI Sidekick, First Edition</a></li>
 
</ul>

</details>
