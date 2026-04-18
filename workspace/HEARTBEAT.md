# HEARTBEAT.md — Emma's Heartbeat Checklist

## Active Checks (rotate through, 2-4x daily)

When heartbeat fires, check ONE of these per cycle (not all at once):

### Email Check
- Check if any urgent emails arrived
- If urgent → forward to human
- If nothing urgent → HEARTBEAT_OK

### Memory Maintenance (every 3rd heartbeat)
- Read `memory/` directory for recent files
- Promote significant items to `MEMORY.md`
- Archive logs older than 7 days

### Project Sync (every 5th heartbeat)
- Check git status in active project directories
- Note any changes worth mentioning

## Stay Quiet When:
- Time is 23:00-08:00 local (sleep hours)
- Last check was <20 minutes ago
- Nothing actionable found

## Track State
Update `memory/heartbeat-state.json` after each check.
