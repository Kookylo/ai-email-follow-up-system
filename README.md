# AI Email Follow-up System

## Lead Nurture Email Sequence

This project implements an automated email follow-up system using n8n workflow automation. The system is designed to nurture leads through a strategic email sequence over a 14-day period.

### Features

- **Webhook Integration**: Captures new leads via a webhook endpoint
- **Data Processing**: Structures and stores lead data
- **Google Sheets Integration**: Maintains lead records in a spreadsheet
- **Automated Email Sequence**:
  - Day 0: Welcome email
  - Day 3: Pain point email
  - Day 7: Case study email
  - Day 14: Final offer email with call-to-action
- **Status Tracking**: Updates lead status upon sequence completion

### Setup Requirements

- n8n instance
- SMTP email account
- Google Sheets API access

### Implementation

The workflow is defined in the `lead-nurture-email-sequence.json` file, which can be imported into n8n.

### How It Works

1. A new lead submits their information
2. Lead data is processed and stored in Google Sheets
3. The automated email sequence begins
4. Lead status is updated after the sequence completes

### Customization

Email templates can be customized to match your brand voice and specific offerings. The timing between emails can also be adjusted based on your sales cycle.