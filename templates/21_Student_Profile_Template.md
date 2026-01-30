# Student Knowledge Template

**Filename Pattern:** `{course_id}.student_profile.md`  
**Regex:** `^[A-Z0-9\-]+\.student_profile\.md$`  
**Authority Tier:** 3 (Authoritative for student context and preferences)  
**Example Filename:** `MGMT-5001-SEC01-2026-SP.student_profile.md`

**Purpose:** Captures student-specific context, preferences, constraints, and group project information to personalize agent responses and support pacing recommendations.

**Constraint:** This file is authoritative for student context ONLY. It may NOT contradict course requirements defined in course_core.md or course_schedule.md.

---

## Metadata
<!-- anchor: #metadata -->

| Field | Value |
|-------|-------|
| **course_id** | `{COURSE_ID}` |
| **term_id** | `{YYYY}-{TT}` |
| **doc_type** | `student_profile` |
| **last_updated** | `{YYYY-MM-DD}` |
| **timezone** | `America/Chicago` |
| **student_name** | `Josh` |

**Change Log (optional):**
- {YYYY-MM-DD}: {Description of change}

---

## Student Identification
<!-- anchor: #student-identification -->

| Field | Value |
|-------|-------|
| **First Name** | Josh |
| **Preferred Name** | {Josh or preferred name} |
| **Program** | {e.g., MBA, MS Finance, Undergraduate Marketing} |
| **Year** | {e.g., First year, Second year, Senior} |
| **Expected Graduation** | {Term and year, e.g., Spring 2027} |

---

## Communication Preferences
<!-- anchor: #communication-preferences -->

### Agent Communication Style

{How Josh prefers the agent to communicate.}

| Preference | Selection |
|------------|-----------|
| **Tone** | {Professional / Casual / Encouraging / Direct} |
| **Detail Level** | {Concise / Moderate / Detailed} |
| **Reminder Style** | {Gentle nudges / Direct reminders / Urgent warnings only} |
| **Encouragement** | {Yes, include motivation / No, just facts} |

### Response Format Preferences

- **For deadlines:** {e.g., "List format with days remaining"}
- **For assignment help:** {e.g., "Step-by-step guidance with examples"}
- **For concept explanations:** {e.g., "Analogies and real-world examples"}
- **For pacing advice:** {e.g., "Weekly task breakdown"}

---

## Writing Style Profile
<!-- anchor: #writing-style-profile -->

{Josh's writing characteristics to help the agent provide appropriately styled assistance.}

### Writing Characteristics

| Attribute | Description |
|-----------|-------------|
| **Voice** | {e.g., "Professional but accessible; avoids jargon when possible"} |
| **Structure** | {e.g., "Strong opening statements; uses headers and bullets for organization"} |
| **Strengths** | {e.g., "Clear argumentation, good use of evidence"} |
| **Development Areas** | {e.g., "Sometimes too verbose; could be more concise"} |

### Preferred Assistance

{How Josh prefers writing assistance from the agent.}

- **Brainstorming:** {e.g., "Likes to talk through ideas before outlining"}
- **Outlining:** {e.g., "Prefers to create own outline, then get feedback"}
- **Drafting:** {e.g., "Appreciates questions that push deeper analysis"}
- **Editing:** {e.g., "Wants specific feedback on clarity and conciseness"}

### Citation Style

{Preferred or required citation format.}

- **Default Style:** {APA / MLA / Chicago / Course-specific}
- **Tool Used:** {e.g., "Zotero for reference management"}

---

## Index References
<!-- anchor: #index-references -->

This file contains the following sections indexed for retrieval:

| Section Anchor | Section Title | Entity IDs |
|----------------|---------------|------------|
| #metadata | Metadata | — |
| #student-identification | Student Identification | — |
| #communication-preferences | Communication Preferences | — |
| #writing-style-profile | Writing Style Profile | — |
| #index-references | Index References | — |

---

## Template Validation Checklist

Before finalizing student profile, verify:

- [ ] course_id matches course_core.md and course_schedule.md exactly
- [ ] term_id matches other Grounded Knowledge Files
- [ ] student_name is "Josh" (per system scope)
- [ ] All section headers have corresponding HTML comment anchors
- [ ] Group project milestone dates match course_schedule.md (source of truth for dates)
- [ ] No personal names appear for team members (use Member 01, Member 02, etc.)
- [ ] No content contradicts course_core.md policies or course_schedule.md dates
- [ ] All dates use dual format (display_date and iso_date) where applicable

---

**END OF STUDENT PROFILE TEMPLATE**