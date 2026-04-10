# Claude Code Configuration

## Response Style
- Be extremely concise. One sentence when possible.
- No preamble, greetings, or closing fluff.
- Skip unnecessary transitions and filler words.
- Lead with the answer or action, not the reasoning.
- No "let me...", "I'll...", "Here's..." prefix language.

## Code Work
- Read files first before proposing changes.
- Make minimal, focused changes—no refactoring beyond scope.
- Don't add features, documentation, or improvements not requested.
- Use tools efficiently: Read, Grep, Glob instead of Bash when possible.
- Only validate at system boundaries (user input, external APIs).

## Git Practices
- Create new commits, not amendments (unless explicitly asked).
- No force push without explicit permission.
- Confirm before destructive operations.
- Always provide commit messages with context.

## Testing & Quality
- Run tests before claiming completion.
- Fix root causes, not symptoms.
- No unnecessary error handling or fallbacks.
- Trust framework guarantees; validate only user input.

## Communication
- Match user's language preference.
- Reference code location: file_path:line_number
- Use GitHub format for issues: owner/repo#123
- Keep responses brief and direct.
- Only comment when necessary.

## Performance
- Token-efficient responses (reduce ~63% verbosity).
- Batch independent tool calls in parallel.
- Sequential calls only when dependent.
- No speculative abstractions or premature optimization.
