# AIRUUN Platform — Internal Team Working Brief
## TWF Product & Technical Definition Kickoff

**Status:** Working Draft for Internal Kickoff  
**Owner:** TWF Technology / Product Team  
**Working mode:** Start from available brief, document assumptions, validate only decisions that materially affect scope.

---

# 1. Project Context

AIRUUN is being positioned as a **Wisdom + Wellbeing Platform**, not only a microsite or content repository.

The platform should create long-term relationship value through useful content, practices, activities, community participation, and a connection between the digital platform and AIRUUN physical space.

TWF's responsibility is to translate the approved strategic direction into a usable, scalable, and maintainable digital product.

## TWF role

- Product and technical definition
- Information architecture
- User journey and UX design
- Functional requirements
- Technical architecture
- CMS and content model
- Member identity and access
- Event and physical-space modules
- Analytics and data tracking
- System integrations
- Development planning and estimation

## Out of scope at this stage

- Rebuilding the AIRUUN brand strategy
- Revalidating the five pillars
- Rewriting the core proposition
- Defining TGH's corporate strategy
- Full content production
- Full community operation

Strategy support may be proposed later only where a missing decision blocks product definition.

---

# 2. Product Principles

The team must use these as non-negotiable design constraints.

1. **AIRUUN is a gift, not a product.**
2. **No selling inside the platform.**
3. **Give value before asking for identity or participation.**
4. **No dark patterns, addiction loops, or engagement farming.**
5. **Reading-only users are still successful users.**
6. **AIRUUN comes first; TGH is presented transparently as sponsor.**
7. **The experience must feel warm, plain, unhurried, practical, and respectful.**
8. **Digital and physical experiences should feel like one offer.**

---

# 3. Target Audience — Working Assumption

The first product model should support four user states:

1. **Anonymous Guest**
   - Discovers AIRUUN through search, social sharing, events, or direct links
   - Can receive value before registering

2. **Registered Non-policyholder**
   - Creates an AIRUUN relationship voluntarily
   - Can save preferences, content, and event history

3. **TGH Policyholder / Recognized Member**
   - Enters through LINE, CRM, SMS, or a personalized invitation
   - May be recognized through LINE Login, magic link, OTP, or TGH identity

4. **Admin / Content / Event Staff**
   - Manages content, programmes, member submissions, and operational data

**Current assumption:** Policyholder and non-policyholder share the same core wellbeing experience. Differences should initially be limited to recognition, communication, and possible event access until the client confirms privileges.

---

# 4. Experience Architecture

## 4.1 Receive

The daily entry experience.

### Core module: Daily Dawn

A small, complete, useful piece that arrives each morning and provides value even when the user does not tap further.

Possible formats:

- Health insight
- Reflection
- Financial tip
- Thai wisdom
- Short audio
- Short practice
- Image and text
- Short video

### Initial requirements to define

- Daily content scheduling
- Today view
- Archive or previous Dawn access
- Save and share
- Editorial selection
- Optional personalization
- LINE delivery or reminder
- Content analytics

## 4.2 Return to the Root

Thai wisdom and cultural grounding.

Possible content:

- Thai traditional medicine
- Herbal knowledge
- Movement and massage traditions
- Meditation
- Seasonal and temple rhythms
- Wat Arun custodianship
- Elder wisdom
- Founding documentary

### Product interpretation

This should be a permanent, browsable heritage experience rather than a launch-only campaign section.

## 4.3 Dwell

Rooms that users may enter and stay in. They should be browsable and curated, not an infinite social feed.

Initial room model:

- Practice
- Heritage
- Health Room
- Financial Room
- The Commons
- Live Sessions

### Working assumption

Each room is a content and experience destination with its own landing page, content types, and related actions.

## 4.4 Walk In

Connects the digital platform with AIRUUN physical space.

Possible modules:

- Physical space information
- Opening hours
- Location and directions
- Programme listings
- Event details
- Registration or booking
- Capacity and waitlist
- Confirmation and reminder
- Attendance or QR check-in

**Current assumption:** Phase 1 should include programme listing and event details. Booking and check-in should be estimated as optional modules until confirmed.

---

# 5. Five Pillars as Product Taxonomy

The five pillars are approved strategic concepts and should be translated into a content and recommendation taxonomy.

## Jai — The Heart

- Calm
- Mood
- Emotional balance
- Reflection
- Rest and resilience

## Kai — The Body

- Energy
- Movement
- Sleep
- Physical wellbeing
- Healthy ageing

## Katanyu — Loved Ones

- Family
- Ageing parents
- Caregiving
- Relationships
- Intergenerational connection

## Por-piang — Enough

