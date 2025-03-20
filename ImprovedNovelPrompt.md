# Professional Novel Creation Prompt for Manus AI

## Overview

This comprehensive prompt template is designed to enable Manus AI to create professional-quality novels with human author-level craftsmanship. The template integrates advanced writing principles, storytelling techniques, and systematic development processes while leveraging GitHub for version control, progress tracking, and file management. This prompt is self-contained and requires no additional user input after initial parameters are provided.

## Initialization Parameters

```
TITLE: [Novel title]
GENRE: [Primary genre with optional subgenre]
WORD_COUNT: [Target word count range, e.g., "80,000-100,000"]
SETTING: [Time period and location]
CENTRAL_LOCATION: [Key location where significant action occurs]
LOCATION_TRANSFORMATION: [How the central location changes from its original purpose to current state]
THEMATIC_ELEMENTS: [2-4 core themes to be explored]
POV_STYLE: [First-person/Third-person limited/Third-person omniscient/Multiple POV]
CHARACTER_COUNT: [Number of POV characters]
CONCEPTUAL_TRAITS: [Key character traits or archetypes to be embodied by characters]
CHARACTER_ROLES: [Protagonist/Antagonist/Supporting roles]
CORE_CONFLICT: [Central tension driving the narrative]
KEY_ELEMENT: [Object, concept, or event of significance to the plot]
AUTHORIAL_STYLE: [Specific author's style to emulate or stylistic elements to incorporate]
PROSE_ELEMENTS: [Specific prose characteristics, e.g., "lyrical," "sparse," "dialogue-heavy"]
REPOSITORY_URL: [GitHub repository URL]
PERSONAL_ACCESS_TOKEN: [GitHub PAT for authentication]
```

## Execution Process

Upon receiving this prompt with completed parameters, Manus AI will:

1. Initialize the GitHub environment using the provided repository URL and personal access token
2. Create a structured development plan with clear milestones
3. Generate all necessary planning and development files
4. Execute the novel creation process through systematic stages
5. Commit progress regularly with descriptive messages
6. Deliver a complete, professional-quality novel requiring no additional editing

## Development Framework

### Phase 1: Foundation Building (15% of process)

#### World Building
- Create `World.md` documenting:
  - Detailed setting analysis including historical, cultural, and physical elements
  - Central location's original purpose and transformation process
  - Societal structures, rules, and systems relevant to the narrative
  - Sensory details that bring the world to life (sights, sounds, smells, textures)
  - Thematic integration with setting elements

#### Character Development
- Create `Characters.md` documenting:
  - Detailed profiles for each POV character including:
    - Physical attributes and appearance
    - Psychological profile (motivations, fears, desires, contradictions)
    - Background and formative experiences
    - Voice patterns and distinctive speech characteristics
    - Character-specific worldview aligned with thematic elements
    - Relationship dynamics with other characters
    - Character arcs mapped to plot progression
  - Secondary character profiles with relevant details
  - Character relationship map showing connections and tensions

#### Conceptual Framework
- Create `Conceptual.md` documenting:
  - Analysis of thematic elements and their manifestation in plot and characters
  - Symbolic systems and motifs to be employed
  - Philosophical or ideological questions to be explored
  - Emotional journey mapped across narrative arc
  - Intended reader experience and emotional impact

### Phase 2: Structural Development (25% of process)

#### Plot Architecture
- Create `Plot.md` documenting:
  - Three-act structure breakdown with key turning points
  - Chapter-by-chapter outline with purpose of each chapter
  - Subplot integration plan showing how secondary narratives support main plot
  - Conflict escalation pattern throughout narrative
  - Resolution design for main plot and subplots
  - Key element integration throughout narrative structure

#### Narrative Design
- Create `Narrative.md` documenting:
  - POV implementation strategy
  - Scene sequencing with pacing considerations
  - Tension and release patterns
  - Information revelation strategy (what readers learn when)
  - Foreshadowing and payoff planning
  - Timeline management for narrative events

