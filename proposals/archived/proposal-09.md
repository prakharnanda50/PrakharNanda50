# Proposal 09 - Dynamic Timetable Coordination

| Field | Value |
|---|---|
| Archive record | AR-09 |
| Sponsoring department | Academic Affairs / CSE / ECE / EEE |
| Introduced | 2023-09-13 |
| Status | Revisit |
| Last activity | 2026-05-20 |

## Background

Every term each department builds its timetable by hand in shared spreadsheets. A single change, such as a faculty member becoming unavailable or a room being withdrawn, breaks several other sections, and clashes are usually found by students on the first day of classes. Laboratory sessions are the hardest case because they need specific rooms and equipment, and elective groups cut across sections. The Academic Office reported three or more full timetable revisions per term in every department in 2023.

## Proposal

Build an intelligent timetable scheduling platform able to generate optimized academic schedules automatically while respecting the constraints below, and able to rebuild a schedule quickly when something changes. An AI or multi-agent approach is preferred (for example separate agents for faculty, rooms, laboratories and student groups negotiating towards a conflict-free schedule), but any constraint-satisfaction or optimization method is acceptable.

## Desired capabilities

- faculty availability (including duty slots and maximum weekly load)
- classroom capacity matched to section size
- laboratory requirements (specific rooms and equipment)
- student groups (sections, batches and shared electives)
- subject requirements (weekly hours, contiguous lab blocks)
- detection and reporting of scheduling conflicts
- automated generation of an optimized timetable
- AI or multi-agent approach to negotiation and optimization
- drag-and-drop manual override by the administrator, with re-checking of conflicts
- administrator dashboard

## Open questions

- How are changes mid-term propagated to students?
- Who has authority to override a generated slot?
- Can the tool read last term's timetable as a starting point?

## Revision log

- 2023-09-13 - Submitted to the committee; status set to Under Discussion (intake register).
- 2023-10-11 - First discussion; committee asked for departmental data (MN-07).
- 2024-05-15 - Status changed: Under Discussion -> Archived (MN-09). No faculty time available to run a pilot this year.
- 2025-11-20 - Status changed: Archived -> Revisit (MN-14). Reopened after recurring timetable complaints from several departments.
- 2026-02-16 - Placed in review queue; panel constituted (MN-15). Register entry R-09.
- 2026-05-20 - Remains in review queue; panel report awaited (MN-17).
