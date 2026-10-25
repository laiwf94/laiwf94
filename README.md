### Woon Fei Lai

Distributed systems engineer and tech lead. I build the parts of a system people only notice when they break: how requests are routed and cached, how services fail over, and how a system decides who you are and what you're allowed to do. I also build AI-powered products and commerce platforms end to end.

**Open source**

Traffic and the edge

- [steer](https://github.com/laiwf94/steer): an HTTP load balancer that keeps serving through failures, with health checks, outlier ejection, priority failover, retry budgets and Maglev hashing. Go.
- [relink](https://github.com/laiwf94/relink): a link shortener whose redirects run at the edge from a core compiled to WebAssembly, backed by Postgres at the origin. Rust.

Identity and access

- [grantd](https://github.com/laiwf94/grantd): an authorization service in the style of Google's Zanzibar, with a schema language, consistent snapshots and a crash-safe write-ahead log. Go, standard library only.
- [wicket](https://github.com/laiwf94/wicket): single sign-on in front of any app, OIDC and SAML through nginx, Traefik or Envoy forward-auth. Go.
- [toolgate](https://github.com/laiwf94/toolgate): a security gateway for AI agent tool calls over MCP, with default-deny policy, approvals, rate limits and a tamper-evident audit log. Go.

Money

- [ledgerd](https://github.com/laiwf94/ledgerd): a double-entry ledger with two-phase transfers, idempotency keys, reconciliation and group commit. Go.
- [payflow](https://github.com/laiwf94/payflow): an order payment saga that undoes what it already did when a step fails, with a transactional outbox to Kafka and crash recovery tests. Java and Spring Boot.

Shipping safely

- [flagship](https://github.com/laiwf94/flagship): feature flags and gradual rollouts, evaluated locally in the SDKs and kept in sync over SSE, with a React admin UI. TypeScript.
- [evalkit](https://github.com/laiwf94/evalkit): tells you whether a change made an AI feature better or worse, with an LLM judge, paired statistics and a CI gate. Python.

**Work with:** Go · Java · TypeScript · Rust · Python · AWS · Kubernetes · Terraform · PostgreSQL · Redis

[woonfei.com](https://woonfei.com) · [LinkedIn](https://www.linkedin.com/in/woonfeilai/)
