**Planning basis:** Phase 0 is the decision and replanning phase. Phases 1–3 are provisional and depend on Phase 0 findings, Gate 1 approval and later gate decisions. Dates and resource assumptions are not yet commitments.

```mermaid
gantt
    title Lantern Reset Plan - Phases 1 to 3 provisional
    dateFormat YYYY-MM-DD
    axisFormat %b %Y

    section Tower
    P0 Price Tower acceleration :t01, 2026-11-27, 2026-12-18
    P0 Confirm interface and commissioning dependencies :t02, 2026-11-27, 2026-12-18
    P1 Start approved acceleration :t03, 2026-12-19, 2027-03-31
    P1 Work Tower Flow interfaces :t04, 2026-12-19, 2027-03-31
    P1 Complete construction and certify :t05, 2026-12-19, 2027-03-31
    P2 Run three month commissioning :t06, 2027-04-01, 2027-06-30
    P2 Complete tests and close critical interfaces :t07, 2027-04-01, 2027-06-30

    section Flow
    P0 Assess squad resourcing options :f01, 2026-11-27, 2026-12-18
    P0 Define Flow FlowSense separation :f02, 2026-11-27, 2026-12-18
    P1 Triage 96 Tower Flow RFIs :f03, 2027-01-01, 2027-03-31
    P1 Prioritise Tower Flow interface work :f04, 2026-12-19, 2027-03-31
    P1 Plan work through Sprint 54 :f05, 2027-01-01, 2027-04-16
    P1 Apply approved resourcing and monitor workload :f06, 2027-01-01, 2027-03-31
    P1 Preserve records and respond to regulator :f07, 2027-01-01, 2027-11-30
    P1 Review privacy security and clinical safety :f08, 2027-01-01, 2027-03-31
    P2 Complete Sprint 54 and assess exit criteria :f09, 2027-01-01, 2027-04-16
    P2 Run ten week Flow cutover :f10, 2027-04-17, 2027-06-25
    P2 Confirm participating site readiness :f11, 2027-04-17, 2027-06-25

    section People
    P0 Cost face to face training plan :p01, 2026-11-27, 2026-12-18
    P0 Plan local community sessions :p02, 2026-11-27, 2026-12-18
    P1 Prepare trainers sites and backfill :p03, 2026-12-19, 2027-03-31
    P1 Validate workflows and training content :p04, 2026-12-19, 2027-03-31
    P2 Deliver face to face site training :p05, 2027-02-01, 2027-06-25
    P2 Hold local community sessions :p06, 2027-03-01, 2027-06-25

    section Program wide
    P0 Confirm six site grant milestone :w01, 2026-11-27, 2026-12-18
    P0 Define minimum safe operational scope :w02, 2026-11-27, 2026-12-18
    P0 Identify scope that could follow 30 June :w03, 2026-11-27, 2026-12-18
    P0 Confirm grant date flexibility :w04, 2026-11-27, 2026-12-18
    P0 Freeze unapproved scope changes :w05, 2026-11-27, 2026-12-18
    P0 Set change control and decision rights :w06, 2026-11-27, 2026-12-18
    P0 Appoint interim Program Director :w07, 2026-11-27, 2026-12-18
    P0 Establish regular program reviews :w08, 2026-11-27, 2026-12-18
    P0 Consolidate option costs and time savings :w09, 2026-11-27, 2026-12-18
    P0 Assess cost to complete and funding options :w10, 2026-11-27, 2026-12-18
    P0 Prepare Committee options paper :w11, 2026-11-27, 2026-12-18
    P0 Check duplicate options paper row :w12, 2026-11-27, 2026-12-18
    P2 Confirm Commonwealth funding evidence :w13, 2027-04-01, 2027-06-30
    P3 Review defects adoption connectivity workload feedback cost and benefits :w14, 2027-07-01, 2027-11-30
    P3 Placeholder FlowSense work only through approved, controlled validation :w15, 2027-07-01, 2027-11-30
    P3 Determine if non critical elements are to be installed / commissioned :w16, 2027-07-01, 2027-11-30

    section Gate decisions
    Gate 1 approve options :milestone, g1, 2026-12-18, 0d
    Gate 2 practical completion :milestone, g2, 2027-03-31, 0d
    Gate 3 Sprint 54 exit :milestone, g3, 2027-04-16, 0d
    Gate 4 cutover readiness :milestone, g4, 2027-06-25, 0d
    Gate 5 Tower readiness :milestone, g5, 2027-06-30, 0d
    Gate 6 scale decision :milestone, g6, 2027-11-30, 0d

    section Gate date lines
    G1 : vert, vg1, 2026-12-18, 0d
    G2 : vert, vg2, 2027-03-31, 0d
    G3 : vert, vg3, 2027-04-16, 0d
    G4 : vert, vg4, 2027-06-25, 0d
    G5 : vert, vg5, 2027-06-30, 0d
    G6 : vert, vg6, 2027-11-30, 0d
