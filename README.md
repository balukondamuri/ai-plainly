# AI, Plainly

**Learn AI from prompting to orchestration, explained through everyday life.**

AI, Plainly is a free, self-paced course that teaches how modern AI systems work using situations you already know. The default analogy is a restaurant kitchen. Prompts are order tickets, RAG is a recipe book, agents are chefs, and hooks are the kitchen inspector. You can switch to a different everyday analogy, or pick "Technical" to learn with no analogy at all.

👉 **Live site:** `https://balukondamuri.github.io/ai-plainly`

---

## What you'll learn

The course has 14 short lessons (about 3–5 minutes each) grouped into five stages.

| Stage | Topic | Lessons |
|---|---|---|
| 1 | **Prompting** | What is an LLM? · What is a prompt? · Good vs. bad prompts |
| 2 | **RAG** | What is RAG? · How the AI finds the right page · Answering from the book |
| 3 | **Agents** | What is an agent? · Tools: how an agent acts · The harness |
| 4 | **Extending agents** | CLAUDE.md: the house rules · Skills: recipe cards in a drawer · Hooks: the kitchen inspector · Subagents: the sous-chefs |
| 5 | **Teams of agents** | Orchestration: five ways to run a kitchen (chaining, routing, parallelization, orchestrator-workers, evaluator-optimizer) |

Each lesson includes illustrations, worked examples, a short recap, a "check yourself" quiz, and an interview-style Q&A.

## Interactive tools

- **Prompt Playground**: run a weak prompt and a strong prompt side by side and compare the results.
- **Ask the Course**: watch RAG find the right recipe cards and answer with sources.
- **Kitchen Agent**: watch an agent use tools step by step and approve its orders.
- **Which One Fits?**: practise picking the right building block or pattern for a real situation.

## Pick your analogy

Each lesson can be told through a different part of everyday life:

Restaurant (default) · Running a home · Workout · Driving · Yard and lawn care · Shopping and style · New job at an office · Sports team · Technical (no analogy)

The ready-made analogies are written in advance, so they open instantly.

## Features

- **Single file, no build step**: everything (styles, scripts and inline SVG illustrations) lives in `docs/index.html`.
- **Light and dark mode**: follows your system setting, and each analogy has its own color theme.
- **Progress tracking**: completed lessons and your preferences are saved in your browser's `localStorage`. Nothing is sent to a server.
- **Mobile friendly**: responsive layout that works down to phone width.
- **Accessible typography**: uses Atkinson Hyperlegible for body text.

## Project structure

```
ai-plainly/
├── docs/
│   └── index.html   # the entire site
└── README.md
```

## Deploying to GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
4. Choose your branch (e.g. `main`) and the **`/docs`** folder, then click **Save**.
5. After a minute or two, the site will be live at `https://<your-username>.github.io/<repo-name>/`.

## Running locally

No install is needed. Open `docs/index.html` in a browser, or serve the folder:

```bash
cd docs
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Contributing

Corrections, new analogies and lesson ideas are welcome. Open an issue or a pull request.
