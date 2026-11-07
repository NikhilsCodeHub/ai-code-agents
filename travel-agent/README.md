# Travel Agent

CrewAI vacation planner consumed through an MCP connector from any AI harness (Cursor, Claude Desktop, ChatGPT, and similar). There is no web interface in v1.

This folder is the only location for the Travel Agent product. Do not mix its docs or code with the rest of this repository.

## Product requirements

The full product specification is in [product_requirements/PRD.md](product_requirements/PRD.md).

It covers:

- Product vision, goals, and personas
- Human-in-the-loop interview catalog
- Destination, flight, hotel, and car rental agents
- MCP tool and resource contract
- User stories with acceptance criteria
- Non-functional requirements, security, and later phases

## Status

Documentation only. Application code (CrewAI flows, MCP server, provider adapters) will be added in this folder in later work.

## Target layout (not built yet)

```
travel-agent/
  product_requirements/PRD.md
  src/travel_agent/          # mcp_server, crew, flows, agents, tools, providers
  tests/
```