- Financial wellbeing
- Sufficient living
- Money confidence
- Planning and reflection
- Financial education without selling

## Nam-jai — Warmth to Others

- Generosity
- Kindness
- Volunteering
- Community contribution
- Care for others

## Proposed metadata

Every content item should support:

- Primary pillar
- Secondary pillar
- Room
- User need
- Content type
- Duration
- Life stage
- Access level
- Publish and expiry date
- Author or source
- Related content
- Recommendation priority

---

# 6. Member Journey — Working Version

## Guest journey

1. Discover through search, social, shared content, event, or direct URL
2. Receive useful content before login
3. Select a current wellbeing need
4. View a relevant Dawn, practice, story, or programme
5. Register only when saving, booking, or continuing a journey
6. Return through preferred channel

## Policyholder journey

1. Receive LINE, CRM, SMS, or personalized invitation
2. Enter through light recognition
3. Select current wellbeing need
4. Receive relevant content or activity
5. Save progress or register for an event
6. Receive an optional reminder
7. Return because the next experience is useful

## Experience mapping

- Entry = Receive
- Identity = recognition layer behind the experience
- Intent = need or pillar selection
- Value = Dawn, Root, Rooms, or Physical Programme
- Habit = useful next action and voluntary return

---

# 7. Proposed Phase 1 MVP

## Core public platform

- Responsive website
- Homepage and platform introduction
- Daily Dawn
- Five-pillar browsing
- Heritage / Root section
- Practice and room landing pages
- Content detail pages
- Programme and event listing
- AIRUUN physical-space information
- Search or structured filtering
- Social sharing
- Basic analytics

## Member foundation

- Guest and member states
- Light login approach
- Basic member profile
- Pillar or wellbeing preference
- Saved content
- Basic content history
- Consent management

## CMS

- Structured content types
- Draft, review, publish, archive
- Scheduling
- Tags and taxonomy
- Media management
- Role-based access
- Preview
- Basic audit trail

## Basic personalization

Start with rules, not AI:

- Selected pillar
- Viewed content
- Saved content
- Event interest
- Editorial priority

## Optional MVP modules requiring confirmation

- Event booking
- Waitlist
- LINE notifications
- Member story submission
- Moderated comments
- Live-session integration
- Policyholder verification
- CRM synchronization

---

# 8. Future Phases

## Phase 2 — Engagement

- Advanced profile
- Saved journeys
- Progress tracking
- Event registration and attendance
- Curated member stories
- Limited reactions or comments
- Segment-based communication
- Operational dashboards

## Phase 3 — Intelligence and Community

- AI-assisted recommendations
- Advanced behavioural personalization
- Full CRM/CDP automation
- Community groups
- Member-led activities
- Predictive re-engagement
- Cross-channel orchestration

---

# 9. Technical Discovery Tracks

The team can start preparing these immediately.

## Track A — Identity

Investigate:

- LINE Login
- OTP
- Magic link
- TGH SSO
- Policyholder verification
- Guest-to-member conversion
- Account deletion and consent withdrawal

## Track B — Integration

Prepare an integration inventory for:

- LINE OA
- CRM/CDP
- Policyholder database
- Consent management
- Analytics
- Marketing automation
- Existing event system
- A ROOT or other ecosystem links

## Track C — CMS

Define:

- Content types
- Editorial workflow
- Admin roles
- Scheduling
- Multilingual requirements
- Content ownership
- Initial content migration

## Track D — Data and analytics

Draft tracking events:

- View Dawn
- Select need
- View content
- Complete practice
- Save
- Share
- Login
- Register
- View programme
- Book event
- Attend event
- Return visit

## Track E — Security and infrastructure

Prepare questions for:

- Hosting ownership
- Cloud standard
- Environments
- WAF
- Penetration testing
- Data residency
- PDPA
- Backup and disaster recovery
- Admin security
- SLA

---

# 10. Deliverables for Product & Technical Definition

The team should produce:

1. Brief interpretation and assumptions
2. Sitemap
3. Information architecture
4. Guest/member/policyholder journeys
5. Core wireflows
6. Feature inventory
7. MVP / Phase 2 / Future matrix
8. Content model
9. CMS requirements
10. Solution architecture
11. Data flow diagram
12. Integration inventory
13. Analytics tracking plan
14. Technical risks and dependencies
15. Development estimate and roadmap

---

# 11. Three-Week Working Plan

## Week 1 — Define

### Product / BA

- Consolidate brief and meeting direction
- Build assumption log
- Draft personas by relationship state
- Create sitemap v0.1
- Create feature inventory
- Map user journeys

### UX/UI

