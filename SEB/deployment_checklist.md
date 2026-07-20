SEB Chatbot (N8N how to deploy production - checklist)
1. Duplicate SEB_Chatbot flows.
2. Check Webhook is pointing to the production endpoint.
3. Make sure tools are pointing to right flow.
4. Salesforce production endpoint in genesys node.
5. Genesys integration id.

Chatbot changes:
Status - deployment 20-7-2026
1. Disconnect validation response SAP flow and account check
2. Update Orchestrator and Customer Service prompt

Voicebot changes:
Status - deployment 7-7-2026 (#23)
* feat: transfer language based on conversation

* chores: supply interruption prompt

* feat: transfer categorization

* feat: use callers mobile number (#14)

* feat: bill copy flow use email from profile check

* chores: DTMR-golive-changes-irene (#15)

* chores: DTMR-golive-changes-irene

add Filler Words, DTMR enforcement, Remove "say digits one by one" + Passport handling, add Landline number format, update Numerical Hallucinations issue, structure the flow if got any ripple effect

* chores: enforce flow to capture CA last

---------

Co-authored-by: syahin-rdt <syahin@radiantcomm.com>

* fix: hardened description/prompt for unrequired mobile number tools

* chores: resolving "dollar" issue (#16)

update: ## Monetary Amounts + **Monetary tool outputs:**

* chores: changes  based on findings/feedback SEB (#18)

update ringgit table & DTMF path logic, remove loophole that potentially cause Bot to occasionally tell customer to say the digit one by one, other minor changes

* Revert "chores: changes  based on findings/feedback SEB (#18)"

This reverts commit 1217105.

* Refactor intermittent dtmf logic (#19)

* refactor: certain call session bot didn't capture DTMF

* fix: echo user input

* fix: update ringgit prompt (#20)

* fix: update ringgit prompt

* chores: minor change

---------

Co-authored-by: irenewong99 <irenewong@radiantcomm.com>

* fixed: region&station (#22)

---------

Co-authored-by: irenewong99 <irenewong@radiantcomm.com>