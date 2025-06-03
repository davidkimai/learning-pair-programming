# [What Actually Works: 12 Lessons from AI Pair Programming](https://forgecode.dev/blog/ai-agent-best-practices/)

> By [Forge Code](https://github.com/antinomyhq/forge)

TL;DR

Planning & Process:

    Write a plan first, let AI critique it before coding
    Use edit-test loops: write failing test → AI fixes → repeat
    Commit small, frequent changes for readable diffs

Prompt Engineering:

    Keep prompts short and specific context bloat kills accuracy
    Ask for step-by-step reasoning before code
    Use file references (@path/file.rs:42-88) not code dumps

Context Management:

    Re-index your project after major changes to avoid hallucinations
    Use tools like gitingest.com for codebase summaries
    Use Context7 MCP to stay synced with latest documentation
    Treat AI output like junior dev PRs review everything

What Doesn't Work:

    Dumping entire codebases into prompts
    Expecting AI to understand implicit requirements
    Trusting AI with security-critical code without review



