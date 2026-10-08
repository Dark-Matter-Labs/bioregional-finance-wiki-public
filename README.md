# Bioregional Finance Wiki: use it with your AI

This is a shared knowledge base on bioregional finance. It covers how money reaches
bioregions, the instruments and institutions that carry it, and what has worked so far.
Dark Matter Labs and partner organisations keep it.

Anyone can read it, with any AI. It has 0 public page(s). The latest page
change is from not yet.

**Address:** https://dark-matter-labs.github.io/bioregional-finance-wiki-public/

## Three ways to use it

### 1. Ask your AI (no setup)

This works in ChatGPT, Claude, Gemini, Perplexity and most other chat assistants.
Copy this prompt and add your question at the end:

```text
Read https://dark-matter-labs.github.io/bioregional-finance-wiki-public/llms-full.txt. It is the Bioregional Finance Wiki.
Answer my question from it. Cite the page title for each claim.
Say clearly when the wiki does not cover something.

My question:
```

Some assistants cannot open links. If yours cannot:

1. Download [llms-full.txt](https://dark-matter-labs.github.io/bioregional-finance-wiki-public/llms-full.txt).
2. Attach the file to your chat.
3. Use the same prompt.

### 2. Work with it in a coding agent

Use this way for deeper work in Claude Code, Cursor, Codex or a similar tool.

1. Download the wiki: `git clone https://github.com/dark-matter-labs/bioregional-finance-wiki-public`
2. Open the folder in your agent.
3. Ask your question. The agent reads `AGENTS.md` first and follows it.

### 3. Connect a tool of your own

- [llms.txt](https://dark-matter-labs.github.io/bioregional-finance-wiki-public/llms.txt) is a map of every page, in the format most AI tools expect.
- [llms-full.txt](https://dark-matter-labs.github.io/bioregional-finance-wiki-public/llms-full.txt) holds every page in one file.
- Each page is a separate markdown file at `https://dark-matter-labs.github.io/bioregional-finance-wiki-public/wiki/<page>.md`.

## How to read an answer

Each page states two things about itself:

- **`confidence`**: how well its sources support it. `low` often means one source.
- **`validation`**: who has stood behind it. `machine` means an AI wrote it and no person
  has confirmed it yet. `self`, `peer` and `collective` mean people have reviewed it.

Treat an answer as good as the pages under it. Check the cited page before you rely on it.

## Reading and changing the wiki

- **Anyone can read** everything here.
- **Nobody edits this copy directly.** It is rebuilt from the working wiki, so direct edits disappear.
- **To suggest a source or a correction**, email leon@darkmatterlabs.org.

The wiki is selective on purpose. It looks for approaches that change how finance works,
not only ones that improve it. Not every suggestion is added. See [CONTRIBUTING.md](CONTRIBUTING.md).

## Licence

The content is licensed [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
You may share and adapt it, including for commercial use. Give credit and share your
adaptations under the same licence. Credit it as:

> Bioregional Finance Wiki, Dark Matter Labs and contributors, https://dark-matter-labs.github.io/bioregional-finance-wiki-public/, CC BY-SA 4.0

## Privacy

This site has no tracking and no cookies. Your questions go to your own AI provider, not to us.
