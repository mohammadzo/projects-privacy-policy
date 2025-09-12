# Privacy Policy for Acquia Service Cloud Extension

**Effective Date**: September 12, 2025  
**Version**: 2.6.1

## Overview

The Acquia Service Cloud Extension ("Extension") is an internal productivity tool designed exclusively for Acquia employees to enhance their experience with the Acquia Service Cloud platform. This extension is distributed only to Acquia employees through private Chrome Web Store channels and provides advanced functionality, performance monitoring, time tracking, and improved user interface capabilities for internal support operations.

## Data Collection and Usage

### Information We Collect

This internal employee extension collects the following types of data:

**Authentication Information:**
- Toggl API tokens (when employees opt to use timer integration features)
- Stored locally using Chrome's secure storage API
- Used only to authenticate with the employee's own Toggl account for time tracking

**User Activity Data:**
- Detection of when employees view Acquia Service Cloud case pages (to enable timer functionality)
- Monitoring of page navigation within Acquia Service Cloud (for intelligent link management)
- Timer start/stop events for time tracking on client cases
- Logout event detection for security compliance and timer cleanup
- This monitoring is limited to Acquia Service Cloud domains only

**Website Content:**
- Case numbers and titles from Acquia Service Cloud pages (for timer descriptions and AI prompt preparation)
- Page structure information (to apply themes and visual enhancements)
- DOM elements (for debugging and performance monitoring)
- Page content for automated refresh and interface improvements
- Content access is restricted to Acquia Service Cloud domains only

**Local Storage Data:**
- User interface themes and customization preferences
- Extension settings and feature configurations
- Timer state for session persistence across page reloads
- Employee preferences for link grabber behavior

### Information We Do NOT Collect

- Personal identifying information (names, addresses, emails, phone numbers)
- Health information
- Financial or payment information
- Personal communications (emails, texts, chat messages)
- Location data or IP addresses
- Web browsing history outside of Acquia Service Cloud
- Authentication credentials other than optional Toggl API tokens

### How We Use Information

All data processing occurs locally on employee devices for internal productivity enhancement:

**Core Functionality:**
- Enhance the Acquia Service Cloud user interface for support staff
- Provide performance monitoring tools for internal development
- Apply themes and visual improvements for better employee experience
- Enable intelligent tab management to reduce clutter during support workflows

**Timer Integration (Optional):**
- Track time spent on client cases when employees enable Toggl integration
- Automatically populate timer descriptions with case information
- Provide accurate time tracking for billing and productivity analysis
- Sync with employee's personal Toggl workspace for time management

**Data Processing Principles:**
- All data processing occurs locally on employee devices
- No data is transmitted to external servers except optional Toggl API calls
- Extension operates with minimal required permissions
- Data collection is limited to functionality essential for internal productivity

### External Service Integration

**Toggl Time Tracking API (Optional):**
- When employees choose to enable timer integration, the extension communicates with api.track.toggl.com
- API calls are made using employee-provided authentication tokens
- Data transmitted includes case numbers and timer information for time tracking
- Employees have full control over this integration and can disable it at any time
- No other external services receive any data from this extension

## Data Sharing and Transfer

**Internal Use Only:**
- This extension is designed exclusively for internal Acquia employee use
- No data is shared with third parties outside of optional employee-controlled Toggl integration
- No data is sold, rented, or traded with any external entities
- All functionality operates within Acquia's organizational boundaries

**Limited Use Compliance:**
- Data is used solely for the extension's single purpose of enhancing Acquia Service Cloud productivity
- No data is used for advertising, marketing, or any purpose unrelated to internal productivity
- Data transfer is limited to employee-initiated Toggl API calls for time tracking
- No human access to user data except for technical support when explicitly requested by employees

## Permissions Used

The extension requests the following permissions for internal productivity functionality:

