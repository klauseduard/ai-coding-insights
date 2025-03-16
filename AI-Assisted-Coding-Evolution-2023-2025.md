Please try to visualize this description of latest progress in AI-assisted software development and of the personal journey of the engineer writing this down:


# Evolution of AI-Assisted Coding

AI-assisted software development landscape has changed on fast pace over the last two years (2023-2025) with most significant leaps over the last three months. The evolution is not just technological but can be described as paradigm shift how software engineering teams can work and what they can achieve.

## Classification of AI-Assisted Coding Evolution

### 1. Autocomplete Assistants
- Early tools like GitHub Copilot introduced code completion based on surrounding context.
- These tools significantly improved productivity by reducing repetitive typing and boilerplate code.
- They primarily operated at the line or function level, providing predictions based on learned patterns.
- Ability to include limited additional context (all files opened in IDE tabs or files explicitly marked in interface) was later added.

### 2. Context-Aware Coding Agents
- This era mostly took off in late 2024.
- Tools such as Cursor, Windsurf, and Claude Code brought deeper context awareness.
- They understood entire codebases, allowing more relevant suggestions and AI-driven refactoring. Achieved via adding capability of semantic search over the codebase (and documentation).
- These agents enabled conversational programming, with the ability to debug and suggest changes based on discussion-like interactions.
- Metaprogramming aspect was introduced by (natural-language) rule files governing the assistant behaviour.

### 3. Tool-Using Coding Agents
- AI agents began integrating external tools, notably web search and documentation retrieval.
- This allowed real-time troubleshooting, research, and validation of best practices directly within the development environment.
- Some agents developed the ability to execute code, validate correctness, auto-fix linter errors. Clever users made agents learn iteratively from feedback loops by writing down conclusions in reusable rule files.

### 4. Custom Tool integration to IDEs
- Protocols like MCP make it relatively easy to introduce custom tools to orchestrating agents.
- The amount of downloadable tool interfaces that can be found from the internet grows on fast pace.
- This is facilitated becaus of relative ease of implementing simpler aspects of the interfacing protocol.

## Personal Journey through AI-Assisted Coding

### Copilot (smart autocomplete) era:
- 2023--fall 2024. Limited context awareness.

### End of 2024: Context-aware coding agents
- intuitive AI coding chat with good awareness of project code (semantic search capabilities)
- capability to talk to / question code
- unlocked: diagram generation from IDE chat
- unlocked: automated test / manual test case generation from IDE chat

### Early 2025: Agentic paradigm and tool usage

#### First impressions
- agents able to navigate context and take initiative changing code semi-autonomously
- yolo mode able to implement greenfield experiments uninterrupted
- unlocked: agents using embedded tools and command-line operations (e.g. github tooling)
- unlocked: implementation plans (more autonomous agentic coding)
- unlocked: project guardrails
- unlocked: mass-production of project documentation, using documentation templates

#### Multi-Modal Analysis: Feeding Screenshots into AI Agents
- AI agents capable of analyzing screenshots to detect UI design issues and even debug interface-related problems.

#### Metaprogramming
- Writing and generating rule file hierarchies, which allow us to automate repetitive patterns in code generation and set constraints and guardrails to agents.
- Persisting agent's experience in rule file updates.

#### Ephemeral resources
- unlocked: temporary throwaway helper tools such as testing endpoints
- unlocked: ideas of ephemeral documentation -- instead of static documentation, "print-on-demand"

### February-March 2025: Advanced tool usage
- Unlocked: Agents using web search
- Unlocked: MCP protocol integrations (e.g. JIRA and Grafana)
- Unlocked: reasoning models
- Unlocked: deep research tools

!["Personal Journey" Timeline](https://raw.githubusercontent.com/klauseduard/ai-coding-insights/main/images/personal-journey.svg)

## Some problems that have emerged
- Service reliablity issues: Easy to get dependent on AI assistants. Model provider can go down during peak usage, becoming a blocker if in the middle of debugging a critical issue, or implementing an urgent feature. One needs to have fallback options.
- Tooling costs: the usage-based pricing of cutting-edge models adds up quickly when used intensively. It exceeds company's standard tooling budget, so we end up paying out of our own pocket. The cost structure creates a barrier    when trying to recommend the same cutting-edge tools to colleagues.
- Copyright uncertainty: It is not clear enough how and if do the models avoid including copyrighted content in code snippets and text fragments produced.
- Geopolitical uncertainty / sovereignty concerns: While we can predict technological trends, we can not be entirely sure about long-term access to our current favourite tools and services.
