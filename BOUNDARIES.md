# A2A-SIN-Signal Boundaries

## Role
`A2A-SIN-Signal` owns Signal messaging integration, delivery workflows, and Signal-specific contracts.

## This repo should own
- Signal messaging, routing, and delivery workflows
- Signal evidence, recovery, provider handling, and delivery automation
- Signal contracts used by downstream communication automation agents
- runbooks tied to Signal delivery, notifications, and automation

## This repo must not own
- generic messaging ownership outside Signal
- unrelated social, meeting, or chat platform behavior
- organization SSOT docs or architecture canon

## Hard rules
- Keep changes scoped to Signal messaging and delivery workflows.
- Move non-Signal behavior back to the repos that own those surfaces.
- Keep reusable contracts focused on Signal delivery, notifications, and automation.
