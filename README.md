<div align="center">
    <img src="./media/logo_small.webp"/>
    <h1>🌱 Spec Kit</h1>
    <h3><em>Build high-quality software faster.</em></h3>
</div>

<p align="center">
    <strong>An effort to allow organizations to focus on product scenarios rather than writing undifferentiated code with the help of Spec-Driven Development.</strong>
</p>

[![Release](https://github.com/github/spec-kit/actions/workflows/release.yml/badge.svg)](https://github.com/github/spec-kit/actions/workflows/release.yml)

---

## Table of Contents

- [🤔 What is Spec-Driven Development?](#-what-is-spec-driven-development)
- [🏗️ Architecture](#️-architecture)
- [⚡ Get started](#-get-started)
- [🎯 Available commands](#-available-commands)
- [📚 Core philosophy](#-core-philosophy)
- [🌟 Development phases](#-development-phases)
- [🔧 Prerequisites](#-prerequisites)
- [📖 Learn more](#-learn-more)
- [Detailed process](#detailed-process)
- [Troubleshooting](#troubleshooting)

## 🤔 What is Spec-Driven Development?

**Spec-Driven Development** transforms software development from ad-hoc coding into a systematic, specification-driven process. The Spec-Kit provides a comprehensive set of 10 commands that work together in a layered architecture to implement this methodology.

### Core Philosophy

- **Intent-driven development** where specifications define the "_what_" before the "_how_"
- **Executable specifications** that generate working implementations
- **Continuous refinement** through AI-assisted validation and consistency checking
- **Multi-layered integration** supporting gradual adoption and enhancement
- **Collaborative intelligence** through expert systems and agent coordination

## 🏗️ Architecture

The Spec-Kit implements a **4-layer architecture** where each layer builds upon the previous ones:

```text
Layer 4: PACT Coordination (Multi-agent collaboration)
├── /pact command for coordination setup
├── coordination/ directory structure
└── Enhanced collaboration patterns

Layer 3: Expert Systems (Domain guidance)  
├── /expert command for domain expertise
├── experts/ directory for knowledge files
└── Agentic integration patterns

Layer 2: SPARC Methodology (Structured development)
├── /sparc command for systematic approach
├── Phase-by-phase documentation
└── Quality gates and validation

Layer 1: Project Foundation (Discovery & planning)
├── /discover command for comprehensive analysis
├── Foundation documents (BACKLOG.md, IMPLEMENTATION_GUIDE.md, etc.)
└── Market reality validation
```

**Orchestration Layer**: Integrated workflows that coordinate all layers
- `/workflow` for complex development scenarios
- `/sync` for maintaining consistency across systems

## ⚡ Get started

### 1. Install Specify

Initialize your project depending on the coding agent you're using:

```bash
uvx --from git+https://github.com/github/spec-kit.git specify init <PROJECT_NAME>
```

### 2. Choose your approach

**Quick Start (Basic SDD):**
```bash
/specify "Feature description" → /plan "Implementation" → /tasks "Break down work"
```

**Comprehensive Discovery (Recommended):**
```bash
/discover "Project overview" → /specify → /plan → /tasks
```

**Full Integration (Advanced):**
```bash
/workflow --type=feature-development "Feature description"
```

### 3. Progressive adoption

Start simple and add capabilities as needed:

- **Level 1**: Basic SDD workflow (`/specify` → `/plan` → `/tasks`)
- **Level 2**: Foundation-enhanced (`/discover` → basic SDD)
- **Level 3**: Methodology-enhanced (`/sparc` → basic SDD)
- **Level 4**: Expert-guided (`/expert` → basic SDD)
- **Level 5**: Full integration (`/discover` → `/sparc` → `/expert` → `/pact` → SDD)
- **Level 6**: Orchestrated workflows (`/workflow`)

For detailed step-by-step instructions, see our [comprehensive guide](./spec-driven.md).

## 🎯 Available commands

The Spec-Kit provides a comprehensive set of commands that work together in a layered architecture:

### Core SDD Commands (Always Available)

- **`/specify`** - Start new feature by creating specification and feature branch
- **`/plan`** - Plan feature implementation with technical details and architecture  
- **`/tasks`** - Break down plan into executable, numbered tasks with dependencies

### Foundation Commands (Enhanced Project Discovery)

- **`/discover`** - Execute comprehensive project discovery with market reality validation
- **`/enhance`** - Upgrade existing projects with enhanced analysis and codebase extraction

### Methodology Commands (Structured Development)

- **`/sparc`** - Apply SPARC methodology (Specification, Pseudocode, Architecture, Refinement, Completion)

### Expert System Commands (Domain Guidance)

- **`/expert`** - Generate or consult specialized expert context files with agentic integration

### Collaboration Commands (Multi-Agent Coordination)

- **`/pact`** - Implement PACT framework (Planning, Action, Coordination, Testing)

### Orchestration Commands (Integrated Workflows)

- **`/workflow`** - Execute integrated workflow combining multiple methodologies
- **`/sync`** - Update and synchronize expert and memory systems for consistency

### Example Integration Patterns

**New Project Development:**
```bash
/discover "Project overview" → /sparc → /expert → /specify → /plan → /tasks
```

**Feature Development (Enhanced SDD):**
```bash
/specify "Feature description" → /plan "Implementation" → /tasks "Break down work"
```

**Complex Feature Development:**
```bash
/sparc --phase=specification → /specify → /plan → /tasks
```

**Full Integration Workflow:**
```bash
/workflow --type=feature-development "Feature description"
```

## 📚 Core philosophy

Spec-Driven Development with Spec-Kit integration is a structured process that emphasizes:

- **Intent-driven development** where specifications define the "_what_" before the "_how_"
- **Executable specifications** that generate working implementations
- **Continuous refinement** through AI-assisted validation and consistency checking
- **Multi-layered integration** supporting gradual adoption and enhancement
- **Collaborative intelligence** through expert systems and agent coordination
- **Comprehensive project discovery** with brutal market reality validation
- **Structured methodology application** through SPARC (Specification, Pseudocode, Architecture, Refinement, Completion)
- **Expert knowledge integration** providing domain-specific guidance and agentic coordination
- **Multi-agent collaboration** through PACT framework (Planning, Action, Coordination, Testing)

## 🌟 Development phases

| Phase | Focus | Key Activities |
|-------|-------|----------------|
| **0-to-1 Development** ("Greenfield") | Generate from scratch | Start with high-level requirements<br/>Generate specifications<br/>Plan implementation steps<br/>Build production-ready applications |
| **Creative Exploration** | Parallel implementations | Explore diverse solutions<br/>Support multiple technology stacks & architectures<br/>Experiment with UX patterns |
| **Iterative Enhancement** ("Brownfield") | Brownfield modernization | Add features iteratively<br/>Modernize legacy systems<br/>Adapt processes |

## 🎯 Experimental goals

Our research and experimentation focus on:

### Technology independence

- Create applications using diverse technology stacks
- Validate the hypothesis that Spec-Driven Development is a process not tied to specific technologies, programming languages, or frameworks

### Enterprise constraints

- Demonstrate mission-critical application development
- Incorporate organizational constraints (cloud providers, tech stacks, engineering practices)
- Support enterprise design systems and compliance requirements

### User-centric development

- Build applications for different user cohorts and preferences
- Support various development approaches (from vibe-coding to AI-native development)

### Creative & iterative processes

- Validate the concept of parallel implementation exploration
- Provide robust iterative feature development workflows
- Extend processes to handle upgrades and modernization tasks  

## 🔧 Prerequisites

- **Linux/macOS** (or WSL2 on Windows)
- AI coding agent: [Claude Code](https://www.anthropic.com/claude-code), [GitHub Copilot](https://code.visualstudio.com/), or [Gemini CLI](https://github.com/google-gemini/gemini-cli)
- [uv](https://docs.astral.sh/uv/) for package management
- [Python 3.11+](https://www.python.org/downloads/)
- [Git](https://git-scm.com/downloads)

## 📖 Learn more

- **[Complete Spec-Driven Development Methodology](./spec-driven.md)** - Deep dive into the full process
- **[Commands and Features Guide](./src/COMMANDS_AND_FEATURES_GUIDE.md)** - Comprehensive command documentation
- **[Integration Guide](./INTEGRATION_GUIDE.md)** - Comprehensive integration documentation
- **[Detailed Walkthrough](#detailed-process)** - Step-by-step implementation guide

---

## Detailed process

<details>
<summary>Click to expand the detailed step-by-step walkthrough</summary>

You can use the Specify CLI to bootstrap your project, which will bring in the required artifacts in your environment. Run:

```bash
specify init <project_name>
```

Or initialize in the current directory:

```bash
specify init --here
```

![Specify CLI bootstrapping a new project in the terminal](./media/specify_cli.gif)

You will be prompted to select the AI agent you are using. You can also proactively specify it directly in the terminal:

```bash
specify init <project_name> --ai claude
specify init <project_name> --ai gemini
specify init <project_name> --ai copilot
# Or in current directory:
specify init --here --ai claude
```

The CLI will check if you have Claude Code or Gemini CLI installed. If you do not, or you prefer to get the templates without checking for the right tools, use `--ignore-agent-tools` with your command:

```bash
specify init <project_name> --ai claude --ignore-agent-tools
```

### **STEP 1:** Bootstrap the project

Go to the project folder and run your AI agent. In our example, we're using `claude`.

![Bootstrapping Claude Code environment](./media/bootstrap-claude-code.gif)

You will know that things are configured correctly if you see the `/specify`, `/plan`, and `/tasks` commands available.

The first step should be creating a new project scaffolding. Use `/specify` command and then provide the concrete requirements for the project you want to develop.

>[!IMPORTANT]
>Be as explicit as possible about _what_ you are trying to build and _why_. **Do not focus on the tech stack at this point**.

An example prompt:

```text
Develop Taskify, a team productivity platform. It should allow users to create projects, add team members,
assign tasks, comment and move tasks between boards in Kanban style. In this initial phase for this feature,
let's call it "Create Taskify," let's have multiple users but the users will be declared ahead of time, predefined.
I want five users in two different categories, one product manager and four engineers. Let's create three
different sample projects. Let's have the standard Kanban columns for the status of each task, such as "To Do,"
"In Progress," "In Review," and "Done." There will be no login for this application as this is just the very
first testing thing to ensure that our basic features are set up. For each task in the UI for a task card,
you should be able to change the current status of the task between the different columns in the Kanban work board.
You should be able to leave an unlimited number of comments for a particular card. You should be able to, from that task
card, assign one of the valid users. When you first launch Taskify, it's going to give you a list of the five users to pick
from. There will be no password required. When you click on a user, you go into the main view, which displays the list of
projects. When you click on a project, you open the Kanban board for that project. You're going to see the columns.
You'll be able to drag and drop cards back and forth between different columns. You will see any cards that are
assigned to you, the currently logged in user, in a different color from all the other ones, so you can quickly
see yours. You can edit any comments that you make, but you can't edit comments that other people made. You can
delete any comments that you made, but you can't delete comments anybody else made.
```

After this prompt is entered, you should see Claude Code kick off the planning and spec drafting process. Claude Code will also trigger some of the built-in scripts to set up the repository.

Once this step is completed, you should have a new branch created (e.g., `001-create-taskify`), as well as a new specification in the `specs/001-create-taskify` directory.

The produced specification should contain a set of user stories and functional requirements, as defined in the template.

At this stage, your project folder contents should resemble the following:

```text
├── memory
│	 ├── constitution.md
│	 └── constitution_update_checklist.md
├── scripts
│	 ├── check-task-prerequisites.sh
│	 ├── common.sh
│	 ├── create-new-feature.sh
│	 ├── get-feature-paths.sh
│	 ├── setup-plan.sh
│	 └── update-claude-md.sh
├── specs
│	 └── 001-create-taskify
│	     └── spec.md
└── templates
    ├── CLAUDE-template.md
    ├── plan-template.md
    ├── spec-template.md
    └── tasks-template.md
```

### **STEP 2:** Functional specification clarification

With the baseline specification created, you can go ahead and clarify any of the requirements that were not captured properly within the first shot attempt. For example, you could use a prompt like this within the same Claude Code session:

```text
For each sample project or project that you create there should be a variable number of tasks between 5 and 15
tasks for each one randomly distributed into different states of completion. Make sure that there's at least
one task in each stage of completion.
```

You should also ask Claude Code to validate the **Review & Acceptance Checklist**, checking off the things that are validated/pass the requirements, and leave the ones that are not unchecked. The following prompt can be used:

```text
Read the review and acceptance checklist, and check off each item in the checklist if the feature spec meets the criteria. Leave it empty if it does not.
```

It's important to use the interaction with Claude Code as an opportunity to clarify and ask questions around the specification - **do not treat its first attempt as final**.

### **STEP 3:** Generate a plan

You can now be specific about the tech stack and other technical requirements. You can use the `/plan` command that is built into the project template with a prompt like this:

```text
We are going to generate this using .NET Aspire, using Postgres as the database. The frontend should use
Blazor server with drag-and-drop task boards, real-time updates. There should be a REST API created with a projects API,
tasks API, and a notifications API.
```

The output of this step will include a number of implementation detail documents, with your directory tree resembling this:

```text
.
├── CLAUDE.md
├── memory
│	 ├── constitution.md
│	 └── constitution_update_checklist.md
├── scripts
│	 ├── check-task-prerequisites.sh
│	 ├── common.sh
│	 ├── create-new-feature.sh
│	 ├── get-feature-paths.sh
│	 ├── setup-plan.sh
│	 └── update-claude-md.sh
├── specs
│	 └── 001-create-taskify
│	     ├── contracts
│	     │	 ├── api-spec.json
│	     │	 └── signalr-spec.md
│	     ├── data-model.md
│	     ├── plan.md
│	     ├── quickstart.md
│	     ├── research.md
│	     └── spec.md
└── templates
    ├── CLAUDE-template.md
    ├── plan-template.md
    ├── spec-template.md
    └── tasks-template.md
```

Check the `research.md` document to ensure that the right tech stack is used, based on your instructions. You can ask Claude Code to refine it if any of the components stand out, or even have it check the locally-installed version of the platform/framework you want to use (e.g., .NET).

Additionally, you might want to ask Claude Code to research details about the chosen tech stack if it's something that is rapidly changing (e.g., .NET Aspire, JS frameworks), with a prompt like this:

```text
I want you to go through the implementation plan and implementation details, looking for areas that could
benefit from additional research as .NET Aspire is a rapidly changing library. For those areas that you identify that
require further research, I want you to update the research document with additional details about the specific
versions that we are going to be using in this Taskify application and spawn parallel research tasks to clarify
any details using research from the web.
```

During this process, you might find that Claude Code gets stuck researching the wrong thing - you can help nudge it in the right direction with a prompt like this:

```text
I think we need to break this down into a series of steps. First, identify a list of tasks
that you would need to do during implementation that you're not sure of or would benefit
from further research. Write down a list of those tasks. And then for each one of these tasks,
I want you to spin up a separate research task so that the net results is we are researching
all of those very specific tasks in parallel. What I saw you doing was it looks like you were
researching .NET Aspire in general and I don't think that's gonna do much for us in this case.
That's way too untargeted research. The research needs to help you solve a specific targeted question.
```

>[!NOTE]
>Claude Code might be over-eager and add components that you did not ask for. Ask it to clarify the rationale and the source of the change.

### **STEP 4:** Have Claude Code validate the plan

With the plan in place, you should have Claude Code run through it to make sure that there are no missing pieces. You can use a prompt like this:

```text
Now I want you to go and audit the implementation plan and the implementation detail files.
Read through it with an eye on determining whether or not there is a sequence of tasks that you need
to be doing that are obvious from reading this. Because I don't know if there's enough here. For example,
when I look at the core implementation, it would be useful to reference the appropriate places in the implementation
details where it can find the information as it walks through each step in the core implementation or in the refinement.
```

This helps refine the implementation plan and helps you avoid potential blind spots that Claude Code missed in its planning cycle. Once the initial refinement pass is complete, ask Claude Code to go through the checklist once more before you can get to the implementation.

You can also ask Claude Code (if you have the [GitHub CLI](https://docs.github.com/en/github-cli/github-cli) installed) to go ahead and create a pull request from your current branch to `main` with a detailed description, to make sure that the effort is properly tracked.

>[!NOTE]
>Before you have the agent implement it, it's also worth prompting Claude Code to cross-check the details to see if there are any over-engineered pieces (remember - it can be over-eager). If over-engineered components or decisions exist, you can ask Claude Code to resolve them. Ensure that Claude Code follows the [constitution](base/memory/constitution.md) as the foundational piece that it must adhere to when establishing the plan.

### STEP 5: Implementation

Once ready, instruct Claude Code to implement your solution (example path included):

```text
implement specs/002-create-taskify/plan.md
```

Claude Code will spring into action and will start creating the implementation.

>[!IMPORTANT]
>Claude Code will execute local CLI commands (such as `dotnet`) - make sure you have them installed on your machine.

Once the implementation step is done, ask Claude Code to try to run the application and resolve any emerging build errors. If the application runs, but there are _runtime errors_ that are not directly available to Claude Code through CLI logs (e.g., errors rendered in browser logs), copy and paste the error in Claude Code and have it attempt to resolve it.

</details>

---

## Troubleshooting

### Git Credential Manager on Linux

If you're having issues with Git authentication on Linux, you can install Git Credential Manager:

```bash
#!/bin/bash
set -e
echo "Downloading Git Credential Manager v2.6.1..."
wget https://github.com/git-ecosystem/git-credential-manager/releases/download/v2.6.1/gcm-linux_amd64.2.6.1.deb
echo "Installing Git Credential Manager..."
sudo dpkg -i gcm-linux_amd64.2.6.1.deb
echo "Configuring Git to use GCM..."
git config --global credential.helper manager
echo "Cleaning up..."
rm gcm-linux_amd64.2.6.1.deb
```

## Maintainers

- Den Delimarsky ([@localden](https://github.com/localden))
- John Lam ([@jflam](https://github.com/jflam))

## Support

For support, please open a [GitHub issue](https://github.com/github/spec-kit/issues/new). We welcome bug reports, feature requests, and questions about using Spec-Driven Development.

## Acknowledgements

This project is heavily influenced by and based on the work and research of [John Lam](https://github.com/jflam).

## License

This project is licensed under the terms of the MIT open source license. Please refer to the [LICENSE](./LICENSE) file for the full terms.
