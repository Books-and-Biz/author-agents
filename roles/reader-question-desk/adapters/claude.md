# Claude installation

1. Extract this kit to a persistent folder and open it in Claude Desktop or Claude Code.
2. Ask Claude to read SKILL.md, select an author data folder, and run the first routine manually. Inspect the output and log.
3. For recurring work, make one scheduled task per routine with the prompt `Read <kit>/routines/<id>/SKILL.md and follow it for <author-data-folder>.` Use the author's time zone.
4. Test a real scheduled run. New Cowork tasks may run in the cloud; local file access requires the relevant desktop connection to be available. If the task cannot see the local folder, use Claude Code with a local scheduler or run manually.
5. Keep external-action approvals in effect; scheduling is permission to prepare the work, not to send or publish.
