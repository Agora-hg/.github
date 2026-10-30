## Agora — packaging suppliers, matched to the task

Agora is a B2B platform for buying transport and industrial packaging in Moscow. A buyer describes what they need, and Agora returns real suppliers from its catalogue with an honest match score. The AI does not invent suppliers.

**Demo:** [agora-demo-cyan.vercel.app](https://agora-demo-cyan.vercel.app) · **Overview and architecture:** [sofya0206/agora-showcase](https://github.com/sofya0206/agora-showcase) · Accelerators: *Ya v Dele*, *Innovators of Moscow*

| Repository | Role |
| --- | --- |
| agora | Storefront and buyer AI chat (Next.js) |
| agora-back | REST API, catalogue, grounded AI matching (Laravel, PostgreSQL) |
| [agora-admin](https://github.com/Agora-hg/agora-admin) | Admin panel: suppliers, offers, AI test bench (React) |
| agora-tgbot | Telegram notifications for admins and suppliers (FastAPI) |
| agora-leads | Supplier lead collector and classifier (Python) |
| [agora-catalog](https://github.com/Agora-hg/agora-catalog) | SEO catalogue that tests search demand (Next.js, Drizzle) |

**Team:** Sofia Guliaeva (co-founder, frontend) · [Rauan228](https://github.com/Rauan228) (backend, admin, bot, leads)
