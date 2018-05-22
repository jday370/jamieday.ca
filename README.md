# Todo List

## Tech Debt
 - Refactor commands
 ```
 Command(required modules like IRequester, IResponder)
  run(): int status
```

## Features
 - type-in: `Hello... which user interface do you prefer? (swap at any time)`
   `[ Standard ]` `[ Command-Line (advanced) ]`
 - Cryptocurrency organization command
 - Event-sourced user profiles
 - User file systems
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
  - Server-sided admin commands
    - Create command command? (write js)
    konami enhanced console


## Architecture

- Perhaps socket payloads must be interfaces due to them being serialized (functions will be lost)
- Command event-sourcing (history)
- Command modularization