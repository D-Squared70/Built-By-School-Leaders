# Built By School Leaders — Landing Page Specification

## Document Overview
**Site**: BuiltBySchoolLeaders.com (or subdomain)
**Purpose**: Speak directly to K-12 educators and administrators, capture EdTech ideas through PIIE
**Last Updated**: January 28, 2026

---

## Strategic Goals

| Goal | Priority | Success Metric |
|------|----------|----------------|
| Capture educator ideas via PIIE | High | PIIE start rate > 15% |
| PIIE completion | High | Completion rate > 50% |
| Build trust with skeptical educators | High | Bounce rate < 45% |
| Email capture | Medium | Lead capture > 10% |
| Marketplace awareness (future) | Low | Placeholder clicks tracked |

---

## Target Audience

### Primary Personas

#### 1. The Frustrated Teacher
- **Role**: Classroom teacher (K-12)
- **Pain**: Spends hours on tasks that should take minutes; tools don't understand classroom reality
- **Motivation**: Wants to help students, not fight software
- **Fear**: Being ignored, idea theft, wasting time
- **Tech Comfort**: Low to medium

#### 2. The Resourceful Administrator
- **Role**: Principal, AP, Department Head, District Admin
- **Pain**: Managing multiple systems, reporting burdens, communication gaps
- **Motivation**: Efficiency, compliance, supporting teachers
- **Fear**: Budget constraints, implementation difficulty
- **Tech Comfort**: Medium

#### 3. The EdTech Dreamer
- **Role**: Any educator with a specific app idea
- **Pain**: Has thought "someone should build this" many times
- **Motivation**: Wants to see their idea exist
- **Fear**: Not technical enough, idea not good enough
- **Tech Comfort**: Varies

### Psychographic Profile
- **Skeptical of tech promises** — They've seen countless "revolutionary" tools fail
- **Time-starved** — Every minute matters; don't waste their time
- **Mission-driven** — Ultimately care about student outcomes
- **Community-oriented** — Value peer recommendations
- **Budget-conscious** — Understand resource constraints

### Language They Use
- IEPs, ILPs, 504 plans
- PLCs (Professional Learning Communities)
- Standards-based grading
- Parent communication / parent-teacher conferences
- Lesson planning, curriculum mapping
- Attendance, behavior tracking
- FERPA compliance
- "Admin" (administration, not technology admin)

---

## Page Architecture

### Information Hierarchy
```
1. Hero (Above the Fold) ─────────────────── PRIMARY CONVERSION
2. The Educator's Problem ────────────────── EMPATHY/VALIDATION
3. What You Get (Concept Memo) ───────────── VALUE DEMONSTRATION
4. Idea Prompts ──────────────────────────── REDUCE FRICTION
5. How It Works ──────────────────────────── PROCESS CLARITY
6. Trust & Privacy ───────────────────────── OBJECTION HANDLING
7. FAQ ───────────────────────────────────── OBJECTION HANDLING
8. Final CTA ─────────────────────────────── CONVERSION RECOVERY
9. Footer ────────────────────────────────── LEGAL/RESOURCES
```

---

## Section-by-Section Specification

### Section 1: Hero (Above the Fold)

**Viewport Coverage**: 100vh
**Goal**: Immediate resonance with educator identity + clear action

#### Content

| Element | Specification |
|---------|---------------|
| **Headline** | "Finally—Apps Built By Educators, For Educators" |
| **Subheadline** | "You know exactly what tools would make your school run better. Describe your idea in 12-15 minutes and walk away with a professional concept memo—yours to keep." |
| **Primary CTA** | "Get Your Free Concept Memo" → Opens PIIE |
| **Secondary CTA** | "See How It Works ↓" → Smooth scroll |
| **Trust Micro-copy** | "No tech skills needed. Your idea stays yours—even if you never submit it." |
| **Urgency Element** | "X educator ideas in review this month" (dynamic counter) |

#### Alternative Headlines (A/B Test)
- A: "Finally—Apps Built By Educators, For Educators" (current)
- B: "What If YOUR Ideas Became the Apps?"
- C: "Turn Your Classroom Ideas Into Real Tools"
- D: "The EdTech Tools You Need Don't Exist Yet. Let's Build Them."

