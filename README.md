# Lighthouse for Cursor

[Lighthouse](https://lighthouseai.co) monitors the business metrics in your data warehouse (Snowflake, BigQuery, Postgres, Redshift, Mixpanel and more) and alerts your team in Slack when they move.

This plugin connects Cursor to the Lighthouse MCP server, so the agent can work with your Lighthouse organization:

- List metrics, data sources and data sets, and read their configuration
- Look at a metric's history, recent runs and which segments matched an alert
- Test a new metric against your data before saving it
- Create and update metrics, and run a metric on demand
- Acknowledge or resolve alert results

## Sign in

The first time Cursor connects, it opens the Lighthouse sign-in page in your browser. Sign in, pick one organization and approve the connection. The agent acts as you: it can only do what your Lighthouse role allows, and a new connection starts with read access. You can disconnect it any time from Settings, API & Agents in Lighthouse.

You need a Lighthouse account. [Start for free](https://lighthouseai.co).

## Documentation

- [MCP server docs](https://lighthouseai.co/docs/mcp)
- [Privacy policy](https://lighthouseai.co/privacy-policy)
- Support: admin@lighthouseai.co

## License

MIT
