# SkillBridge

## Problem Statement

Skill-development programmes may be designed using broad or historical occupation categories that do not fully reflect changing technologies, local industry demand, job roles, productivity standards and employer expectations. Course curricula, equipment, trainer capacity and assessment methods may lag emerging requirements. Employers may struggle to identify job-ready candidates, while trainees may complete courses that have limited placement potential.

The challenge is to create a continuous, evidence-based mechanism for translating industry demand into course design, capacity planning, trainer development and candidate guidance.

## My Solution

We are building a labour-market intelligence platform that pulls together multiple layers of real-world signal instead of relying on a single, potentially outdated or biased source.

### Data Layers

1. **Job-market demand signal**
   We collect current job posting data (via public job APIs and portals such as Naukri, Indeed, and government job boards) to identify which skills and roles are trending, by location and proficiency level, and where a mismatch exists between what's being taught and what's actually being hired for.

2. **First-party outcome data — our key differentiator**
   Self-reported placement statistics from training centers are often inflated. We distribute our own lightweight survey/feedback forms to trainees and job-seekers (via WhatsApp groups, colleges, and training centers) to collect honest, structured outcome data: did they get placed, in what role, at what stage, and which skills they had to learn on their own that the course didn't cover. This gives us a real, first-party dataset that doesn't exist anywhere else.

3. **Social signal (secondary)**
   We supplement this with analysis of public discussions (Reddit, YouTube comments, course reviews) using NLP to extract genuine sentiment about specific courses and skills — flagging which ones are seen as outdated versus genuinely valuable.

4. **Employer validation layer**
   To cross-check survey data against reality, we build a lightweight confirmation loop with employers — for example, showing them "X applicants with Course Y on their resume applied to your openings this month" and letting them confirm or correct whether that skillset is actually what they're hiring for.

5. **Global trend signal**
   We track foreign (US/EU) job market trends as an early-warning layer, since emerging skill demand often appears in global markets before it reaches India — helping the platform recommend forward-looking skills, not just reactive ones.

6. **Sector growth signal**
   We incorporate macro-level sector growth data (from sources like NSDC reports, government economic surveys, and industry body publications such as NASSCOM/CII) to distinguish sustained, structural industry growth from short-term hiring spikes — ensuring curriculum recommendations are based on durable trends, not noise.

7. **AI-generated curriculum update recommendations**
   Beyond flagging which courses are outdated or oversupplied, the platform proposes *what the fix should look like* — e.g., "add a module on solar panel wiring to the electrician course" — using AI to analyze the gap between a course's current syllabus and actual demanded skills, and suggesting concrete, actionable curriculum changes.


## Why This Approach Is Different

Existing platforms typically do one of two things: show raw job listings, or show course catalogs — rarely both, and almost never validated against real outcomes. Government/training-center tools usually rely on self-reported placement data, which is easy to inflate.

SkillBridge is different because:
- It cross-validates claims against real employer signals instead of trusting self-reported numbers alone
- It combines reactive data (current job postings) with predictive data (global trends, sector growth) so recommendations are forward-looking, not just reactive
- It serves three distinct stakeholders (government, training centers, learners) from a single data engine, rather than being a single-purpose tool