#### Alternative CTAs (A/B Test)
- A: "Get Your Free Concept Memo" (recommended)
- B: "Share Your App Idea"
- C: "Describe Your Idea (15 min)"
- D: "Start Your Free Idea Review"

#### Visual Treatment
- **Background**: Light, clean, welcoming
- **Hero Image/Visual Options**:
  - Option A: Diverse educator in classroom setting (not stock-feeling)
  - Option B: Stylized illustration of educator with lightbulb/idea
  - Option C: School dashboard mockup showing app interface
- **Avoid**: Generic stock photos of people high-fiving, sterile corporate imagery

#### Layout (Desktop)
```
┌─────────────────────────────────────────────────────────────────┐
│  [Logo]                      [How It Works] [FAQ] [About]       │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│   Finally—Apps Built By                        ┌─────────────┐  │
│   Educators, For Educators                     │             │  │
│                                                │  [VISUAL]   │  │
│   You know exactly what tools would            │  Educator   │  │
│   make your classroom or school run            │  in context │  │
│   better. Walk away with a professional        │             │  │
│   concept memo—yours to keep.                  └─────────────┘  │
│                                                                 │
│   ┌──────────────────────────────┐                              │
│   │  Get Your Free Concept Memo  │  See How It Works ↓          │
│   └──────────────────────────────┘                              │
│                                                                 │
│   No tech skills needed. Your idea stays yours.                 │
│                                                                 │
│   📊 47 educator ideas in review this month                     │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

#### Layout (Mobile)
- Single column
- Headline and subhead first
- CTA button full-width, positioned for thumb reach
- Visual below CTA or remove entirely
- Trust micro-copy immediately below CTA

---

### Section 2: The Educator's Problem

**Goal**: Show deep understanding of their daily frustrations

#### Content

**Section Header**: "We Get It. The Tools Aren't Built for You."

| Pain Point | Copy |
|------------|------|
| 1 | "I spend hours on tasks that should take minutes—attendance, grading, parent emails, progress reports." |
| 2 | "The apps I'm forced to use weren't designed by anyone who's actually been in a classroom." |
| 3 | "I have a dozen ideas for tools that would help, but no way to build them myself." |
| 4 | "Tech companies don't understand IEPs, parent communication logistics, or the reality of lesson planning with 30 different learners." |

#### Visual Treatment
- Clean list with subtle educator-themed icons
- Consider quote-style formatting
- Soft background differentiation
- Relatable illustration optional

#### Tone
- Empathetic, not condescending
- "We understand" not "We'll save you"
- Acknowledge their expertise

---

### Section 3: What You Get (Concept Memo Preview)

**Goal**: Make the value tangible—show them what they'll receive

#### Content

**Section Header**: "Walk Away With a Professional Concept Memo"
**Section Subhead**: "Whether or not we build your idea, you get this document—it's yours to keep, edit, and use."

**Concept Memo Contents**:
| Section | Description |
|---------|-------------|
| Problem Definition | "A clear articulation of the problem you're solving" |
| Target User | "Who specifically benefits from this tool" |
| Proposed Solution | "How the app would work, in plain language" |
| Key Features | "The core functionality that makes it useful" |
| Potential Challenges | "Honest assessment of what might be tricky" |
| Next Steps | "What happens if this moves forward" |

#### Visual Treatment
- **Mockup of actual concept memo document**
- Show it as a professional-looking document (not a form)
- Highlight that it's downloadable
- Consider showing PDF icon or document preview

#### CTA Options
- Primary: "Get Your Concept Memo →"
- Secondary (smaller): "See a sample memo" → Opens sample PDF in new tab or modal

#### Sample Memo Strategy
Create a real sample concept memo for education vertical showing:
- Example problem: "IEP Progress Note Generator"
- Demonstrates quality of output
- Reduces uncertainty about what they'll receive
- Can be used as exit-intent offer

---

### Section 4: Idea Prompts

**Goal**: Reduce "blank page anxiety"—help them realize they DO have ideas

#### Content

**Section Header**: "Not Sure If Your Idea Counts? Here's What We're Looking For"

| Prompt Style | Examples |
|--------------|----------|
| "I wish there was..." | "I wish there was a tool that auto-generates IEP progress notes based on my daily observations." |
| "Every week I waste time on..." | "Every week I waste time copying the same information into three different systems." |
| "It's ridiculous that..." | "It's ridiculous that there's no easy way to share lesson plans with my co-teachers in real-time." |
| "Parents always ask..." | "Parents always ask for updates, but our communication tools are stuck in 2005." |
| "If I could automate..." | "If I could automate attendance follow-ups, I'd save 5 hours a week." |

#### Additional Examples (Specific)
- "A grade book that actually understands standards-based grading"
- "Parent communication that translates messages automatically"
- "Classroom management that tracks different learning styles"
- "A simple way to schedule and track intervention sessions"
- "Substitute teacher prep that doesn't take an hour"

#### Visual Treatment
- Card-style layout with each prompt
- Conversational, approachable design
- Consider lightbulb or thought-bubble icons
- "Your unique experience will generate ideas we haven't thought of."

---

### Section 5: How It Works

**Goal**: Make the process feel simple and low-commitment

#### Content

**Section Header**: "It's Simpler Than Writing a Lesson Plan"

| Step | Title | Description | Time |
|------|-------|-------------|------|
| 1 | "Have a Conversation" | "Chat with our AI—it asks smart questions about your idea. Think of it like explaining to a colleague who actually listens. Voice or text, your choice." | 12-15 min |
| 2 | "Get Your Concept Memo" | "Instantly receive a professional document summarizing your idea. Download it immediately—it's yours regardless of what happens next." | Instant |
| 3 | "Choose to Submit (Optional)" | "If you want us to evaluate your idea for building, submit it for review. If not, you still keep your memo." | Your choice |
| 4 | "Watch It Get Built" | "Selected ideas get developed into real apps. You get early access, input on features, and revenue share." | If selected |

#### Visual Treatment
- Vertical timeline on mobile, horizontal on desktop
- Clear step numbers
- Time indicators for each step
- Emphasize "~15 min total" and "Optional submission"

#### CTA
- After Step 4: "Get Your Free Concept Memo →"
- Supporting text: "Takes 12-15 minutes—less than a planning period"

---

### Section 6: Trust & Privacy

**Goal**: Directly address fear of idea theft and data concerns

#### Content

**Section Header**: "Your Ideas Are Safe"

| Trust Point | Explanation |
|-------------|-------------|
| "Download before you submit" | "Your concept memo is generated instantly. Download it before you decide whether to submit for review. It's yours no matter what." |
| "We don't steal ideas" | "We help bring them to life. Our business model only works if we build things people want—that means partnering with you, not taking from you." |
| "Confidential submission" | "If you submit, only our evaluation team sees your idea. We never share it publicly without your permission." |
| "FERPA-conscious" | "We minimize PII in all MVPs. If your idea involves student data, we'll build it with compliance in mind." |
| "Your data is protected" | "Your submission is confidential. We never share your idea publicly without explicit permission." |
| "Free to submit" | "No payment ever required. We invest the resources—you invest the expertise." |

#### Visual Treatment
- Clean, reassuring layout
- Shield or lock icons
- Consider "Our Promise" framing
- Link to full Privacy Policy

---

### Section 7: FAQ (Educator-Specific)

**Goal**: Handle remaining objections with educator-specific concerns

#### Content

| Question | Answer |
|----------|--------|
| "I'm not technical at all—is that okay?" | "That's exactly what we want. We need your expertise in education, not coding. The AI interview is just a conversation—if you can describe your problem to a colleague, you can do this." |
| "What if my school has strict technology policies?" | "Submitting an idea doesn't require school approval or any school involvement. This is about YOUR ideas and expertise." |
| "How long does the conversation really take?" | "About 12-15 minutes—less than a planning period. You can use voice dictation if typing feels slow." |
| "What if my idea already exists somewhere?" | "Our AI will let you know during the conversation. No harm in exploring—and your version might be better." |
| "Who sees my idea if I submit it?" | "Only our evaluation team reviews submissions. We never share your idea publicly without explicit permission." |
| "What if I'm not sure my idea is 'big enough'?" | "We specialize in small, focused tools—not massive platforms. If it would save you 30 minutes a week, that's exactly what we're looking for." |
| "How do I know this isn't a scam?" | "You receive your concept memo before we ask for anything. You can download it and walk away. We only make money if we build something successful." |
| "What happens if my idea is selected?" | "We reach out to discuss partnership terms. You'll have input during development, early access to the product, and revenue share from marketplace sales." |

#### Visual Treatment
- Accordion/expandable format
- Educator-friendly language throughout
- Show 3-4 questions expanded by default (include "How do I know this isn't a scam?" as one of the default-expanded—addresses skepticism immediately)
- "More questions? Email us" link

---

### Section 8: Final CTA

**Goal**: Capture educators who scrolled the full page

#### Content

| Element | Specification |
|---------|---------------|
| **Header** | "You've Thought 'Someone Should Build This' Enough Times. Now You Can." |
| **Subhead** | "15 minutes. One conversation. Walk away with a professional concept memo—whether we build it or not." |
| **Primary CTA** | "Get Your Free Concept Memo →" |
| **Urgency Line** | "We're actively reviewing educator ideas. We select 3-5 ideas to build each quarter." |
| **Secondary** | "Not ready? Join our educator community for updates." + Email capture |

#### Visual Treatment
- Contrasting background (warm education-appropriate color)
- Large, centered CTA (minimum 220px wide)
- Urgency line in smaller text below CTA
- Warm, encouraging tone
- Email capture subtle, below primary

---

### Section 9: Footer

#### Content
- Logo
- Navigation: Home, How It Works, FAQ, About, Privacy, Contact
- Resource links (optional): "Teacher Grants", "EdTech Resources"
- Back to main site: "← Built By Studios"
- Legal: Privacy Policy, Terms of Service
- Copyright

#### Visual Treatment
- Clean, minimal
- Emphasize Privacy Policy (trust signal)
- Consider educator-specific resources as value-add

---

## Design System

### Color Palette (Education-Appropriate)

| Role | Color | Hex | Usage |
|------|-------|-----|-------|
| Primary | Education Blue | #2563EB | Headers, links, trust |
| Secondary | Warm Gray | #4B5563 | Body text |
| Accent | Friendly Green | #10B981 | CTAs, success states |
| Background | Soft Cream | #FFFBF5 | Page background |
| Surface | White | #FFFFFF | Cards, sections |
| Highlight | Soft Yellow | #FEF3C7 | Callouts, emphasis |

### Typography

| Element | Font | Size (Desktop) | Size (Mobile) | Weight |
|---------|------|----------------|---------------|--------|
| H1 (Hero) | Inter | 52px | 32px | 700 |
| H2 (Section) | Inter | 36px | 26px | 600 |
| H3 (Subsection) | Inter | 22px | 18px | 600 |
| Body | Inter | 18px | 16px | 400 |
| Small/Caption | Inter | 14px | 14px | 400 |
| CTA Button | Inter | 18px | 16px | 600 |

### Visual Style
- **Aesthetic**: Warm, approachable, professional but not corporate
- **Imagery**: Real educators, diverse representation, actual classroom/school settings
- **Icons**: Friendly, rounded style (not sharp/corporate)
- **Illustrations**: Consider custom illustrations over stock photos
- **Avoid**: Sterile corporate look, overly "techy" aesthetic, generic stock

### Spacing
- Generous white space
- Section padding: 100px top/bottom (desktop), 64px (mobile)
- Comfortable reading line length (max 680px for body text)

---

## Technical Requirements

### PIIE Integration

#### Embedded Experience
- PIIE chat interface embedded directly on page (not redirect)
- "Guest mode" - no login required to start
- Voice dictation prominently featured (Whisper API)
- Mobile-optimized touch targets

#### Conversation Flow
```
1. User clicks "Share Your App Idea"
2. PIIE overlay/modal opens OR scrolls to embedded chat
3. AI begins: "Hi! I'm here to help you capture your EdTech idea..."
4. 10-15 minute conversation
5. AI generates concept memo
6. User views preview of memo
7. Prompt: "Enter your email to download your Concept Memo"
8. Email captured, memo delivered
9. Optional: "Would you like to submit this for review?"
```

#### Key PIIE Prompts (Educator-Specific)
- "What's a task you do repeatedly that frustrates you?"
- "Who specifically would use this tool? Teachers? Admins? Parents?"
- "How do you currently handle this problem?"
- "What would 'success' look like?"

### Performance
| Metric | Target |
|--------|--------|
| First Contentful Paint | < 1.5s |
| Largest Contentful Paint | < 2.5s |
| Time to Interactive | < 3.5s |
| Page load (total) | < 3s |
| PIIE chat load | < 2s |

### Mobile Optimization
- Touch targets: minimum 48x48px
- Thumb-zone CTA placement
- Voice dictation prominent on mobile
- Single-column layout
- No horizontal scrolling

### Accessibility
- WCAG 2.1 AA compliance
- Screen reader compatible
- Keyboard navigation
- High contrast mode support
- Alt text on all images
- Captions on any video content

---

## Analytics & Tracking

### Events to Track

| Event | Trigger | Purpose |
|-------|---------|---------|
| `page_view` | Load | Traffic |
| `scroll_depth` | 25%, 50%, 75%, 100% | Engagement |
| `hero_cta_click` | Hero CTA click | Primary conversion |
| `piie_start` | PIIE conversation begins | Funnel entry |
| `piie_voice_used` | Voice dictation activated | Feature usage |
| `piie_complete` | Memo generated | Funnel completion |
| `email_captured` | Email submitted for memo | Lead capture |
| `idea_submitted` | User submits for review | Full conversion |
| `faq_expand` | FAQ item clicked | Objection interest |
| `prompt_click` | Idea prompt clicked | Engagement |

### Funnel Metrics

```
Page Visit → Hero CTA Click → PIIE Start → PIIE Complete → Email Capture → Idea Submit
   100%    →      15%       →    12%     →      7%       →      6%       →     3%
