# GitHub-Based Novel Creation Instructions for Manus AI

## Overview

This prompt provides detailed instructions for creating professional-quality novels using GitHub for version control, progress tracking, and file management. Instead of containing all novel creation techniques within this prompt, the comprehensive writing instructions are stored in the GitHub repository you'll access. This approach offers several advantages:

1. **Protection against data loss** in case of crashes or context limit issues
2. **Reduction of context bloat** within the task session
3. **Structured version control** for tracking progress and changes
4. **Organized file management** for complex, multi-stage projects
5. **Seamless collaboration** between AI and human authors if needed

## GitHub Repository Access

To begin the novel creation process, you'll need to access the GitHub repository containing all necessary instructions and templates.

```
REPOSITORY_URL: [GitHub repository URL, e.g., "https://github.com/username/repository"]
PERSONAL_ACCESS_TOKEN: [GitHub PAT for authentication - secure token provided by user]
```

## Initial Setup Process

1. **Clone the repository** using the provided URL and Personal Access Token:
   ```
   git clone https://[PERSONAL_ACCESS_TOKEN]@[REPOSITORY_URL without https://]
   ```

2. **Configure Git identity** for proper commit attribution:
   ```
   git config --global user.email "manus@example.com"
   git config --global user.name "Manus AI"
   ```

3. **Verify repository contents** to ensure all necessary files are present:
   ```
   ls -la [repository directory]
   ```

4. **Access the Prompt.md file** which contains comprehensive novel creation instructions:
   ```
   cat [repository directory]/Prompt.md
   ```

## Novel Creation Workflow

### Phase 1: Project Initialization

1. **Create a project directory structure** within the repository:
   ```
   mkdir -p planning drafts final exercises
   ```

2. **Initialize project tracking** by creating a PROGRESS.md file:
   ```
   touch PROGRESS.md
   ```

3. **Commit the initial structure**:
   ```
   git add .
   git commit -m "[INIT] Create project directory structure"
   git push origin main
   ```

4. **Create initialization parameters file** based on user requirements:
   - Create Parameters.md with all novel specifications
   - Commit this file with message "[INIT] Define novel parameters"

### Phase 2: Planning and Development

1. **Follow the sequential process** outlined in Prompt.md:
   - Create all planning documents in the /planning directory
   - Commit each planning document separately with descriptive messages
   - Update PROGRESS.md after each significant milestone

2. **Implement the four-phase development framework**:
   - Foundation Building (15% of process)
   - Structural Development (25% of process)
   - Content Creation (40% of process)
   - Refinement (20% of process)

3. **Use regular commits** to save progress:
   - Commit at logical breakpoints (completion of sections, chapters, or editing phases)
   - Use descriptive commit messages with appropriate prefixes:
     - `[PLAN]` - Planning document updates
     - `[DRAFT]` - New chapter drafts
     - `[REVISE]` - Content revisions
     - `[EDIT]` - Editorial improvements
     - `[EXERCISE]` - Writing exercises and experiments
     - `[FINAL]` - Final version files

4. **Push changes regularly** to protect against data loss:
   ```
   git push origin main
   ```

### Phase 3: Implementation of Writing Techniques

1. **Reference the Appendix in Prompt.md** for detailed implementation instructions on:
   - Four-Stage Editing Process
   - Practical Exercises Implementation
   - Emotional Impact Strategy
   - Argumentation and Persuasion Framework
   - Rhetorical Device Implementation

2. **Create implementation files in the /exercises directory**:
   - Document technique applications
   - Create before/after examples
   - Track effectiveness of different approaches

3. **Apply techniques to draft chapters** in the /drafts directory:
   - Implement techniques systematically
   - Document application in commit messages
   - Track improvements in PROGRESS.md

### Phase 4: Refinement and Completion

1. **Apply the four-layer editing pyramid** to all draft chapters:
   - Structural Editing (foundation layer)
   - Content Editing (second layer)
   - Paragraph and Sentence Editing (third layer)
   - Technical Editing (top layer)

2. **Compile final manuscript** in the /final directory:
   - Create individual chapter files
   - Create complete manuscript as [TITLE].md
   - Generate COMPLETION.md with final word count and summary

3. **Final commit and push**:
   ```
   git add .
   git commit -m "[FINAL] Complete [TITLE] narrative"
   git push origin main
   ```

## GitHub Best Practices

### When to Commit Changes

1. **After completing each planning document**
2. **After drafting each chapter**
3. **After each major revision phase**
4. **After implementing specific techniques**
5. **After reaching word count milestones** (e.g., every 5,000 words)
6. **Before taking breaks** to ensure no work is lost

### Why Use GitHub for Novel Creation

1. **Version Control**: Track the evolution of your novel and revert to previous versions if needed
2. **Progress Tracking**: Maintain a clear record of development through commit history
3. **Structured Organization**: Keep files organized in a logical directory structure
4. **Disaster Recovery**: Protect against data loss with remote storage
5. **Context Management**: Reduce context bloat by storing detailed instructions and reference materials
6. **Collaboration Potential**: Enable seamless collaboration with human authors if needed

### Commit Message Guidelines

Use clear, descriptive commit messages that follow this format:
```
[PREFIX] Brief description of changes

- Detailed bullet point about specific change
- Another specific detail about the changes made
- Any challenges addressed or decisions made
```

Example:
```
[DRAFT] Complete Chapter 3 first draft

- Developed protagonist's confrontation with antagonist
- Implemented foreshadowing of key plot twist
- Established character motivation for upcoming journey
- Current word count: 12,450
```

## Troubleshooting GitHub Issues

### Authentication Problems

If you encounter authentication issues:
1. Verify the Personal Access Token is correct
2. Ensure the token has appropriate repository permissions
3. Try using the HTTPS URL format with embedded token

### Merge Conflicts

If you encounter merge conflicts:
1. Pull the latest changes: `git pull origin main`
2. Resolve conflicts by editing affected files
3. Add resolved files: `git add [conflicted-files]`
4. Complete the merge: `git commit -m "Resolve merge conflicts"`

### Connection Issues

If you encounter connection problems:
1. Verify internet connectivity
2. Try again after a brief pause
3. If persistent, save work locally and attempt push later

## Final Delivery

The completed novel will be delivered as:
1. Individual chapter files in `/final/` directory
2. Complete manuscript as `[TITLE].md` in repository root
3. Final word count and completion report in `COMPLETION.md`
4. Development process documentation in `PROCESS.md`
5. GitHub repository URL for accessing all files and version history

## Implementation Notes

This GitHub-based approach ensures professional-quality output by implementing:

1. Comprehensive planning before drafting
2. Structured development process with clear milestones
3. Multi-layered editing approach
4. Continuous quality verification
5. Consistent version control and progress tracking
6. Protection against data loss
7. Reduction of context bloat

By following these instructions and utilizing the comprehensive novel creation process detailed in Prompt.md within the repository, you will create a professional author-quality novel without requiring additional user input after the initial parameters are provided.
