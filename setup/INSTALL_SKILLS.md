# Install Codex Skills on a New Device

This project uses several Codex skills for academic research, literature review, paper writing, proposal drafting, and review.

After cloning this repository on a new device, install these skills in Codex, then restart Codex.

## Install Commands

```bash
python3 ~/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py --repo lishix520/academic-paper-skills --path strategist --name academic-paper-strategist

python3 ~/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py --repo lishix520/academic-paper-skills --path composer --name academic-paper-composer

python3 ~/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py --repo Imbad0202/academic-research-skills --path deep-research academic-paper academic-paper-reviewer academic-pipeline --method git

python3 ~/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py --repo Master-cai/Research-Paper-Writing-Skills --path research-paper-writing

python3 ~/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py --repo luwill/research-skills --path research-proposal

python3 ~/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py --repo Zhangyanbo/vibe-paper-writing --path . --name vibe-paper-writing

python3 ~/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py --repo Ar9av/PaperOrchestra --path skills/paper-orchestra --name paper-orchestra --method git
```

## Verify Installation

```bash
find ~/.codex/skills -maxdepth 2 -name SKILL.md | sort
```

Expected project-related skills:

- `academic-paper-strategist`
- `academic-paper-composer`
- `deep-research`
- `academic-paper`
- `academic-paper-reviewer`
- `academic-pipeline`
- `research-paper-writing`
- `research-proposal`
- `vibe-paper-writing`
- `paper-orchestra`

## Suggested Workflow

- Use `deep-research` for literature mapping and fact-checking.
- Use `academic-paper-strategist` for research gap and paper story planning.
- Use `research-paper-writing` for Introduction, Related Work, Method, and reviewer-facing revision.
- Use `research-proposal` for proposal defense materials.
