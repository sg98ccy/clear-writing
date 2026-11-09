# Clear Writing

Help readers grasp the main point on first reading, picture what you mean, and follow how the explanation develops.

This agent skill supports drafting, revision, and editorial review. It aims to reduce the reader's effort while preserving your meaning, voice, evidence, and important qualifications. A longer explanation can be clearer when it supplies context the reader needs.

## What it helps with

- Put the main message where readers can find it.
- Replace vague abstractions with concrete people, actions, and outcomes.
- Introduce unfamiliar ideas in plain language before naming the technical term.
- Organize explanations, instructions, reports, research writing, and interface text.
- Connect paragraphs and sections, explain consequential choices, and relate findings to their meaning.
- Use images, diagrams, video, or animation when they explain an idea more directly.

The guidance adapts to the audience and format. It sets no fixed narrative template, word count, reading grade, sentence length, or required number of examples or visuals. Research-writing examples show how context, rationale, and continuity can work together without prescribing a paper structure.

## Use with your AI agent

This skill uses the open [Agent Skills format](https://agentskills.io/home): Markdown instructions with supporting files. **The skill itself requires no Node.js or npx.** Use it with an agent that supports skills, or provide the instructions directly to an agent that can read them.

### Manual setup

1. [Download this repository as a ZIP](https://github.com/sg98ccy/clear-writing/archive/refs/heads/main.zip) and extract it, or clone the repository.
2. Copy `SKILL.md` with its supporting files and folders into a folder named `clear-writing` in your agent's skills directory. Keep the relative file structure intact.
3. Open your project with the agent and try a prompt below.

Common project-level locations are:

| Agent | Skill folder in your project |
| --- | --- |
| [Claude Code](https://code.claude.com/docs/en/skills) | `.claude/skills/clear-writing/` |
| [Cursor](https://cursor.com/docs/skills) | `.cursor/skills/clear-writing/` |
| [GitHub Copilot](https://docs.github.com/en/copilot/concepts/customizations/agent-skills) | `.github/skills/clear-writing/` |
| [OpenCode](https://opencode.ai/docs/skills/) | `.opencode/skills/clear-writing/` |
| [Codex](https://learn.chatgpt.com/docs/build-skills) | `.agents/skills/clear-writing/` |

Follow your agent's linked documentation for other locations or hosted setups. For an agent without native skill discovery, attach or provide [SKILL.md](SKILL.md) and any supporting files it needs, then explicitly ask it to apply the guidance.

<details>
<summary>Optional: install with the Skills CLI</summary>

The [Skills CLI](https://github.com/vercel-labs/skills) can copy the skill into supported agents' directories. **This optional installation method requires Node.js with npx** and network access.

Run from your target project and use the installer to select your agent:

```sh
npx --yes skills@latest add https://github.com/sg98ccy/clear-writing --skill clear-writing
```

On Windows PowerShell, use `npx.cmd` if your execution policy blocks `npx`.

</details>

## Try it

Provide the text and enough context to identify its readers and purpose:

```text
Use the clear-writing skill to revise this explanation for someone seeing
the product for the first time. Make the actions easy to picture and suggest
a visual if it would help. Keep the meaning and the current tone.
```

For research writing:

```text
Use the clear-writing skill to improve the flow of this discussion section.
Preserve the findings, numbers, citations, and uncertainty.
```

Discovery and invocation depend on your agent. Use its skill selector or mention syntax when available. For example, Codex supports `$clear-writing` ([guide](https://learn.chatgpt.com/docs/build-skills)); the prompts above use plain language so you can adapt them to your agent.

## A small example

For instructions to someone reviewing a route before departure:

| Dense wording | Clearer wording |
| --- | --- |
| The interface supports the assessment and modification of route segments in relation to limited sunlight before departure. | Check your route before departure. Revise any sections with limited sunlight. |

The revision makes the action and timing explicit. Different audiences and document types may call for a different approach. More examples are in [references/examples.md](references/examples.md).

## Work with visuals

The agent can use suitable online material, reuse or adapt existing assets, create original visuals with available tools, or combine these approaches. The choice follows the explanation and the reader's needs, with appropriate source attribution and usage rights.

Useful media also needs enough context to be understood: labels, captions, text alternatives, or suitable playback controls where relevant. If a visual is only proposed, the agent should describe it as a proposal.

Read [SKILL.md](SKILL.md) for the full guidance and its sources, including W3C, GOV.UK, and CDC references. [agents/openai.yaml](agents/openai.yaml) contains optional display and invocation metadata for OpenAI tools.

## Update or customize

Edit [SKILL.md](SKILL.md) or [examples](references/examples.md) in your source checkout. Refresh a manual installation by copying the updated skill files into your agent's skill folder. If you used the optional CLI, rerun its install command to refresh from GitHub, or replace the GitHub URL with your local checkout's path. Quote paths containing spaces.

Installed copies do not automatically sync with a source checkout. Keep your changes in the source you maintain, then refresh the copies you use.

For an existing personal `devsetup` installation, `devsetup skills-core` is an optional shortcut that installs the core bundle for Codex from configured local sources.

## Related skills

- [HCI](https://github.com/sg98ccy/hci): improve the interfaces and interactions around the content.
- [Coding Practices](https://github.com/sg98ccy/coding-practices): improve the structure and maintainability of the implementation.
