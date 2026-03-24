# Product
Build a production-grade web app for adult-only romantic roleplay chat between consenting adults.

# Hard boundaries
- Adults only
- No minors
- No illegal sexual content
- No coercive or non-consensual content
- No incest
- No bestiality
- No real-person impersonation
- No client-side API keys
- Keep product copy tasteful and premium, not graphic

# Business goal
Ship a polished web MVP that can later become a paid commercial product.

# Stack
- Next.js 15
- TypeScript
- Tailwind CSS
- shadcn/ui
- PostgreSQL
- Prisma
- Redis
- NextAuth or equivalent auth
- xAI API on the server side only
- Sentry
- Stripe
- Vitest
- Playwright

# Product requirements
- Premium dark UI
- Mobile-first responsive design
- Auth
- Age gate
- Chat streaming
- Conversation history
- Retry / cancel / error states
- Settings page
- Subscription page
- Admin-friendly logging
- Deployable to Vercel

# Engineering rules
- Prefer production-oriented architecture, not demo shortcuts
- Keep code typed
- Add tests for new server logic
- Run lint, typecheck, build, and tests after each milestone
- Do not expose secrets in frontend
- Use environment variables and document them in README

# Definition of done
- App boots locally
- Auth flow works
- Chat page works
- Streaming route exists
- Database schema exists
- README is complete
- No TODO placeholders in critical paths

# Skill policy
Before starting implementation, inspect available Skills and prefer using installed or repo-local Skills when they match the task.

If no suitable Skill exists for a recurring workflow, create a new reusable repo-local Skill instead of solving it only as a one-off change.

Project Skills should be stored in the repository and reused across future milestones.