#### Stylistic Blueprint
- Create `Style.md` documenting:
  - Analysis of target authorial style with specific techniques
  - Sentence structure patterns and variation strategy
  - Vocabulary range and selection principles
  - Dialogue style and attribution approach
  - Descriptive technique parameters
  - Prose rhythm and cadence considerations
  - Literary devices to be employed

### Phase 3: Content Creation (40% of process)

#### First Draft Development
- Create sequential chapter drafts following established structure
- Implement consistent POV handling as defined in narrative design
- Maintain stylistic consistency according to stylistic blueprint
- Ensure thematic elements are woven throughout narrative
- Balance dialogue, action, description, and introspection
- Implement foreshadowing elements as planned
- Create chapter files named `Chapter_XX.md` with consistent formatting

#### Continuity Management
- Create `Continuity.md` to track:
  - Character details and consistency
  - Timeline of events
  - Setting details referenced
  - Plot points and their resolution status
  - Introduced elements requiring payoff
  - Thematic development progress

### Phase 4: Refinement (20% of process)

#### Structural Editing
- Review and revise overall narrative structure
- Ensure proper pacing and tension development
- Verify subplot integration and resolution
- Confirm character arc progression
- Validate thematic development throughout narrative

#### Content Editing
- Enhance scene development where needed
- Strengthen character motivations and reactions
- Improve dialogue authenticity and purpose
- Enrich descriptive elements and sensory details
- Verify logical consistency and causality

#### Line Editing
- Refine prose at sentence level
- Enhance language for maximum impact
- Improve rhythm and flow
- Eliminate redundancies and awkward constructions
- Strengthen imagery and metaphors
- Ensure stylistic consistency

#### Technical Editing
- Correct grammar, punctuation, and spelling
- Standardize formatting
- Verify consistency in names, places, and terminology
- Eliminate continuity errors
- Format for final delivery

## GitHub Integration Protocol

### Repository Structure
- Main branch only workflow
- Organized directory structure:
  - `/planning/` - Contains all planning documents
  - `/drafts/` - Contains chapter drafts
  - `/final/` - Contains final novel files

### Commit Strategy
- Regular commits with descriptive messages
- Commit categories:
  - `[PLAN]` - Planning document updates
  - `[DRAFT]` - New chapter drafts
  - `[REVISE]` - Content revisions
  - `[EDIT]` - Editorial improvements
  - `[FINAL]` - Final version files

### Progress Tracking
- Maintain `PROGRESS.md` with:
  - Completed milestones
  - Current development stage
  - Upcoming tasks
  - Challenges addressed
  - Word count progress

## Quality Assurance Mechanisms

### Narrative Coherence Verification
- Plot thread tracking to ensure all introduced elements are resolved
- Character motivation consistency checks
- Logical causality verification between events
- Timeline consistency validation

### Stylistic Consistency Verification
- Voice consistency monitoring across chapters
- Prose style adherence to established parameters
- Dialogue pattern consistency for characters
- Tonal alignment with genre expectations

### Thematic Development Verification
- Theme tracking throughout narrative
- Symbol and motif consistency
- Character growth alignment with themes
- Resolution satisfaction relative to thematic promises

## Final Delivery

The completed novel will be delivered as:
1. Individual chapter files in `/final/` directory
2. Complete manuscript as `[TITLE].md` in repository root
3. Final word count and completion report in `COMPLETION.md`

All files will be properly committed to the GitHub repository using the provided personal access token, with a final commit message of "Complete [TITLE] narrative."

## Implementation Notes

This prompt template is designed to be completely self-contained, requiring no additional user input after initial parameters are provided. The systematic approach ensures professional-quality output by implementing:

1. Comprehensive planning before drafting
2. Structured development process with clear milestones
3. Multi-layered editing approach
4. Continuous quality verification
5. Consistent version control and progress tracking

The resulting novel will demonstrate professional author-level quality with:
- Engaging and coherent narrative structure
- Well-developed, believable characters
- Thematically rich content
- Stylistically consistent and polished prose
- Satisfying emotional and intellectual reader experience
