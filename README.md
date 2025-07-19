# n8n Automated Daily Email Summary

A ready-to-import n8n workflow that sends you a **daily summary of your emails** – grouped by topic and powered by AI.

## What does this automation do?
- Every day at 7:00 AM, fetches all emails you received in the last 24 hours.
- Uses OpenAI (GPT) to analyze, summarize, and group your emails by topics (job, personal, promo, etc.).
- Sends you a neat summary to your email – in clean HTML, easy to read on desktop or mobile.

## Requirements
- An n8n instance running (Cloud, Docker, Onrender, etc).
- A connected Gmail account (OAuth2 setup in n8n).
- An OpenAI API key (or compatible model via n8n).
- Basic familiarity with importing workflows to n8n.

## How to use
1. Import the provided JSON file into your n8n instance.
2. Configure your Gmail credentials in the relevant nodes.
3. Add your OpenAI API credentials to the AI node.
4. (Optional) Change the recipient email address in the "Send a message" node.
5. Activate the workflow.
6. That's it – you’ll start getting daily email summaries at 7 AM!

## Tips
- You can adjust the summary hour by editing the Schedule Trigger node.
- Works best with personal Gmail accounts (not Google Workspace with heavy security).
- The AI will try to group and summarize as accurately as possible – always double-check your inbox for critical messages.

## Support
If you have questions, need help, or want to share improvements, reach out on LinkedIn or GitHub!
