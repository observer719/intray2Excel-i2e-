# Privacy Policy — Intray to Excel

_Last updated: 23 June 2026_

## Overview

Intray to Excel is a Chrome extension for internal use by University of Technology Sydney (UTS) staff. It reads student record data from the UTS Intray web application and copies it to the clipboard as a formatted row for pasting into a spreadsheet.

## Data Accessed

When you click the extension icon on a UTS Intray student record page, the extension reads the following fields displayed on that page:

- Student number
- Date of birth
- Full name
- Email address
- Phone number
- Mailing address (street, suburb/town, state, postcode, country)
- Course name
- Postage type

This data is already visible to you on the Intray page and is accessed solely to assemble the clipboard row.

## How Data Is Used

The data is used for one purpose only: to format and copy a tab-separated row to your device's clipboard so you can paste it into a spreadsheet. No other processing occurs.

## Data Storage and Transmission

- **No data is stored** by the extension. Nothing is written to local storage, cookies, or any database.
- **No data is transmitted** to any external server, third party, or remote endpoint. All processing happens locally in your browser.
- The clipboard contents are under your control and are cleared when you copy something else.

## Permissions

The extension requests the following Chrome permissions:

| Permission | Why it is needed |
| --- | --- |
| `activeTab` | To read the student record page you have open when you click the extension icon |
| `scripting` | To inject the data-extraction script into the active Intray tab |
| `clipboardWrite` | To write the formatted row to your clipboard |

No browsing history, identity data, or data from any other website is accessed.

## Third Parties

This extension does not share any data with third parties. It does not include analytics, advertising, or tracking code.

## Who Can Use This Extension

This extension is intended for authorised UTS staff who access the Intray system. It operates only on pages at `cfapps1.uts.edu.au`, which require UTS Okta authentication to reach.

## Contact

For questions about this extension or this privacy policy, contact the UTS team responsible for the Intray mailout process at **dachengramirez@gmail.com**.
