# Client Solutions Coach — Setup Guide
**For:** ChatGPT Enterprise Admin (Carlos)
**Time required:** ~20 minutes to launch, ongoing for knowledge uploads

---

## Why a Custom GPT, Not a Project

ChatGPT **Projects** are personal — each team member would maintain their own copy with their own files. A **Custom GPT** is shared org-wide, has persistent uploaded knowledge, and can be given a specific persona and instructions. For a team knowledge tool, Custom GPT wins.

---

## Step 1: Create the Custom GPT

1. Log into ChatGPT Enterprise at chat.openai.com
2. Click your profile icon → **My GPTs** → **Create a GPT**
3. Switch to **Configure** tab (not the chat-based builder)

**Fill in these fields:**

| Field | Value |
|---|---|
| **Name** | Client Solutions Coach |
| **Description** | Your team's institutional knowledge base. Ask about pilots, skills, articles, and best practices the team has collected. |
| **Instructions** | *(paste the full contents of `gpt-instructions/system-prompt.md`)* |

**Conversation starters:**
- "What should I keep in mind when setting up a pilot?"
- "Give me a checklist for executive storytelling"
- "What are the most common negotiation mistakes?"
- "Summarize our best guidance on discovery calls"

---

## Step 2: Upload Knowledge Files

Configure tab → **Knowledge** → **Upload files**

1. `knowledge/README.md`
2. `knowledge/pilot-call-template.md`
3. Completed knowledge files as the team creates them

---

## Step 3: Configure Sharing

Additional Settings → **Who can use this GPT** → **Everyone at [your org]** → Save

---

## Step 4: Share With the Team

> Hey team — we now have a **Client Solutions Coach** GPT in ChatGPT Enterprise. Go to Explore GPTs and search for it. Ask things like "What do we know about setting up a pilot?" or "What storytelling frameworks has the team collected?"
>
> If you learn something worth saving — drop it in [Slack channel] and we'll get it added.
