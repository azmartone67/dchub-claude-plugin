# DC Hub — Claude Code plugin

Data center, power grid and energy data for Claude Code: facilities, markets, interconnection queues, electricity prices, fiber, gas, site risk and incentives, each with a source and date.

The plugin connects Claude Code to DC Hub's remote MCP server at https://dchub.cloud/mcp/claude. It has 67 read-only tools. Every result carries an as-of date and a citation. Without a DC Hub account some results are previews: withheld fields are marked, and the result says so. For tools that need an account, Claude prompts you to sign in with DC Hub.

Install: `/plugin marketplace add azmartone67/dchub-claude-plugin`, or copy `.mcp.json` into your project.

Skills: four workflow skills turn the tools into finished work. `dchub-site-screen` writes a one-page go / caution / no-go screen for a site; `dchub-time-to-power-memo` writes a dated time-to-power memo for a US state or ISO; `dchub-market-compare` compares two to four markets and recommends one; `dchub-capacity-sourcing` finds colocation, turnkey, powered shell or land to lease and requests a provider introduction with your approval.

Try: "Which US markets can take a 200 MW AI campus soonest?" or "What is in the ERCOT interconnection queue?"

- Website: https://dchub.cloud
- Documentation: https://dchub.cloud/integrations/mcp
- Server source: https://github.com/azmartone67/dchub-mcp-server
- Privacy: https://dchub.cloud/privacy
- Support: https://dchub.cloud/support · jonathan@dchub.cloud

License: MIT
