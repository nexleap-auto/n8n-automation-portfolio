# GitHub OAuth2 Issue Sync

## What it does
This n8n workflow authenticates with GitHub using OAuth2, fetches open issues from a repository, and syncs them into a structured Notion database.

## Tech used
- n8n
- GitHub API (OAuth2)
- Notion API

## Workflow steps
1. Manual/Schedule trigger
2. HTTP Request node authenticated via Generic OAuth2 credential
3. Data formatting
4. Notion node creates/updates database entries

