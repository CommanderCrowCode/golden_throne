# Gas Town Rigs Reference

Quick reference for Mayor coordination across all rigs.

## fl_tanwa_info

| Field | Value |
|-------|-------|
| **Purpose** | Personal website for Tanwa Arpornthip (tanwa.info) |
| **Repo** | `git@github.com:CommanderCrowCode/tanwa-info.git` |
| **Beads Prefix** | `fl_tanwa_info-*` |
| **Branch** | `main` |
| **Tech Stack** | Static HTML/CSS, deploying to Render.com |
| **Status** | Active development - Homepage MVP in progress |

**Current Work:**
- `fl_tanwa_info-sk8` - Homepage MVP Epic (polecat: furiosa)
- `fl_tanwa_info-uo7` - Deployment & Usability Epic (polecat: nux)

---

## psu_teaching

| Field | Value |
|-------|-------|
| **Purpose** | Teaching materials for Prince of Songkla University courses |
| **Repo** | `git@github.com:CommanderCrowCode/teaching.git` |
| **Beads Prefix** | `pt-*` |
| **Branch** | `main` |
| **Tech Stack** | Jupyter Notebooks, Python |
| **Status** | Maintenance mode |

---

## 10x_screening

| Field | Value |
|-------|-------|
| **Purpose** | Deal screening automation for SCB 10X VC |
| **Repo** | `git@github.com:CommanderCrowCode/10x_deal_screening.git` |
| **Beads Prefix** | `1s-*` |
| **Branch** | `main` |
| **Tech Stack** | Python, DeepSeek API, Perplexity API |
| **Status** | Setup phase - API keys needed |

**Required API Keys:**
- `DEEPSEEK_API_KEY` - For AI analysis
- `PERPLEXITY_SERVER_API_KEY` - For research pipeline

**Key Files:**
- `run_pipeline.py` - Main entry point
- `src/research_pipeline/` - Core pipeline modules
- `outputs/research_results/` - Generated deal analyses

---

## Quick Commands

```bash
# Check rig status
gt rig list

# List polecats in a rig
gt polecat list <rig>

# Sling work to a rig (auto-spawns polecat)
gt sling <bead-id> <rig>

# Check work in a rig
cd ~/gt/<rig> && bd list --status=open
```

---

*Last updated: 2026-01-04 by Mayor*
