
#### Example Request
```bash
curl \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"description":"acme devices","domain":"connect.acme.com"}' \
https://api.ngrok.com/agent_ingresses