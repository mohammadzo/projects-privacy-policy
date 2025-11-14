# Privacy Policy - Daily Drop Chrome Extension

**Last Updated:** November 14, 2025

## Overview

Daily Drop is committed to protecting your privacy. This extension does not collect, store, transmit, or share any personal information with external servers or third parties.

## Data Collection

**Daily Drop does NOT collect any user data.**

All data you enter (messages, schedules, settings) is stored exclusively in your local browser storage and never leaves your device.

## Data Storage

### What is Stored Locally

The following data is stored in your browser using Chrome's `chrome.storage.local` API:

- **Message Content**: Text messages you create for scheduling
- **Slack Channel URLs**: Channel URLs you configure for message delivery
- **Schedule Settings**: Time, days, and date range preferences
- **Send History**: Local log of when messages were sent (for display purposes only)
- **Extension Preferences**: UI settings and message presets

### Where Data is Stored

All data is stored locally in your Chrome browser profile:
- Location: Chrome's local storage (managed by the browser)
- Accessible only by: You and this extension
- Not synchronized: Data stays on your device unless you enable Chrome Sync

## Data Transmission

**Daily Drop does NOT transmit any data to external servers.**

The extension operates entirely within your browser and only interacts with:
- **Slack's web interface** (app.slack.com) - to send messages you've scheduled
- **Your local browser storage** - to save your settings and messages

No data is sent to:
- Analytics services
- Advertising networks
- Third-party servers
- The extension developer
- Acquia servers
- Any external services

## Permissions Explained

Daily Drop requests the following Chrome permissions:

### `storage`
**Purpose**: Save your messages and settings locally in your browser  
**Data Access**: Only data you explicitly enter into the extension  
**Privacy Impact**: None - data never leaves your device

### `alarms`
**Purpose**: Schedule message sending at times you specify  
**Data Access**: None - only schedules timers  
**Privacy Impact**: None - no data access

### `activeTab`
**Purpose**: Interact with Slack tabs when sending messages  
**Data Access**: Limited to Slack tabs when messages are being sent  
**Privacy Impact**: Minimal - only accesses Slack during scheduled sends

### `tabs`
**Purpose**: Open and manage Slack tabs for message sending  
**Data Access**: Can see when Slack tabs are open  
**Privacy Impact**: Minimal - only used to manage Slack tabs

### `scripting`
**Purpose**: Simulate typing in Slack's message input field  
**Data Access**: Interacts with Slack's DOM to send messages  
**Privacy Impact**: Minimal - mimics manual user actions in Slack

### `host_permissions` (https://app.slack.com/*)
**Purpose**: Access Slack's web interface to send messages  
**Data Access**: Limited to Slack web app pages  
**Privacy Impact**: Extension can interact with Slack only - no other websites

## Third-Party Services

Daily Drop does NOT use any third-party services, including:
- No analytics (Google Analytics, etc.)
- No crash reporting
- No advertising networks
- No tracking pixels
- No external APIs
- No cloud storage

## Slack Integration

Daily Drop interacts with Slack by:
- Simulating user typing in Slack's web interface
- Using your existing Slack login session
- Operating exactly as if you typed messages manually

**Important**: 
- Daily Drop does NOT use Slack's API
- No Slack tokens or credentials are stored
- Messages appear as if you sent them manually
- Uses your existing Slack authentication

## Data Security

Since all data is stored locally in your browser:
- **Encryption**: Managed by Chrome's storage system
- **Access Control**: Only you can access your browser profile
- **Data Isolation**: Each Chrome profile has separate storage
- **No External Risk**: Data cannot be intercepted in transit (because it never leaves your device)

## Data Retention

- **Storage Duration**: Data remains until you clear extension data or uninstall
- **Deletion**: Uninstalling the extension deletes all stored data
- **Manual Deletion**: Clear data via extension settings or Chrome's extension management

## Your Rights

You have complete control over your data:
- **Access**: View all stored data through the extension interface
- **Export**: Export messages to JSON files at any time
- **Delete**: Clear all data by uninstalling or resetting the extension
- **Control**: Disable or remove the extension anytime

## Children's Privacy

Daily Drop does not knowingly collect any information from anyone, including children under 13. Since no data is collected or transmitted, COPPA compliance is inherent.

## Changes to This Policy

If we update this privacy policy, we will:
- Update the "Last Updated" date at the top
- Notify users through extension updates
- Maintain policy history on GitHub

## Open Source

Daily Drop is open source software. You can:
- Review the complete source code on GitHub
- Verify no data collection occurs
- Submit issues or improvements
- Fork and modify the code

**Repository**: https://github.com/acquia/daily-drop-chrome-extension

## Contact

For privacy concerns or questions:
- **GitHub Issues**: https://github.com/acquia/daily-drop-chrome-extension/issues
- **Developer**: Mohammad Zomorodian
- **Organization**: Acquia

## Compliance

Daily Drop complies with:
- Chrome Web Store Developer Program Policies
- General Data Protection Regulation (GDPR) - by not collecting data
- California Consumer Privacy Act (CCPA) - by not collecting data
- Chrome Extension Manifest V3 privacy requirements

## Summary

**In Plain English:**
- We don't collect your data
- We don't track you
- We don't share anything
- Everything stays on your computer
- We don't use analytics
- We're open source - verify it yourself!

---

**Questions?** Open an issue on our [GitHub repository](https://github.com/acquia/daily-drop-chrome-extension/issues).

**License**: MIT License - see [LICENSE](LICENSE) file
