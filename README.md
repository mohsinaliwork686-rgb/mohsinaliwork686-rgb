### Hi, I'm Mohsin

I'm a software engineer at SoftBuilds. There I built the subscription enforcement, billing and licensing for
[AI Refinery](https://www.airefinery.co/), a self-hosted LLM platform on Kubernetes and Azure, and
healthcare order fulfilment systems on Azure and .NET. In my own time I build open-source tools for
applications that use language models, and finish one project a week.

**Projects**

- [rotadesk](https://github.com/mohsinaliwork686-rgb/rotadesk): staff scheduling for small
  businesses, one app for many of them, in ASP.NET Core and React
  ([try it](https://rotadesk.onrender.com))
- [hookline](https://github.com/mohsinaliwork686-rgb/hookline): delivers webhooks reliably, even when
  the receiver is down: stored first, signed, retried by workers sharing PostgreSQL, with a dashboard
- [grounded](https://github.com/mohsinaliwork686-rgb/grounded): document Q&A where every sentence
  cites its passage and a local NLI model checks it, and it says so when the documents don't cover
  the question
- [llm-router](https://github.com/mohsinaliwork686-rgb/llm-router): one endpoint for many language
  models, with a spending cap that holds under concurrent load
- [semcache](https://github.com/mohsinaliwork686-rgb/semcache): caches model answers by meaning,
  with a benchmark that shows where it starts giving wrong answers
- [evalboard](https://github.com/mohsinaliwork686-rgb/evalboard): compares two eval runs case by
  case and shows exactly what got worse ([try it](https://mohsinaliwork686-rgb.github.io/evalboard/))
- [ragsweep](https://github.com/mohsinaliwork686-rgb/ragsweep): measures which retrieval settings
  actually find the right passage
- [helmdrift](https://github.com/mohsinaliwork686-rgb/helmdrift): shows what was changed by hand in
  a Kubernetes cluster, and which tool changed it
- [promptlint](https://github.com/mohsinaliwork686-rgb/promptlint): a linter for LLM prompt
  templates
- [contextlab](https://github.com/mohsinaliwork686-rgb/contextlab): plans a context window before
  it overflows ([try it](https://mohsinaliwork686-rgb.github.io/contextlab/))

**Contributions**

- [StackExchange.Redis](https://github.com/StackExchange/StackExchange.Redis/pull/3313): fixed
  batched commands missing from the client's profiler; shipped in release 3.4.29
- [Swashbuckle.AspNetCore](https://github.com/domaindrivendev/Swashbuckle.AspNetCore/pull/4245): fixed
  two crashes in OpenAPI generation with inheritance, for generic subclasses and for
  [non-public Newtonsoft members](https://github.com/domaindrivendev/Swashbuckle.AspNetCore/pull/4244),
  and marked [read-only](https://github.com/domaindrivendev/Swashbuckle.AspNetCore/pull/4246) and
  [immutable](https://github.com/domaindrivendev/Swashbuckle.AspNetCore/pull/4272) sets as unique,
  and [stopped document filters' edits leaking into later requests](https://github.com/domaindrivendev/Swashbuckle.AspNetCore/pull/4273);
  the first three shipped in v11.0.0
- [System.IO.Abstractions](https://github.com/TestableIO/System.IO.Abstractions/pull/1591): fixed the
  mock file system naming the Unix root drive `/:\` and listing it twice; shipped in v23.0.1
- [TUnit](https://github.com/thomhurst/TUnit/pull/7799): fixed `IsEquivalentTo` reporting an object
  as not equivalent to itself; shipped in v1.86.6
- [Umbraco CMS](https://github.com/umbraco/Umbraco-CMS/pull/24662): made the Management API return a
  400 instead of a 500 for multilingual content created without any language variants, and
  [stopped a new composition from giving the types built on it duplicate property aliases](https://github.com/umbraco/Umbraco-CMS/pull/24768)
- [graphql-code-generator](https://github.com/dotansimha/graphql-code-generator/pull/11106): fixed
  generated code that did not compile for a project with no queries yet, shipped in `client-preset`
  7.0.0, and [enums mapped to objects typed as `null`](https://github.com/dotansimha/graphql-code-generator/pull/11116)
  in resolvers, shipped in `typescript-resolvers` 7.0.1, and
  [utility types generated above the imports](https://github.com/dotansimha/graphql-code-generator/pull/11120),
  shipped in `typescript-operations` 7.0.2
- [Authlib](https://github.com/authlib/authlib/pull/1009): fixed expired `client_credentials` tokens
  not being renewed, and [renewed tokens losing `access_token_params`](https://github.com/authlib/authlib/pull/1026)
- [Tornado](https://github.com/tornadoweb/tornado/pull/3875): stopped adding `Vary: Accept-Encoding`
  to responses it never compresses, and fixed WSGI apps failing on
  [unusual `Host` headers](https://github.com/tornadoweb/tornado/pull/3865)
- [redis-py](https://github.com/redis/redis-py/pull/4466): documented the connection pool limit
  and `BlockingConnectionPool`

**Now:** agent-trace, which records what an AI agent did, step by step, and ci-timeline, which shows which CI step is actually making builds slow.

More about me and my work: [mohsinaliwork686-rgb.github.io](https://mohsinaliwork686-rgb.github.io)
