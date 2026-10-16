> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is Angie's user-facing documentation site, built on [Mintlify](https://mintlify.com)
- Angie is a multi-tenant membership platform for alumni associations: each association ("network") gets its own branded site and admin console, and its members get a portal for dues, events, and communication
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Screenshots live in `/images/admin`, `/images/member`, and `/images/marketing`
- Use the Mintlify MCP server, `https://mcp.mintlify.com`, to edit content and settings via MCP
- Use the Mintlify docs MCP server, `https://www.mintlify.com/docs/mcp`, to query information about using Mintlify via MCP

## Terminology

- Use "association" or "network" for a tenant, not "organization" or "company"
- Use "member" for a regular user of an association, "admin" for an association's own staff, never "user" alone when either is meant
- Use "admin console" for the tenant admin area, "member portal" for the member-facing area
- Use "Angie's team" or "Angie" for the platform operator, never expose the internal name "Control"

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- No em dashes, no "delve"/"leverage"/"tapestry," no negative-parallelism ("it's not X, it's Y")

## Content boundaries

- Document the marketing site, association signup, the member portal, and the admin console only
- Never document Angie's internal operations console (referred to internally as "Control") — that's Angie staff tooling, not a platform feature associations or members use
- Don't include real member data, real association names, or real credentials in examples or screenshots — use disposable test accounts only
