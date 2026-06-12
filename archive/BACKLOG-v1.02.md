# Trust & Freedom Board - Backlog
Version: v1.02 | Updated: 12 June 2026
No secrets, passwords, tokens or credentials in this file.

---

## CLOSED / BUILT / MONITOR

| ID | Title | Status | Version |
|----|-------|--------|---------|
| BL-01 | Drag and drop section ordering | CLOSED - superseded by BL-15 | - |
| BL-02 | Freedom cards carousel view | BUILT - monitor | v1.0x |
| BL-03 | Trust Log suspension audit column | BUILT - monitor | v1.0x |
| BL-04 | Suspension cascade logic | BUILT - monitor | v1.0x |
| BL-05 | Score floor per suspension | BUILT - monitor | v1.0x |
| BL-06 | High cost activities | BUILT - monitor | v1.0x |
| BL-07 | Positive targets and recognition | BUILT - monitor | v1.0x |
| BL-08 | Page order positives before negatives | BUILT - monitor | v1.0x |
| BL-09 | Smarter update mechanism | BUILT - monitor | v1.0x |
| BL-10 | Parent audit trail | BUILT - monitor | v1.0x |
| BL-11 | Dual view parent/son | BUILT - monitor | v1.0x |
| BL-15 | Three-tab view Overview/Detail/Custom | BUILT - monitor | v1.0x |
| BL-16 | Carousel starts on highest GRANTED freedom | BUILT | v1.01 |
| BL-17 | Edit existing entries | BUILT | v1.01 |
| BL-18 | Quick actions real entries | BUILT | v1.01 |
| BL-19 | Auto-commit via GitHub API | BUILT | v1.01 |
| BL-21 | API commit UTF-8 safety | BUILT | v1.01 |
| BL-23 | API commit UTF-8 safety in pipeline | BUILT | v1.01 |
| BL-28 | Date format US/UK confusion in form | FIXED | v1.02 |
| BL-29 | Suspension toggle defaults ON | FIXED | v1.02 |
| BL-30 | Commit button visible without token | FIXED | v1.01 |
| BL-32 | Legacy iPad / iOS 10.3.3 safe rendering | BUILT | v1.02 |
| BL-33 | Legacy-safe manual update mode | BUILT | v1.02 |
| BL-34 | Render failure fallback message | BUILT | v1.02 |
| BL-35 | Debug footer showing render mode / browser | BUILT | v1.02 |
| BL-36 | Print-friendly light mode | BUILT | v1.02 |
| BL-37 | Safe public backlog file | BUILT | v1.02 |
| BL-38 | Font fallback if Google Fonts fail | BUILT | v1.02 |

---

## ACTIVE - TO BUILD

| ID | Title | Priority | Notes |
|----|-------|----------|-------|
| BL-24 | Targets - drag to reorder | Medium | Same long-press approach as custom view |
| BL-25 | Targets - colour highlight toggle | Low | Cycle through default/amber/green per target |
| BL-26 | Diary events - predefined options | Medium | Dropdown/chips for common diary entries |
| BL-31 | Mobile optimisation review | High | Score invisible on mobile, touch targets, tab bar |

---

## ACTIVE - REVIEW / CONVERSATION (not a build)

| ID | Title | Priority | Notes |
|----|-------|----------|-------|
| BL-27 | Starting position - manual freedom overrides | HIGH | Must happen before going live with Vaughan. Review each freedom threshold. Ensure nothing auto-unlocks unexpectedly as score rises. |

---

## PARKED / FUTURE ONLY

| ID | Title | Notes |
|----|-------|-------|
| BL-12 | Proper backend - Supabase/Firebase | Needed for full multi-user auth |
| BL-13 | Password protected parent admin - proper auth | Needs backend first |
| BL-14 | Hosting migration - Netlify or similar | When backend is added |
| BL-20 | Token security improvement | Move token out of browser session |
| BL-22 | Full reset button on Integrity Update | Dangerous - needs double-confirm if ever built |

---

## NOTES
- All secrets, passwords, tokens and credentials are managed separately and must never appear in this file
- Version history is tracked via HTML comment in each file header
- GitHub repo: trusted-independence (public)
- Two files: index.html (board) and integrity-update.html (parent tool)
