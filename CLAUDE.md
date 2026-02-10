# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is an AWS Certified Cloud Practitioner (CLF-C02) study guide repository containing 19 lessons organized by exam domains. Each lesson topic has a `readme.md` (study content) and `diagram.drawio` (visual diagram).

## Repository Structure

```
lesson-XX-topic-name/
  ├── 01-subtopic/
  │   ├── readme.md      # Study content with tables, ASCII diagrams, exam tips
  │   └── diagram.drawio # Visual diagram in Draw.io XML format
  └── 02-subtopic/
      └── ...
```

## Content Standards

### readme.md Files
- Include exam-focused content with key concepts, definitions, and comparisons
- Use markdown tables for structured information
- Include ASCII art diagrams for visual representation
- Add "Exam Tips" sections highlighting what to remember for the test
- End with "Key Takeaways" as numbered bullet points

### diagram.drawio Styling Requirements

All diagrams must follow this AWS-themed styling:

**Color Scheme:**
- `#FF9900` - AWS Orange (primary accent, arrows, highlights)
- `#232F3E` - AWS Dark Blue (containers, service blocks)
- `#1E8900` - Green (positive/benefits, OpEx, cloud advantages)
- `#DD3522` - Red (security, warnings, CapEx, traditional IT)

**Required Style Attributes:**
- Container/group boxes: `rounded=0;shadow=1;`
- Animated arrows: `flowAnimation=1;shadow=1;`
- All shapes include: `shadow=1;`
- Service blocks: `rounded=0;whiteSpace=wrap;html=1;fillColor=#232F3E;strokeColor=none;fontColor=#FFFFFF;`

**Example container style:**
```xml
style="whiteSpace=wrap;html=1;fillColor=#FFF2CC;strokeColor=#FF9900;strokeWidth=2;rounded=0;shadow=1;"
```

**Example arrow style:**
```xml
style="endArrow=classic;html=1;strokeWidth=2;strokeColor=#FF9900;flowAnimation=1;shadow=1;"
```
