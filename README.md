# Todo List

## Features
- Blackboard
  - Persistence
  - Clear blackboard button allowing people to decline the clear if they say so within 10 seconds (like league surrender vote)
  - Undo/redo
- Login & signup buttons in console
- Autogenerated changelog (from git, tags, commits or special commit format)
- JamieDay ETH donation tokens, send ETH to contract, receive JamieDay tokens...

```
What's your username?

\> [username]

What's your password?

\> [password]

Can you type that again please?

\> [password]
```

- Server-sided commands integrated with client-sided ones, command information aggregates server commands & client commands with little UI differentiation

## Architecture

- Command event-sourcing (history)
- Command modularization