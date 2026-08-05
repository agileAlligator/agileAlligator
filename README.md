### hi, i'm Avneesh

solutions engineer at Gruve. i build secure MCP servers for clients and harden the agentic layer against prompt injection, tool misuse, and privilege abuse.

one idea runs through all of it: **the model can't police itself.** a guardrail in a model's judgment can be talked past. a guardrail in deterministic server code holds, whatever the model is convinced to do. so the controls live in the server, not the prompt.

**things i've built**

- **mcploitable.** the "Metasploitable of MCP": deliberately vulnerable servers mapped to the OWASP Agentic Top 10, on an L0 to L3 control ladder. 105 attempts at the wall, zero through.
- **my résumé is an MCP server.** a live public server you can point an agent at. the naive build leaks a canary to a path traversal. the hardened build refuses.
- **the lab.** six interactive exhibits, each testing one claim a different way: a guardrail in the model's judgment fails, a guardrail in code holds.

want to try it? point an agent at my résumé:

```
claude mcp add --transport http avneesh-resume https://mcp.apkasture02.workers.dev/mcp
```

before this i was a SOC analyst (threat hunting, detection engineering) and a digital forensics intern. ISC2 Certified in Cybersecurity.

→ **[avneeshk.me](https://avneeshk.me)** · [field notes](https://avneeshk.me/blog) · [the lab](https://avneeshk.me/lab)
