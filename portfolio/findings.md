# Pilot Findings Analysis — Week 9

**Participants**: 3 (2 HTMX, 1 No-JS)
**Date range**: [2025-12-04 to 2025-12-08]

---

## Quantitative Summary

### Task 1: Filter and Complete
| Metric | HTMX (n=2) | No-JS (n=1) | Overall |
|--------|------------|-------------|---------|
| Mean time (s) | 7.3 | 7.7 | 7.4 |
| Success rate | 100% | 100% | 100% |
| Mean Ease | 8.5 | 8 | 8.33 |
| Mean Issue | 5 | 0 | 3.33 |

**Interpretation**: Seems to be fine overall, with a few small issues surrounding selection.

---

### Task 2: Add New Task
| Metric | HTMX | No-JS | Overall |
|--------|------|-------|---------|
| Mean time (s) | 10.93 | 9.33 | 10.39 |
| Success rate | 100% | 100% | 100% |
| Mean Ease | 8.5 | 10 | 9 |
| Mean Issue | 3 | 0 | 2 |

**Interpretation**: All pilots were pretty happy with this task, with similar small issues surrounding colour.

---

### Task 3: Edit task
| Metric | HTMX | No-JS | Overall |
|--------|------|-------|---------|
| Mean time (s) | 14.19 | xx.xx | 14.19 |
| Success rate | 100% | 0% | 67% |
| Mean Ease | 6 | 5 | 5.67 |
| Mean Issue | 6 | 8 | 6.67 |

**Interpretation**: JS Pilot was unable to complete the task due to JS being off, and Pilot one suffered from button colours being the same.

---

### Task 4: Delete task
| Metric | HTMX | No-JS | Overall |
|--------|------|-------|---------|
| Mean time (s) | 4.78 | 3.70| 4.42 |
| Success rate | 100% | 100% | 100% |
| Mean Ease | 8.5 | 10 | 9 |
| Mean Issue | 4.5 | 0 | 3 |

**Interpretation**: Everyone had a fine time, giving similar feedback of no real issues.

---

## Qualitative Themes

### Theme 1: Button Colours too similar
**Evidence**: 2/3 Pilots mentioned Button colours being too similar
**Quotes**:
- P1 (HTMX): "Makes edit and delete button different colours"
- P2 (HTMX): "Selection colours could be clearer"

**Design implication**: Change delete button to be a different colour, such as Red.

---

## Accessibility Observations

### Keyboard Navigation
- ✅ All features reachable
- ⚠️ Element in selection hard to tell
- ⚠️ Edit Button and Delete Button easily confused
---

## Prioritised Issues

Based on frequency + severity:

1. **High**: Button Colour of Edit and Delete
2. **Medium**: Selection for keyboard users
3. **Low**: Edit button not working when JS is off