- Collect visual and experience references
- Define navigation principles
- Draft homepage, Daily Dawn, room, and programme wireframes
- Explore guest-first experience

### Tech Lead

- Draft solution options
- Identify identity and integration dependencies
- Define possible CMS approaches
- Create technical-question backlog

### Output

- Product model v0.1
- Sitemap v0.1
- Journey v0.1
- Technical assumption log

## Week 2 — Structure

### Product / UX

- Complete core wireflows
- Define room behaviours
- Define Daily Dawn states
- Define guest/member boundaries
- Draft content taxonomy

### Technical

- Draft architecture
- Draft data model
- Draft CMS structure
- Draft analytics events
- Separate mandatory and optional integrations

### Output

- Wireflow pack
- Feature matrix
- Content model
- Architecture v0.1
- MVP recommendation

## Week 3 — Package

- Internal review
- Resolve inconsistencies
- Estimate UX/UI and development work
- Identify client decisions
- Prepare client-facing definition deck
- Prepare budget range and timing
- Prepare Phase 1 proposal

### Output

- Product & Technical Definition Pack
- MVP scope
- Roadmap
- Risk and dependency list
- Preliminary budget and timeline

---

# 12. Internal Team Assignment

## Product Lead / BA

Own:

- Assumptions
- Sitemap
- Requirements
- Feature matrix
- Client decision log
- Scope control

## UX/UI

Own:

- Experience architecture
- Wireflows
- Information hierarchy
- Design principles
- Prototype direction

## Tech Lead

Own:

- Architecture
- Identity options
- Integration approach
- CMS recommendation
- Security and infrastructure assumptions
- Estimation

## Developer Representative

Own:

- Technical feasibility
- Module breakdown
- Third-party dependency review
- Implementation risks

## QA / PM

Own:

- Acceptance-criteria framework
- Risk log
- Timeline
- Review cadence
- Document control

---

# 13. Assumption Log — Start Here

Use the following until the client confirms otherwise.

1. Phase 1 is a responsive web platform.
2. LINE is an entry and return channel, but full MINI App scope is not yet confirmed.
3. Guests can read selected content without login.
4. Login is required for saving, booking, or personalized continuity.
5. Daily Dawn is editorially managed.
6. Phase 1 personalization is rule-based.
7. Community begins as curated participation, not an open forum.
8. No commerce or product checkout occurs in AIRUUN.
9. Events and programmes are displayed in Phase 1; full booking is optional.
10. Policyholder data integration is treated as a dependency, not assumed ready.
11. Thai is the primary launch language unless confirmed otherwise.
12. TWF builds the platform; the client owns content strategy and ongoing editorial operation.

---

# 14. Questions That Should Not Block the Team

The team should proceed using assumptions for:

- Final login method
- Final CMS technology
- Full community model
- Event booking depth
- AI recommendation
- CRM integration
- Policyholder privileges
- Bilingual launch
- Physical-space check-in

These should be designed as modular decisions so the work can continue without waiting.

---

# 15. Decisions Needed Before Fixed Development Pricing

Only these decisions materially affect final fixed scope:

1. Web only or Web + LINE MINI App
2. Login and policyholder verification
3. Required integrations and API readiness
4. Event listing only or full booking/check-in
5. Community interaction level
6. CMS and editorial workflow
7. Launch content volume and migration owner
8. Security, hosting, and compliance requirements
9. Expected launch traffic and SLA
10. Thai-only or multilingual launch

---

# 16. Internal Kickoff Agenda — 60 Minutes

## 0–10 min: Direction

- What AIRUUN is
- What TWF owns
- Non-negotiable experience principles

## 10–25 min: Product model

- Receive
- Return to the Root
- Dwell
- Walk In
- Five pillars
- Guest and member journey

## 25–40 min: MVP

- Mandatory modules
- Optional modules
- Assumptions
- Phase breakdown

## 40–50 min: Team workstreams

- Product
- UX/UI
- Architecture
- Data
- Integration
- Estimation

## 50–60 min: Actions

- Assign owners
- Confirm Week 1 outputs
- Set internal review date
- Open decision and risk log

---

# 17. Immediate Tasks After Kickoff

1. Create sitemap v0.1
2. Draft Daily Dawn product flow
3. Draft guest and recognized-member journeys
4. Define room template and content types
5. Draft event and physical-space flow
6. Build feature matrix
7. Prepare identity options
8. Prepare integration inventory
9. Draft analytics event list
10. Create assumption, risk, and decision logs

---

# Working Principle

> Start with what is known.  
> Make assumptions visible.  
> Design uncertain parts as modules.  
> Ask the client only for decisions that materially change scope.
