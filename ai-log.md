## AI interaction 1
Date: October 1, 2026
Assistant: Claude.ai
Purpose: Understand core GitHub concepts before structuring my workflow
Prompt or summary: Asked for an explanation of the difference between a repository, branch, commit, pull request, and issue.
Useful suggestion: Clarified that commits happen on branches, PRs propose merging branches, and issues can be linked to PRs/commits for tracking. .
Decision: accepted
Reason: The explanation was accurate and directly useful for reviewing the workflow structure.
Related GitHub URL: https://github.com/pintsizedcoder/swe325_525-github-ai-practice/

## AI interaction 2
Date: October 1, 2026
Assistant: Claude.ai
Purpose: Improve the clarity of commit messages in my existing repo history
Prompt or summary: Shared a screenshot of my commit history (README.md, workflow-notes.md, and ai-log.md changes) and asked for a proposed improvement to the commit messages.
Useful suggestion: Recommended following the type: summary, convention (for example: 'docs: add setup instructions to README.md' ) instead of GitHub's auto messages like "Update README.md," since descriptive messages explain what changed and why. Also flagged that my "Create ai-log.md and Edit ai-log.md with AI interaction #1" commit bundled two separate actions into one message and suggested splitting it into two distinct commits.
Decision: accepted
Reason: The suggested format made my commit history easier to scan and understand at a glance, and splitting bundled commits follows the best practice of one commit representing one logical change.
Related GitHub URL: https://github.com/pintsizedcoder/swe325_525-github-ai-practice/

## AI interaction 3
Date: October 1, 2026
Assistant: Claude.ai
Purpose: Create a checklist for a complete pull-request description.
Prompt or summary: Asked Claude for a suggested pull-request checklist
Useful suggestion: Claude suggested including a change summary, related issues, change type, testing, screenshots where applicable, reviewer checks, breaking changes, and deployment notes. 
Decision: revised
Reason: I kept the relevant suggestions and added the assignment-specific requirements. I omitted testing, linting, and deployment items because they do not apply to this Markdown documentation work.
Related GitHub URL: https://github.com/pintsizedcoder/swe325_525-github-ai-practice/

## Reflection

1. Which GitHub action or object was most useful to you, and why?

The pull request was most useful because it brought my branch changes together in one place where I could review the files and commits before merging them into the default branch.

2. Which AI suggestion did you accept, and what made it useful?

I accepted Claude. ai suggestion to organize my issue into a goal, scope, acceptance criteria, and task checklist. This helped me distinguish the steps I needed to take from the conditions that would show the work was complete.

3. Which AI suggestion did you revise or reject, and why?

I revised Claude’s pull-request checklist by adding the assignment-specific requirements, including the commit list, AI-assistance summary, and acceptance checklist. I left out testing, linting, and deployment items because they did not apply to this documentation-only repository.

4. What did you verify yourself instead of trusting the AI?

I checked my GitHub commit history to confirm the actual commit messages rather than relying on AI-generated examples. I also read the assignment requirements and reviewed my Markdown files in the pull request.

5. What would you change in your GitHub workflow next time?

Next time, I would use more descriptive commit messages instead of messages such as “Update README.md.” I would also record GitHub links and AI interactions as I work so that the final documentation is easier to complete.
