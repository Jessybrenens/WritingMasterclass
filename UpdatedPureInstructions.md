# GitHub Access Instructions for Novel Creation

REPOSITORY_URL: https://github.com/Jessybrenens/WritingMasterclass
PERSONAL_ACCESS_TOKEN: [PERSONAL_ACCESS_TOKEN]

git clone https://[PERSONAL_ACCESS_TOKEN]@github.com/Jessybrenens/WritingMasterclass.git

git config --global user.email "manus@example.com"
git config --global user.name "Manus AI"

# How to use the three GitHub files:

1. First, read Prompt.md - This contains all story-specific parameters you need to understand
   - Fill in any missing parameters if needed
   - Use these parameters throughout the novel creation process

2. Next, follow Writing.md - This contains the complete novel creation process
   - Follow each phase in sequence (Foundation Building, Structural Development, Content Creation, Refinement)
   - Create all required files and documents as specified
   - Apply all writing techniques as outlined

3. Use GitHub.md for version control throughout the process
   - Follow the commit guidelines for each stage
   - Use the specified commit message format
   - Push changes regularly to protect against data loss

Create project structure as specified in Writing.md:
mkdir -p planning drafts final exercises

touch PROGRESS.md

git add .
git commit -m "[INIT] Create project directory structure"
git push origin main

Follow the four-phase development framework in Writing.md:
- Foundation Building (15% of process)
- Structural Development (25% of process)
- Content Creation (40% of process)
- Refinement (20% of process)

Use Git for version control as specified in GitHub.md:
git add [files]
git commit -m "[PREFIX] Descriptive message"
git push origin main

Deliver final novel as specified in Writing.md.
