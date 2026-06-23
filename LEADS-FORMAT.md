# Leads — Format & Rules

## JSON Schema (per lead)
```json
{
  "name": "",
  "business": "",
  "status": "",
  "notes": ""
}
```

## Status Values
- `new` — identified, not yet contacted
- `contacted` — reached out (call or door-to-door), no response yet
- `warm` — already in talks / showed interest
- `proposal` — proposal sent, waiting for decision
- `closed` — signed client
- `dead` — not interested / no follow-up

## Niche Folders
- 05-Leads/riads-hotels/
- 05-Leads/clinics/

## Rules
- warm-leads.md = status is warm, proposal, or closed
- cold-leads.md = status is new, contacted, or dead
- Update after every call/visit session
