# GitHub Profile README Design

**Date:** 2026-01-11
**Status:** Approved

## Goals

- **Primary audience:** ML/AI research community, professional peers
- **Purpose:** Professional networking and personal brand establishment
- **Tone:** Balanced credibility with approachability

## Design Decisions

| Decision | Choice | Rationale |
|----------|--------|-----------|
| Content depth | Teaser approach | Drive traffic to full portfolio site |
| Visual style | Badge-forward with visual elements | Creates presence and scannability |
| Key elements | Role, research interests, education, standout project | Establishes authority and substance |

## Structure

### 1. Header & Introduction

**Name as H1** followed by animated typing SVG cycling through roles:
- "Head of Federal Innovation @ Google"
- "ML Researcher"
- "AI Builder"

Uses `readme-typing-svg.herokuapp.com` for the animation effect.

**Bio (2 sentences):**
> I lead AI innovation initiatives at Google focused on the federal sector, combining research rigor with real-world deployment. My work spans NLP, computer vision, and generative AI—from parameter-efficient architectures to production systems.

### 2. Education Credentials

Inline badges for:
- Columbia University
- UC Berkeley

Clean, recognizable logos that communicate prestige instantly.

### 3. Research Interests

Section header "What I Work On" with domain badges:
- Machine Learning
- NLP
- Computer Vision
- Generative AI

Dark backgrounds with accent colors for visual cohesion.

### 4. Featured Projects

Two project showcase cards with linked repos:

**BERTVision**
- Parameter-efficient NLP achieving BERT-level performance at a fraction of the compute
- Tag: Research

**Facial Keypoints Detection**
- Kaggle 2nd place finish (RMSE: 1.28637)
- 15-landmark CNN architecture
- Tag: Computer Vision

Cards use HTML table layout for consistent presentation.

### 5. Call-to-Action

Section header "Let's Connect" with:
- Invitation text for collaboration/discussion
- Portfolio button badge (orange #ED7D31)
- LinkedIn button badge

Closing line: "Always happy to discuss ML architectures, research ideas, or interesting problems."

## Visual Elements

| Element | Implementation |
|---------|----------------|
| Typing animation | `readme-typing-svg.herokuapp.com` |
| Badges | `shields.io` with consistent styling |
| Project cards | HTML tables with emoji icons |
| Color scheme | Dark badges, orange accent for portfolio CTA |

## Technical Notes

- All badges use `style=for-the-badge` for consistency
- Project cards link directly to GitHub repos
- Portfolio link: https://cbenge509.github.io/
- LinkedIn link: https://linkedin.com/in/crisbenge

## Content to Migrate

From current README:
- Portfolio badge (update styling)
- Basic expertise badges (refine selection)

From portfolio site:
- Bio language (adapt for brevity)
- Project descriptions (condense)
- Education credentials (add as badges)