- **`activeTab`**: Access currently active Acquia Service Cloud tab when employees interact with extension
- **`tabs`**: Manage multiple Service Cloud tabs for intelligent link redirection and case management
- **`scripting`**: Inject productivity enhancement scripts and themes into Service Cloud pages
- **`storage`**: Store employee preferences, settings, and timer state locally on device
- **`alarms`**: Provide timer reminders and periodic maintenance for optimal performance
- **`webNavigation`** (optional): Enhanced link management for better tab organization
- **Host permissions**: Access to Acquia Service Cloud domains and optional Toggl API for timer integration

All permissions are used exclusively for internal employee productivity enhancement and follow the principle of least privilege.

## Data Security and Encryption

**Local Data Protection:**
- All employee data is stored locally using Chrome's secure storage APIs
- Extension settings and preferences are encrypted at rest by Chrome's security model
- Timer state and configurations are protected using browser-level security

**Network Security:**
- Toggl API communications use HTTPS encryption for data in transit
- No other external network requests are made by the extension
- All internal functionality operates without network transmission

**Access Controls:**
- Extension is distributed only through private Chrome Web Store channels to verified Acquia employees
- No unauthorized access to extension functionality
- Employee-controlled optional features with explicit consent requirements

## Data Retention and User Control

**Data Retention:**
- Extension settings and preferences are stored locally until manually cleared by employees
- Timer state data is retained only as long as needed for session persistence
- Toggl API tokens are stored until employees remove them or uninstall the extension
- Uninstalling the extension removes all associated local data immediately

**Employee Rights and Controls:**
- Full control over all optional features (timer integration, enhanced link management)
- Ability to disable specific extension permissions through Chrome's extension settings
- Access to locally stored extension data through Chrome's developer tools
- Right to delete all extension data by uninstalling the extension
- Control over Toggl integration and associated data sharing

**Data Modification and Deletion:**
- Employees can modify or delete extension settings at any time through the options interface
- Timer integration can be disabled, removing all associated tokens and configurations
- Chrome's extension management provides additional data control options
- Complete data removal is achieved through extension uninstallation

## Limited Use Disclosure

This extension complies with Chrome Web Store Limited Use requirements:

**Single Purpose:** This internal tool serves the single purpose of enhancing Acquia employee productivity within Service Cloud environments.

**Minimal Data Use:** Data collection is limited to what is necessary for core productivity features and is used only for the intended functionality.

**No Advertising:** No data is used for advertising, marketing, or any commercial purposes outside of internal productivity enhancement.

**Secure Handling:** All data is handled securely with encryption for any network transmission and secure local storage.

**Employee Consent:** Optional features requiring additional data access (like Toggl integration) require explicit employee consent and can be disabled at any time.

## Changes to Privacy Policy

We may update this privacy policy to reflect changes in our practices, new features, or for legal and regulatory compliance. Acquia employees will be notified of any material changes through:

- Extension update notifications in Chrome
- Internal Acquia communication channels
- Updated version information in the extension interface
- Prominent disclosure for any changes affecting data collection or usage

Continued use of the extension after policy updates constitutes acceptance of the revised privacy policy.

## Contact Information

For questions about this privacy policy or the extension:

- **Developer**: Acquia Service Cloud Development Team (Internal)
- **Internal Support**: Contact through Acquia's internal support channels
- **Repository**: https://github.com/mohammadzo/service-cloud-chrome-extension
- **Issues**: For technical issues, use internal Acquia development channels

## Legal Compliance

This internal employee extension complies with:

- Chrome Web Store Developer Program Policies and Limited Use requirements
- Chrome Extension Manifest V3 security and privacy requirements
- Acquia's internal data protection and security policies
- Data minimization principles and employee privacy protection
- GDPR and applicable privacy regulations for employee data

## Employee Privacy Rights

As an internal Acquia tool, employees have additional rights under organizational policies:

- Right to know what data is collected and how it's used
- Right to access their locally stored extension data
- Right to modify or delete extension data at any time
- Right to disable or uninstall the extension without affecting employment
- Right to report privacy concerns through internal Acquia channels
- Protection under Acquia's employee privacy policies and procedures

---

_This privacy policy applies exclusively to the internal Acquia Service Cloud Extension and does not cover the privacy practices of the Acquia Service Cloud platform, Toggl services, or other Acquia systems and tools._
