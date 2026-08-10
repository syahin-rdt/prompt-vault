SEB Chatbot (N8N how to deploy production - checklist)
1. Duplicate SEB_Chatbot flows.
2. Check Webhook is pointing to the production endpoint.
3. Make sure tools are pointing to right flow.
4. Salesforce production endpoint in genesys node.
5. Genesys integration id.

Chatbot State:
Last deployment: 5-8-2026
Pending changes from DEV(flow): None
Detail:
* Update Orchestrator, Customer Service and General Knowledge agents prompt.

Voicebot State:
Last deployment: 27-7-2026
Pending changes from DEV(flow): Direct case number follow up to include closed cased.
Detail:
* user mid response interruption (code)
* Direct case number follow up to include closed cased (flow)