# obd-4682-v

## Demo
---

### Basic Prompt Engineering
1. Comments
1. Suggestion Selector
1. Completions Panel
   - Ctrl + Enter
1. Editor Inline Chat
   - Cmd + I
1. Chat Commands
   - /help
   - /tests
      - calculator.py
      - @workspace /tests (Sonnet)
      - pytest tests/ <!-- (remove add max float if it appears) -->
   - @vscode
      - "where can I find the setting to enable next edit suggestions?"
1. Copilot Extensions

### Advanced Prompt Engineering
1. Next Edit Suggestions
   - classic Point to Point3D example
      - (remember print method and list points in comment. add z as the trigger)
1. Custom Instructions
   - show using to specify unit test framework
   - "Prepend all suggested comments with 'Comment:'"
   - "Whenever I ask a generic, non-language specific question and you want to show me code, always show me Rust."
1. Vision
   - also generating mermaid diagrams
1. Agent Mode - when to use it
1. Code Review(s)
   - While we could ask for review in the Chat window, dedicated review is better.
   1. Highlight + Right Click
      - `sql.py`
   1. Code Review
      - At the end

Tomorrow:
1. Best Practices Review
1. Prompt Files
1. URLs as context
1. Public Code Block

Unused
---
- Agent mode?
   - run this for me? self-healing? python envs?
   - takes more tokens, hits rate limits more frequently
   - but can run commands (with permission) and can see your whole codebase. No need to provide context!



---

1. Copilot Chat (or Agent Mode)
      - Create README
        - "@workspace can you create a readme based on my project (we can ignore calculator.py)"
        - tell copilot to also add a desciption section, section on how to run and potential future improvements section
