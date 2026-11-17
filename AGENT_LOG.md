# Agent log

Add a dated entry each time you work with your AI coding agent, with the newest entry at the bottom. Each entry records what you asked the agent, what it produced, and what you checked or changed. Paste your key prompts in exactly as you typed them. Include at least one time the agent got something wrong, and how you caught it.

Copy this outline for each entry:

```markdown
## YYYY-MM-DD: What you worked on

- **Asked:** "Paste your prompt here."
- **Agent produced:** What it made or changed.
- **Checked or changed:** How you checked it, and what you fixed.
```

## 2026-11-16: Build the college-town home sales explorer

- **Asked:** "我现在有两个标签页，第一个canvas里面有这份作业的全部教程，你自己看。然后在帮我在GitHub这个网页上直接完成"
- **Agent produced:** Replaced the placeholder homepage with an interactive city median sale-price explorer. It reads the provided CSV, filters out sales below $10,000, shows city counts and medians, and lets readers filter by university or search by city. GitHub Pages was set to use GitHub Actions.
- **Checked or changed:** Read AGENTS.md and docs/data_description_sheet.md first. I initially pasted the new HTML without selecting the old contents; the editor showed the placeholder appended after the new page. I caught this in the editor and replaced the whole file before committing. The page code uses the documented city, state, university, and sale_price fields and leaves the five data files unchanged.

- **Asked:** "你继续你的工作吧 我刚刚开了其他软件不小心断了你的工作"
- **Agent produced:** Resumed the GitHub edit and committed the new homepage to main.
- **Checked or changed:** Confirmed the commit is visible in the repository. The live page still needs its Actions publish workflow to finish before checking the public URL.
