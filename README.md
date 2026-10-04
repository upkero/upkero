# Hi, I'm upkero 👋

I build AI agents that do actual work for a business: pick up the phone and book a table,
sell a package without inventing a discount, find the answer in a company's own documents
instead of making one up.

Most of my time goes into the less visible half. That means the backend the agent talks to,
the checks that stop it from promising what it can't deliver, and the tests that prove
those checks work.

## One example

Six repositories that work together as a single system:

- 📞 [**voice-agent-service**](https://github.com/upkero/voice-agent-service): call Mila, ask
  for a table for two tomorrow at 19:30, and the booking shows up in the database. Speaks
  Russian and English, and can run entirely on your own server.
- 💬 [**sales-agent-service**](https://github.com/upkero/sales-agent-service): a sales chat
  that goes from "hi" to a confirmed order. It never quotes a price it didn't get from the
  API, even when someone tries to talk it into a 90% discount.
- 📚 [**rag-chat-service**](https://github.com/upkero/rag-chat-service): answers questions
  from a knowledge base and shows where each answer came from. Ask it about the weather on
  Mars and it will tell you it doesn't know.
- 🧰 [**mcp-ops-agent**](https://github.com/upkero/mcp-ops-agent): an MCP server with five
  tools for an operations desk, plus an agent that uses them. "Find Tom Okafor and send him
  a quote for six sessions" is one request.
- 🗄️ [**ops-core-api**](https://github.com/upkero/ops-core-api): the backend all of the
  above share. Customers, bookings, prices and document search on FastAPI, PostgreSQL and
  pgvector.
- 🌐 [**portfolio-site**](https://github.com/upkero/portfolio-site): my site, where each of
  these runs as a live demo you can try.

## Get in touch ✉️

If you want something like this for your business, or just want to talk it through:
[upkero@icloud.com](mailto:upkero@icloud.com)
