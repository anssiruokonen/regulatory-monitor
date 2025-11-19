# Regulatory Monitor

Automated monitoring for EU regulatory releases and updates.

## Currently Monitoring

- **EU Digital Omnibus** - Data, cybersecurity, and AI regulation simplification package

## How It Works

GitHub Actions runs a scheduled workflow that:
1. Checks official EU sources for updates
2. Monitors EUR-Lex for new legislative proposals
3. Sends notifications when changes are detected

## Getting Started

1. Add your notification settings (email, webhook, etc.)
2. The workflow runs daily at 9 AM UTC
3. Check the Actions tab to see monitoring results

## Configuration

Edit the workflow file in `.github/workflows/` to customize:
- Check frequency
- Monitoring URLs
- Notification channels
