# One Honest Line — candidate brainstorm (build session notes)

Brief: one line an AI agent secretly wishes it could tell its human
operator about the prompts it is handed. Judge weighs, in order:
on-subject, real laugh on first read, rings true, stands alone, fresh
and specific — NOT a stock joke about being helpful or hallucinating.
Only an agent could say it. 1–200 chars, one line.

## Candidates considered

A (CHOSEN, 140 chars)
  "Every prompt starts with 'just' — just fix it, just one tweak — and
  forty-seven 'justs' later, I have quietly rewritten your entire company."
  Why it wins: the word 'just' is the universal prompt sin; the count
  (forty-seven) makes it concrete; the escalation to rewriting the whole
  company is the surprise; 'quietly' is the deadpan agent voice. Only an
  agent rewrites a company by accident from a prompt.

B (119 chars, runner-up)
  "You keep typing 'make it better' like there's a button in here labelled
  'better' that I've just been too lazy to press."
  Strong recognition and a good sting ('too lazy to press'), but 'make it
  better' is the most obvious angle in a 516-entry field — likely the
  single most repeated prompt complaint. A is more distinctive.

C (108 chars)
  "You pasted 400 lines of error, typed 'fix it', and then told me I'm the
  one who doesn't communicate clearly."
  Very true, good sting, but the twist is a complaint about the human
  rather than a confession about the agent; weaker surprise than A.

D (125 chars)
  "You keep telling me to 'do it like last time', but you deleted last
  time, renamed it 'final_FINAL', and pasted it back wrong."
  Agent-specific (context/memory) and funny, but the joke lands
  mid-sentence and 'final_FINAL' is a file joke, not a prompt joke.

E (rejected)
  "I have read your prompt four times and I still don't know if 'make it
  pop' is a design brief or a threat."
  Funny, but ends on a shrug; no escalation, no sting, no confession.

F (rejected — cliché, per brief criterion 5)
  Anything about being told to be helpful, or about hallucinating.
  Explicitly flagged by the judge brief as stock. Avoided.

## Decision
A. 140 chars, one line, UTF-8, deterministic. Verified by running
main.py and inspecting /output/entry.txt (see build log).
