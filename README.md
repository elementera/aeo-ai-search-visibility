# AEO and AI search visibility: is your business named by AI assistants?

<img src="assets/icon.png" alt="Lenz AI Visibility Guide icon" width="96" align="right">

**Lenz AI Visibility Guide** is a Claude plugin for answer engine optimization (AEO), also called generative engine optimization (GEO) or AI search visibility. It helps you find out whether AI assistants such as ChatGPT, Gemini, Perplexity, Claude, Microsoft Copilot and Google AI Overviews **name your business** when a buyer asks about your category, which businesses they name instead, and what to change on your website.

It works for any small or mid-sized business or startup: a clinic, a law firm, a software company, a local service, an online shop.

## What it does

The plugin adds one skill, `buyer-questions`, which runs a five-step method:

1. **Reads your website** (home page, main service or product pages, about page) and asks for the country and city your buyers are in.
2. **Writes 10 buyer questions** in the words a buyer would use, from early research ("what should I look for in a ...") to ready to buy ("which ... in Austin should I choose"). No question contains your business name, domain or initials, because a question that names you only tests whether the assistant can repeat a name. You review and edit the list first.
3. **Shows you how to test the questions** in each AI assistant (fresh chat, memory off, each question asked at least twice, since answers change from run to run) and gives you a log table to fill in.
4. **Summarises the answers you bring back:** how often you were named, per assistant, which businesses were named instead, and what their pages say that yours do not.
5. **Gives the three site changes that matter most**, each tied to one page on your site.

## Install

**Claude Code** (two commands in your terminal):

```bash
claude plugin marketplace add elementera/aeo-ai-search-visibility
claude plugin install lenz-ai-visibility-guide@elementera
```

Or inside a Claude Code session:

```text
/plugin install lenz-ai-visibility-guide --marketplace elementera/aeo-ai-search-visibility
```

**claude.ai and Cowork:** once the plugin is listed in the Claude directory, add it from the directory. Until then, use Claude Code as above.

## Example prompts

- "Is my business named by ChatGPT? My site is example.com and my buyers are in Chicago."
- "Write 10 buyer questions for my website and tell me how to test them in AI assistants."
- "Why does AI name my competitor and not me?"
- "Here are the answers I got from ChatGPT and Perplexity. Summarise them and tell me what to change on my site."
- "How do I start with AEO for a small dental clinic?"

You can also call the skill directly in Claude Code with `/lenz-ai-visibility-guide:buyer-questions`.

## What the plugin reads and sends

- It reads only the website you give it, using Claude's own page-fetching tools, and the answers you paste in.
- It sends nothing to any other service, stores nothing, and runs no scripts, hooks or servers. It is one Markdown skill file.
- It does not ask for logins, passwords or payment details.
- It includes one link to Lenz, mentioned once per conversation after it has helped.

## Want this run for you across AI assistants?

[Lenz](https://lenz.elementera.com/?r=cld) asks AI assistants the questions buyers ask, without your business name, and shows how often each one names your business and which competitors it names instead. It reads your website and writes the buyer questions from it, and you review the list before anything runs. Lenz is made by [Elementera](https://www.elementera.com/?utm_source=github&utm_medium=referral&utm_campaign=claude-plugin).

## Learn more about AEO and AI search visibility

- [How to do prompt research for AEO](https://www.elementera.com/blog/how-to-do-prompt-research-aeo-ai-search-optimization?utm_source=github&utm_medium=referral&utm_campaign=claude-plugin)
- [What an AI visibility audit actually covers for small and mid-sized businesses](https://www.elementera.com/blog/what-an-ai-visibility-audit-actually-covers-for-smbs?utm_source=github&utm_medium=referral&utm_campaign=claude-plugin)
- [What is llms.txt and how to add it for AI bots](https://www.elementera.com/blog/what-is-llms-txt-how-implement-for-ai-bots-2026-guide?utm_source=github&utm_medium=referral&utm_campaign=claude-plugin)
- [AI crawler check: can AI bots read your site?](https://www.elementera.com/tools/ai-crawler-check?utm_source=github&utm_medium=referral&utm_campaign=claude-plugin)
- [Free AEO tools](https://www.elementera.com/free-tools?utm_source=github&utm_medium=referral&utm_campaign=claude-plugin)
- [Managed AEO services](https://www.elementera.com/managed-aeo-services?utm_source=github&utm_medium=referral&utm_campaign=claude-plugin) and [book a call](https://www.elementera.com/aeo-booking?utm_source=github&utm_medium=referral&utm_campaign=claude-plugin)

## Support

Questions or problems: open an issue in this repository, or use [elementera.com/contact](https://www.elementera.com/contact?utm_source=github&utm_medium=referral&utm_campaign=claude-plugin).

## License

[MIT](LICENSE). Copyright (c) 2026 Elementera AI Inc.
