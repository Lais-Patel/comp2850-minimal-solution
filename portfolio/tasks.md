# Evaluation Tasks — Week 9

## Task 1: Filter and Complete
**Scenario**: You've just finished your COMP2850 HCI lab write-up.

**Instructions**:
1. Filter to find the task titled "Finish HCI 2850 portfolio work"
2. Mark it as complete by removing it
3. Verify it's gone

**Success criteria**:
- Participant finds correct task within 30 seconds
- Participant successfully removes the task
- They are able to verify its removal

**Inclusion focus**: Keyboard access, screen reader announcement

---

## Task 2: Add New Task
**Scenario**: You've just been assigned a new coursework deadline.

**Instructions**:
1. Add a new task: "Submit COMP2860 Worksheet 6"
2. Confirm it appears in the list

**Success criteria**:
- Form submission works (HTMX + no-JS)
- New task appears immediately (or after reload for no-JS)
- Confirmation message shown

**Inclusion focus**: Error handling (if blank title), status announcements

---

## Task 3: Edit Task Inline
**Scenario**: You made a typo in a task title.

**Instructions**:
1. Find task "Submit COMP2860 Worksheet 6"
2. Edit it to "Submit COMP2870 Worksheet 6"
3. Save the change

**Success criteria**:
- Edit mode activates (input appears)
- Save updates the title
- Focus returns to edited task

**Inclusion focus**: Focus management, keyboard-only editing, Cancel button

---

## Task 4: Delete Completed Task
**Scenario**: You've completed "Submit COMP2870 Worksheet 6"" and want to remove it.

**Instructions**:
1. Find task "Submit COMP2870 Worksheet 6"
2. Delete it
3. Confirm it's gone

**Success criteria**:
- Confirmation shown (HTMX) OR form submits (no-JS)
- Task removed from list
- Status message announced

**Inclusion focus**: Confirmation (HTMX has `hx-confirm`, no-JS has none - documented trade-off)

---

## Metrics per Task

For each task, record:
- **Time** (seconds from start to completion)
- **Observation** (Qualitive - how they felt)
- **Ease [1-10]** (How easy was it to complete)
- **Feedback** (Qualitive - what they think could be better)
- **Issue [1-10]** (How important to fix issue stated in feedback)