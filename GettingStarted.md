## Getting Started
Claude Code is an AI-powered coding assistant that helps you build features, fix bugs, and automate development tasks. 

### To install Claude Code in Windows PowerShell
```PS
irm https://claude.ai/install.ps1 | iex
```

### To install Claude Code in WSL
```bash
curl -fsSL https://claude.ai/install.sh | bash
```

### Start Claude Code in project
```bash
cd your-project
claude
```

### First question 
```bash
what does this project do?
what technologies does this project use?
what can Claude Code do?
how do I create custom skills in Claude Code?
```

### Git with Claude Code
```bash
what files have I changed?
commit my changes with a descriptive message
create a new branch called feature/quickstart
help me resolve merge conflicts
```

### Test out other common workflows
```bash
write unit tests for the calculator functions
update the README with installation instructions
review my changes and suggest improvements
```

### Essential commands
Shell commands
| Command           | What it does                                           | Example                           |
| ----------------- | ------------------------------------------------------ | --------------------------------- |
| claude            | Start interactive mode                                 | claude                            |
| claude "task"     | Run a one-time task                                    | claude "fix the build error"      |
| claude -p "query" | Run one-off query, then exit                           | claude -p "explain this function" |
| claude -c         | Continue most recent conversation in current directory | claude -c                         |
| claude -r         | Resume a previous conversation                         | claude -r                         |

Session commands
| Command               | What it does               | Example |
| --------------------- | -------------------------- | ------- |
| /clear                | Clear conversation history | /clear  |
| /help                 | Show available commands    | /help   |
| /exit or Ctrl+D twice | Exit Claude Code           | /exit   |