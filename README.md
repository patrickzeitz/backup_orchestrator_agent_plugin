# Backup Orchestrator Agent Plugin

Public release channel for the WordPress agent plugin used by WP Pull Orchestrator.

This repository is for published artifacts only.

Do not develop plugin features here.

The plugin source of truth remains in the private main repository at:

- `legacy/wordpress_plugin/agent-backup/`

Files published here:

- `agent-backup.zip`
- `agent-backup-update.json`

WordPress-native updates resolve against the raw files on the `main` branch of this repository.

Repository:

- https://github.com/patrickzeitz/backup_orchestrator_agent_plugin

Typical workflow:

1. Change plugin code in the private main repository.
2. Publish fresh artifacts with `python scripts/admin/publish_agent_public_repo.py --write-readme`.
3. Commit and push the generated files in this repository.
