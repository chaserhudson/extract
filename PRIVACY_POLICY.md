# Privacy Policy for Extract Chrome Extension

**Last Updated:** January 2025

## Overview

Extract is a Chrome extension that helps you extract and organize information from web pages. We are committed to protecting your privacy and being transparent about our data practices.

**The short version: We don't collect, store, or transmit any of your data. Everything stays on your device.**

## Data Collection

### What We DON'T Collect

- We do **not** collect any personal information
- - We do **not** collect browsing history
  - - We do **not** collect or transmit the content you extract
    - - We do **not** use analytics or tracking services
      - - We do **not** use cookies
        - - We do **not** have servers that receive your data
          - - We do **not** share any data with third parties
           
            - ### What The Extension Accesses
           
            - When you click "Extract" on a webpage, the extension accesses:
           
            - - The current webpage's content (to extract links, text, emails, etc.)
              - - Your browser's local storage (to save extracted data on your device)
               
                - **This data never leaves your device.**
               
                - ## Data Storage
               
                - All extracted data is stored locally in your browser using Chrome's built-in storage API (`chrome.storage.local`). This means:
               
                - - Your data is stored only on your computer
                  - - Your data is tied to your Chrome profile
                    - - Your data can be deleted at any time through the extension's settings
                      - - Your data is not synced to any external servers
                        - - Uninstalling the extension removes all stored data
                         
                          - ## Data Retention
                         
                          - You control how long your data is kept:
                         
                          - - **Default:** Data is kept until you manually delete it
                            - - **Optional:** You can set automatic deletion after 30, 60, or 90 days
                              - - **Backup/Restore:** You can export your data as a JSON file and import it later
                               
                                - ## Permissions Explained
                               
                                - The extension requests the following permissions:
                               
                                - | Permission | Why It's Needed |
                                - |------------|-----------------|
                                - | `activeTab` | To read the content of the current webpage when you click Extract |
                                - | `tabs` | To detect when you switch tabs so the side panel can update |
                                - | `storage` | To save extracted data locally on your device |
                                - | `clipboardWrite` | To copy data to your clipboard when you click Copy |
                                - | `sidePanel` | To display the extension interface in Chrome's side panel |
                                - | `alarms` | To run periodic cleanup of expired data (if auto-delete is enabled) |
                               
                                - We request only the minimum permissions necessary for the extension to function.
                               
                                - ## Third-Party Services
                               
                                - Extract does not use any third-party services, APIs, or analytics tools. The extension operates entirely offline after installation.
                               
                                - ## Children's Privacy
                               
                                - Extract does not knowingly collect any information from children under 13 years of age. The extension does not collect information from anyone.
                               
                                - ## Changes to This Policy
                               
                                - If we make changes to this privacy policy, we will update the "Last Updated" date at the top. Significant changes will be noted in the extension's update notes.
                               
                                - ## Open Source
                               
                                - Extract is open source. You can review the complete source code to verify our privacy practices:
                               
                                - [GitHub Repository](https://github.com/chaserhudson/extract)
                               
                                - ## Contact
                               
                                - If you have questions about this privacy policy or the extension, please open an issue on our GitHub repository.
                               
                                - ## Your Rights
                               
                                - Since we don't collect any data, there is no personal data for us to provide, modify, or delete. All your data is stored locally on your device and is fully under your control.
                               
                                - ---

                                **Summary:** Extract is a privacy-first extension. Your data stays on your device. We have no servers, no tracking, no analytics. You are in complete control of your information.
