# 🤝 Contributing to Neuro-Study-Hub

Thank you for your interest in contributing to Neuro-Study-Hub! This document provides guidelines and instructions for adding your study materials to our collaborative platform.

## 📋 Table of Contents

- [Getting Started](#getting-started)
- [Types of Contributions](#types-of-contributions)
- [Content Guidelines](#content-guidelines)
- [File Structure](#file-structure)
- [Contribution Process](#contribution-process)
- [Pull Request Guidelines](#pull-request-guidelines)
- [Code of Conduct](#code-of-conduct)
- [FAQ](#faq)

## 🚀 Getting Started

### Prerequisites

- GitHub account (free at [github.com](https://github.com))
- Basic understanding of Git/GitHub
- Original or properly attributed content
- Willingness to share knowledge with peers

### First-Time Setup

1. **Fork the Repository**
   - Click the "Fork" button on the [main repository](https://github.com/sharonkuotah-lab/Neuro-Study-Hub)
   - This creates your own copy to work with

2. **Clone Your Fork**
   ```bash
   git clone https://github.com/YOUR-USERNAME/Neuro-Study-Hub.git
   cd Neuro-Study-Hub
   ```

3. **Create a New Branch**
   ```bash
   git checkout -b add/your-contribution-name
   ```
   Example: `add/neuroanatomy-study-guide`

## 📚 Types of Contributions

### ✏️ Study Notes
- Comprehensive notes on specific topics
- **Format**: Markdown (.md)
- **Location**: `/resources/notes/`
- **Template**: Use headings (H1, H2, H3) for organization
- **Length**: Can be extensive, well-organized notes
- **Include**: Key concepts, definitions, clinical relevance

### 🎴 Flashcards
- Q&A flashcard sets for memorization
- **Format**: JSON or CSV
- **Location**: `/resources/flashcards/`
- **Template**:
  ```json
  {
    "title": "Unit 1: Basic Neuroanatomy",
    "cards": [
      {
        "question": "What are the main divisions of the nervous system?",
        "answer": "Central nervous system (CNS) and peripheral nervous system (PNS)"
      }
    ]
  }
  ```
- **Guidelines**: 10-50 cards per set, clear and concise

### 📖 Study Guides
- Comprehensive unit-by-unit study guides
- **Format**: Markdown (.md)
- **Location**: `/resources/guides/`
- **Include**:
  - Key learning objectives
  - Outline of major concepts
  - Practice questions
  - Exam preparation tips
  - References and resources

### 🎨 Visual Diagrams
- Anatomical drawings, flowcharts, concept maps
- **Format**: SVG, PNG, or PDF
- **Location**: `/resources/diagrams/`
- **Guidelines**:
  - Use clear labels
  - Include legend if necessary
  - High resolution
  - Properly attributed if based on other work

### 📹 Video Resources
- Curated links to educational videos
- **Format**: Markdown (.md)
- **Location**: `/resources/videos/`
- **Template**:
  ```markdown
  ## Recommended Videos
  
  ### Topic Name
  - [Video Title](https://link-to-video)
    Duration: XX minutes
    Source: Channel Name
    Description: Brief description of content
  ```
- **Guidelines**: Legitimate educational sources only

### ❓ Practice Questions
- Exam-style questions with explanations
- **Format**: Markdown (.md)
- **Location**: `/resources/practice-questions/`
- **Include**:
  - Question number and type (Multiple choice, Short answer, etc.)
  - Question text
  - Answer options (if applicable)
  - Correct answer
  - Explanation/rationale
  - Reference to relevant concepts

## ✅ Content Guidelines

### Accuracy & Quality

1. **Medical Accuracy**
   - Content must be evidence-based and medically accurate
   - Use reputable sources
   - Include citations for specific claims
   - Consult course textbooks and materials

2. **Clarity & Organization**
   - Write for nursing students (not too advanced, not too basic)
   - Use clear, professional language
   - Avoid jargon without explanation
   - Organize logically with headers

3. **Completeness**
   - Include references and sources
   - Provide context and clinical relevance
   - Link concepts to NURS 251 learning objectives
   - Include definitions of key terms

4. **Original Work**
   - Content must be original or properly attributed
   - If adapting from other sources, cite them
   - Use quotation marks for direct quotes
   - Include source URLs and author information

### Citation Format

Use APA format for citations:

```markdown
## References

- Author, A. A., & Author, B. B. (Year). *Title of work*. Publisher.
- Website Title. (Year). Retrieved from https://example.com
```

Inline citations:
```markdown
The nervous system has two main divisions (Smith & Jones, 2020).
```

## 📁 File Structure

### Naming Conventions

**Study Notes:**
- `Topic_Name.md` - Main notes
- `Topic_Name_Key_Terms.md` - Terminology
- `Topic_Name_Clinical_Notes.md` - Clinical applications

**Flashcards:**
- `Unit_Number_Topic_Name.json`
- Example: `Unit_1_Basic_Neuroanatomy.json`

**Study Guides:**
- `Unit_Number_Study_Guide.md`
- `Unit_Number_Exam_Prep.md`

**Practice Questions:**
- `Unit_Number_Practice_Questions.md`
- `Unit_Number_Answer_Key.md`

**Diagrams:**
- Descriptive names: `Brain_Lobes.svg`, `Neurotransmitter_Pathways.png`

### Directory Structure

```
/resources/
├── notes/
│   ├── Neuroanatomy.md
│   ├── Neuroanatomy_Key_Terms.md
│   └── Neural_Transmission.md
├── flashcards/
│   ├── Unit_1_Basics.json
│   └── Unit_2_Anatomy.json
├── guides/
│   ├── Unit_1_Study_Guide.md
│   └── Unit_2_Exam_Prep.md
├── diagrams/
│   ├── Brain_Anatomy.svg
│   └── Synapse_Diagram.png
├── videos/
│   └── Recommended_Videos.md
└── practice-questions/
    ├── Unit_1_Questions.md
    └── Unit_1_Answer_Key.md
```

## 🔄 Contribution Process

### Step-by-Step Guide

#### 1. Fork & Clone
```bash
# Fork on GitHub, then:
git clone https://github.com/YOUR-USERNAME/Neuro-Study-Hub.git
cd Neuro-Study-Hub
```

#### 2. Create a Branch
```bash
git checkout -b add/your-topic-name
# Branch naming: add/, fix/, improve/, update/
```

#### 3. Create Your Content
- Add files to appropriate directories
- Follow naming conventions
- Include citations and references
- Proofread carefully

#### 4. Add & Commit
```bash
git add .
git commit -m "Add: Brief description of your contribution"
# Examples:
# "Add: Neurotransmitter study guide and flashcards"
# "Fix: Correct anatomical terminology in neuroanatomy notes"
# "Improve: Add diagrams to spinal cord section"
```

#### 5. Push to Your Fork
```bash
git push origin add/your-topic-name
```

#### 6. Create a Pull Request
- Go to your fork on GitHub
- Click "Compare & pull request"
- Fill out the PR template completely
- Submit for review

## 📝 Pull Request Guidelines

### PR Title Format
```
[Type]: Brief description
```

Types:
- `[Add]` - New content
- `[Fix]` - Correct errors
- `[Improve]` - Enhance existing content
- `[Update]` - Refresh outdated information

### PR Description Template

```markdown
## Description
Brief overview of your contribution

## Type of Change
- [ ] New study material
- [ ] Correction of existing content
- [ ] Improvement/enhancement
- [ ] New feature/resource

## Content Checklist
- [ ] Content is medically accurate
- [ ] Sources are cited
- [ ] Follows file naming conventions
- [ ] Located in correct directory
- [ ] Proofread for spelling/grammar
- [ ] References are complete

## Related Issues
Closes #(issue number) if applicable

## Additional Context
Add any other context here
```

### Review Process

1. **Initial Review** - Maintainers check:
   - File structure and naming
   - Basic accuracy
   - Citation completeness

2. **Content Review** - Peer reviewers verify:
   - Medical accuracy
   - Clarity and organization
   - Appropriateness for NURS 251
   - Citation format

3. **Feedback & Revision**
   - Address any requested changes
   - Respond to comments
   - Update your branch
   - Push updates (no need to recreate PR)

4. **Approval & Merge**
   - PR is approved
   - Changes are merged to main
   - Your contribution goes live!

## 💬 Code of Conduct

### Our Commitment
We are committed to providing a welcoming and inclusive environment.

### Expected Behavior
- Be respectful of all contributors
- Provide constructive feedback
- Accept criticism gracefully
- Focus on what is best for the community
- Show empathy towards others

### Unacceptable Behavior
- Harassment or discrimination
- Trolling or insulting comments
- Personal attacks
- Publishing private information
- Any form of abuse

### Reporting Issues
If you witness inappropriate behavior, please report it to sharonkuotah@gmail.com

## ❓ FAQ

### Q: Do I need to be a NURS 251 student to contribute?
**A:** Preferably yes, but instructors and others with relevant expertise are also welcome.

### Q: What if my content contains an error that's discovered later?
**A:** No problem! Open an issue or submit a new PR with the correction. Continuous improvement is part of our process.

### Q: Can I contribute video content?
**A:** We curate links to existing educational videos rather than hosting our own. Submit markdown files with organized video recommendations.

### Q: How long before my PR is reviewed?
**A:** Usually within 1-2 weeks, depending on complexity and reviewer availability.

### Q: Can I contribute content in other languages?
**A:** Currently, we focus on English. Multilingual support may be added in the future.

### Q: What if I have multiple contributions?
**A:** Create separate branches and PRs for each contribution. This helps with organization and review.

### Q: Can I remove my contributed content later?
**A:** Yes, but consider if it might still help others. If you need to remove content, open an issue.

### Q: Do contributors get any recognition?
**A:** Absolutely! Contributors are listed in:
- The README.md file
- GitHub contributors page
- Individual file attributions

## 📚 Resources

- [GitHub Hello World](https://guides.github.com/activities/hello-world/)
- [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
- [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)
- [APA Citation Format](https://apastyle.apa.org/)
- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

## 🎉 Thank You!

Your contributions make Neuro-Study-Hub a better resource for everyone. We truly appreciate your time and effort!

---

**Questions?** Open an issue or contact us at sharonkuotah@gmail.com

**Ready to contribute?** [Get started now!](https://github.com/sharonkuotah-lab/Neuro-Study-Hub/fork)
