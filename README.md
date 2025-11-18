# awesome-in-agent-payment
A Resource Collection of Awesome In Agent Payment and Purchase Resources

| Brand |	Primary Payment API/Platform | Agent MCP (Model Context Protocol) Integration |
| ---- | ---- | ----- |
| PayPal	| Orders API (v2): The core REST API for online payments (Create, Authorize, Capture, Refund). |	PayPal MCP Server: A dedicated protocol/server to integrate PayPal business features (like  invoicing, transaction lookups) with AI Agents/LLMs. https://docs.paypal.ai/developer/tools/ai/mcp-quickstart |
| Stripe | Stripe API https://docs.stripe.com/ | Stripe MCP Server https://docs.stripe.com/mcp |
| Alipay+ |	Alipay+ Unified Gateway API: The platform for cross-border mobile and in-store QR code payments (including the Multi-Currency Pricing (MCP) feature). |	Alipay+ MCP Server: A specialized server built on the MCP standard to expose core payment operations (Create Payment, Query Status, Refund) to AI assistants. https://github.com/alipay/global-alipayplus-mcp
| WeChat Pay |	WeChat Pay API (Global/V3): APIs for various payment scenarios (In-App, JSAPI, Native QR Code). Often integrated via a Payment Service Provider (PSP). |	Not directly available/publicized as a native WeChat Pay MCP server. Integrations are usually managed through PSPs who may offer their own custom tools for AI assistants.
