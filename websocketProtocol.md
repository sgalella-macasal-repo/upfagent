.json with two fields: 'type' and 'content'

Initialize agent when someone comes near the totem
{"type": "start", "content": }

End agent when people leaves he area
{"type": "end", "content": }

Send
{"type": "request", "content": "text containing what the agent says"}

Initialize agent when someone comes near the totem
{"type": "response", "content": "text containing the answer of the user" }
