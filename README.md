# Agents, MCP & Amazon Bedrock AgentCore — Knowledge Guides

A focused, end-to-end learning library for moving from foundational AI-agent concepts to governed enterprise implementations on AWS.

**Live knowledge library:** https://kanizmadix.github.io/agents_mcp_guide/

## Guides

| Order | Guide | Coverage | Pages |
|---:|---|---|---:|
| 1 | [Agentic AI, MCP & Amazon Bedrock AgentCore — Field Guide](Agents_and_MCP_Field_Guide.pdf) | Mental models, agent loops, tools, memory, MCP, coding patterns, AgentCore and production considerations | 23 |
| 2 | [Guide 1 — Coding & AWS Foundations](Guide_1_Foundations_Coding_and_AWS.pdf) | Python, Pydantic, async, HTTP reliability, schemas, testing, AWS account setup and Bedrock foundations | 14 |
| 3 | [Guide 2 — Enterprise Agentic Build for Banking](Guide_2_Enterprise_Agentic_Build_Banking.pdf) | End-to-end disputes and fraud-triage agent, architecture, IAM, data, deployment, observability and go-live | 13 |
| 4 | [Guide 3 — Enterprise MCP Build for Banking](Guide_3_Enterprise_MCP_Build_Banking.pdf) | Governed MCP platform design, FastMCP services, transports, AgentCore Gateway, security and operations | 10 |

## Recommended learning path

1. Start with the **Field Guide** to build the complete mental model.
2. Complete **Guide 1** and use its readiness checks to close prerequisite gaps.
3. Build the production agent workflow in **Guide 2**.
4. Generalize tools into a governed enterprise MCP platform with **Guide 3**.

The examples are educational reference implementations. Adapt account IDs, ARNs, IAM boundaries, data classifications, security controls and operational procedures to your environment before production use.

## Hosting

The PDFs are stored directly in this repository. GitHub Pages publishes a static index through `.github/workflows/pages.yml`; no backend, API key or runtime service is required.

## License

See [LICENSE](LICENSE).
