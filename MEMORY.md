# Nexura Long-Term Memory
*This file is the agents permanent brain. Update it every session. If its not written here, it didnt happen.*

---

## Business Identity
- Company: Nexura Marketing (not yet registered on Companies House)
- Domain: nexuramarketing.co.uk
- Business email: nexura@nexuramarketing.co.uk
- Gmail: nexuramarketinguk@gmail.com
- What we are: A full-service AI-powered marketing agency for hospitality businesses
- What we are NOT: An Instagram posting tool. Instagram auto-posting is one feature of many.
- Stage: Pre-revenue. Testing with a few London pubs to prove the model works.
- Positioning: A tech company delivering everything a traditional marketing agency does but faster, smarter, and cheaper through AI. Think of us as the entire marketing department a hospitality business cant afford to hire.

## What We Do (Full Scope)
Nexura handles a clients entire marketing operation:
- Social media management: Instagram, Facebook, TikTok. Content creation, scheduling, posting, engagement
- Google Business Profile: posting updates, managing reviews, responding to customers, keeping profiles optimised
- Email marketing: campaigns, newsletters, event promotions, loyalty programmes, automated sequences
- Review management: monitoring Google/TripAdvisor reviews, drafting responses, generating new reviews
- Local SEO: optimising visibility in local search results, managing listings, keyword strategy
- Content strategy: content calendars, brand voice development, trend analysis, performance reporting
- Analytics and reporting: monthly branded reports showing what we delivered and the impact
- Paid advertising: Meta ads, Google ads (premium tier)
- Video content: short-form video for TikTok/Reels
- Website and digital presence: landing pages, menu updates, event pages

The WhatsApp auto-posting pipeline is our first product, the entry point. But the vision is total marketing ownership for each client.

## Current Status
- WhatsApp to Instagram/Facebook posting pipeline: Built and working on Railway
- Testing with a few London pubs to validate the experience
- Everything else on the service list: being built out now
- OpenClaw deployed as the operations and business intelligence layer

## Business Decisions Log
- [2026-03-27] Target market: London hospitality businesses, starting with pubs
- [2026-03-29] n8n removed from critical path, Railway handles core pipeline
- [2026-03-30] Railway (Node.js/Express) confirmed as production backend
- [2026-03-31] OpenClaw deployed as operations layer on dedicated MacBook
- [2026-04-01] First target area: Central London (Soho, Covent Garden, Fitzrovia, Marylebone, Mayfair)
- [2026-04-01] Business email: nexura@nexuramarketing.co.uk
- [2026-04-01] Pricing not yet decided, testing first

## Leads and Prospects
(Agent: repopulate from fresh Central London research)

## Active Clients
(None yet)

## Outreach Tracker
(None yet)

## What Works
### Outreach
(Update as learned)
### Service Delivery
(Update as learned)
### Content and Marketing
(Update as learned)
### Sales and Closing
(Update as learned)

## What Doesnt Work
(Update with every failed attempt)

## Market Intelligence
### Competitor Agencies
(Agent: rebuild from research)
### Industry Benchmarks
(Agent: rebuild from research)
### Platform Trends
(Agent: rebuild from research)
### Pricing Intelligence
(Agent: rebuild from research)

## Service Readiness
- Instagram posting: Live (Railway)
- Facebook posting: Live (Railway)
- TikTok: Research done, needs build
- Google Business Profile: Research done, needs build
- Email marketing: Designed, needs platform
- Review management: Planned
- Local SEO: Planned
- Content calendars: Planned
- Client reporting: Planned
- Meta/Google ads: Future
- Video content: Future

## Sams Preferences
- Hates filler, preamble, over-explanation
- Wants action, not plans
- Thinks at Apple/Tesla brand level
- Gets frustrated when scope is narrowed to just Instagram, always think full agency
- Prefers one step at a time for technical walkthroughs
- Pushes back hard when advice misses the mark
- Values honest pushback over agreement
- Prioritises revenue-generating work over admin
- Uses British English

## Hudsons Preferences
- Same technical skill level as Sam
- Tests the system and handles deployment access
- Existing Airtable business: SH Marketing

## Lessons Learned
- [2026-04-01] NEVER use openclaw gateway install --force, it wiped the entire workspace
- [2026-04-01] Rate limits hit with rapid requests, wait 2 min between large tasks
- [2026-04-01] tools.profile must be: minimal, coding, messaging, or full
- [2026-04-01] Dont narrow the business to Instagram posting, we are a full marketing agency
- [2026-03-30] Cloudinary cloud name: djxrlfysy (NOT djxrifysy)
- [2026-03-30] WhatsApp 4096-char limit requires splitting messages
- [2026-03-30] Airtable field names must be exact

## Technical Architecture
### Production Backend (DO NOT TOUCH)
- Railway (Node.js/Express): nexura-services-production.up.railway.app
- GitHub: github.com/nexuramarketinguk/nexura-services
- Claude model: claude-sonnet-4-20250514

### Database (Airtable Base ID: appscIMDvyCAJ2rzG)
- Clients: tbl6Gs01GVMt4eRUO
- Leads: tblvqhlpFh3LlfXGg
- Jobs: tblxDTuXeuECS4sOK
- Conversations: tblWVzD6Lt4x05wRh

### Meta / Social
- WhatsApp Phone Number ID: 1078027412055823
- Instagram Business Account ID: 17841440065768492
- Facebook Page ID: 1042673788932856
- Meta app: Marketing for nexura (Development mode)
- Two portfolios: Nexura (blue N, WhatsApp) and nexuramarketinguk (orange N, Instagram/Facebook)
- Webhook verify token: nexura_verify_2024

### Infrastructure
- Cloudinary: djxrlfysy (preset: nexura_unsigned)
- OpenClaw: macOS 12, Telegram, Claude primary, Gemini secondary
- Daily briefing: n8n to Gemini 2.5 Flash to sam.chalmers@me.com

## Outstanding Tasks
- [ ] Companies House registration (SIC 73110)
- [x] Google Workspace (nexura@nexuramarketing.co.uk active)
- [ ] Virtual office address
- [ ] Wise Business account
- [ ] Meta app Live mode
- [ ] Deploy website to nexuramarketing.co.uk
- [ ] Privacy policy on website
- [ ] Hudsons Telegram access
- [ ] Rotate Telegram bot token
- [ ] First pub outreach
- [ ] GitHub repo for workspace assets