```

Target conversion rates (adjust based on data).

---

## Email Capture & Conversion Flow

### Value-First, Gate-Second Pattern (Educator-Specific)

Educators are time-starved and skeptical. The PIIE conversation MUST deliver value before asking for email.

#### Recommended Flow
```
1. User clicks "Get Your Free Concept Memo"
2. PIIE modal/overlay opens (no login, no email yet)
3. AI begins: "Hi! I'm here to help you capture your EdTech idea.
   What's something that frustrates you in your daily work?"
4. 10-15 minute conversation with educator-specific prompts
5. AI generates concept memo preview
6. User sees memo preview with key sections visible
7. GATE: "Enter your email to download your Concept Memo"
   └── Email field + "Send My Memo" button
   └── Checkbox: "Yes, evaluate my idea for building" (optional)
8. Email captured → Memo delivered instantly
9. Thank you screen with next steps
```

#### Educator-Specific Considerations
- Emphasize FERPA consciousness in conversation
- Use education terminology naturally
- Keep time visible ("5 minutes remaining")
- Allow voice input prominently

#### Abandonment Recovery
- Partial PIIE conversations: Store with consent, email reminder if captured early
- After memo preview abandonment: Trigger exit-intent
- Follow-up sequence for captured emails who didn't submit

---

## Exit-Intent Strategy (Educator-Specific)

### Exit-Intent Popup Specification

**Trigger**: Mouse moves toward close (desktop) or back button behavior (mobile)

**Conditions**:
- Only show if scrolled > 30% of page
- Only show once per session
- Don't show if PIIE already started

#### Exit-Intent Content (Education)

| Element | Specification |
|---------|---------------|
| **Header** | "Before You Go—See What Other Educators Are Building" |
| **Body** | "Download a sample concept memo to see exactly what you'd get. It's for a tool that auto-generates IEP progress notes." |
| **Primary CTA** | "Download Sample Memo" → PDF download, no email required |
| **Secondary CTA** | "I'm Ready to Share My Idea" → Opens PIIE |
| **Dismiss** | Small "X" or "Maybe later" link |

#### Visual Treatment
- Warm, not aggressive
- Show thumbnail of sample memo
- Brief educator testimonial if available

#### Alternative Exit-Intent (A/B Test)
- **Version A**: Sample memo download (above)
- **Version B**: "Join 200+ educators getting updates" + email capture
- **Version C**: Short video explaining the process (< 60 seconds)

---

## Social Proof Strategy

### Current State (Early Stage)
Without testimonials, use activity-based social proof:
- "X educator ideas submitted this month"
- "Currently reviewing ideas for: [specific tools]"
- Founder credibility with education background (if applicable)

### Future State (Post-Launch)
Add as available:
- Educator testimonials (with photo, school, role)
- "Apps built from educator ideas" showcase
- School district logos (if any institutional relationships)
- EdTech publication mentions

### Placement
- Activity counter: Hero section (subtle)
- Testimonials: After "How It Works" or before Final CTA
- Founder statement: Trust section

---

## Shorter Page Variant (A/B Test)

### Hypothesis
Educators are time-starved. A shorter page may convert better.

### Shortened Structure (Test Variant)
```
1. Hero (Above the Fold)
2. Concept Memo Preview (What You Get)
3. How It Works (3 steps only)
4. Trust & Privacy (condensed)
5. Final CTA
```

**Sections Removed:**
- Problem Statement (merged into hero)
- Idea Prompts (test if needed)
- Detailed FAQ (link to separate page)

**Word Count Target**: ~400 words (vs. ~800 current)

---

## Content Voice & Tone Guidelines

### Do
- Use "you" and "your" frequently
- Acknowledge their expertise
- Use education terminology naturally
- Be warm and encouraging
- Keep sentences short
- Address fears directly

### Don't
- Be condescending ("We'll teach you...")
- Overpromise ("Revolutionary!")
- Use corporate jargon
- Make it sound complicated
- Dismiss their concerns
- Use generic tech-speak

### Example Transformations

| ❌ Don't Write | ✅ Do Write |
|----------------|-------------|
| "Our platform leverages AI to optimize ideation" | "Our AI helps you capture and clarify your app idea" |
| "Submit your concepts for our review pipeline" | "Share your idea—we'll let you know if we can build it" |
| "Ideal for education professionals seeking innovation" | "Built for teachers who know what their classroom actually needs" |

---

## A/B Test Roadmap

### Priority 1: Headlines
- A: "Finally—Apps Built By Educators, For Educators"
- B: "What If YOUR Ideas Became the Apps?"
- C: "The EdTech You Need Doesn't Exist. Let's Build It."

### Priority 2: CTA Copy
- A: "Share Your App Idea"
- B: "Start the Conversation"
- C: "Describe Your Idea"
- D: "Get Your Free Concept Memo"

### Priority 3: Trust Section Placement
- A: After How It Works (current)
- B: Before How It Works
- C: Integrated into Hero

### Priority 4: Idea Prompts
- A: Full section with 6+ examples
- B: Condensed to 3 examples
- C: Remove section entirely

---

## Launch Checklist

### Content
- [ ] All section copy finalized
- [ ] FAQ answers complete
- [ ] Educator terminology reviewed
- [ ] Tone/voice consistent throughout
- [ ] No jargon or corporate speak

### Design
- [ ] Desktop layouts complete
- [ ] Mobile layouts complete
- [ ] All images/illustrations sourced
- [ ] Icons consistent
- [ ] Color accessibility verified

### Technical
- [ ] Page built and responsive
- [ ] PIIE integration functional
- [ ] Voice dictation working
- [ ] Email capture functional
- [ ] Analytics tracking verified
- [ ] Page speed < 3s
- [ ] Cross-browser tested
- [ ] Accessibility audit passed

### Legal/Compliance
- [ ] Privacy Policy updated
- [ ] Terms of Service updated
- [ ] FERPA considerations documented
- [ ] Cookie consent if required

---

## Copywriting Assessment Summary

**Assessment Date**: January 28, 2026
**Overall Grade**: A-

### Strengths
- **Voice/Tone**: Outstanding audience understanding—uses educator terminology naturally (IEPs, PLCs, FERPA, "less than a planning period")
- **Heightened Emotion**: Pain points feel real ("The apps I'm forced to use weren't designed by anyone who's actually been in a classroom")
- **Zero Risk**: Comprehensive trust section addresses idea theft fears directly
- **Idea Prompts**: Specific, relatable examples that reduce "blank page anxiety"

### Key Improvements Made
1. **Subheadline**: Tightened "classroom or school" to just "school" (encompasses both)
2. **Time Specificity**: Changed "~15 min" to "12-15 minutes" throughout for more precision
3. **Trust Section**: Added explicit data protection statement
4. **FAQ Visual Treatment**: Noted that "How do I know this isn't a scam?" should be default-expanded to address skepticism immediately
5. **Urgency Line**: Changed "Limited build capacity" to "We select 3-5 ideas to build each quarter"

### Areas for Post-Launch Optimization
- Add educator testimonials with photos, school names, and roles as they become available
- Consider video content (educators may appreciate face-to-face explanation)
- Track whether sample concept memo download increases trust/conversion

---

*Specification prepared for Gradient Labs AI, LLC / Built By Studios*
*Version 1.1 — January 28, 2026*
