# Manual candidate screening, but low accuracy when it becomes automated

## Problem summary
One of the most common problems in HR is that candidate screening takes too much time when done manually, but loses too much quality when automated in a simplistic way. Teams get stuck between two bad options: slow human review or fast filtering with low confidence.

## Real-world report
One of the most common problems in HR is that candidate screening, when done manually, consumes too much time, energy, and attention from the team. Depending on the role, dozens or even hundreds of resumes may arrive, and someone has to stop everything to open profile after profile, read experience, compare information, try to identify fit, and decide who should move forward.

That makes the process slow, exhausting, and heavily dependent on the availability of whoever is recruiting. Many times, I know the team needs to be more agile, but we simply cannot review everything with enough depth in the time the business expects.

At the same time, when the company tries to automate that screening, another problem appears: low accuracy. The system may help filter by keywords, degree, years of experience, or a few objective criteria, but that does not always reflect the candidate’s real potential for the role.

A lot of strong candidates get filtered out because they did not write their resume in the exact way the tool expects, because they did not use the right keywords, or because they have a less conventional background. On the other hand, some candidates pass the automated filter but do not show real fit once the HR team looks more deeply.

In practice, the company gets trapped between two frustrating scenarios. If everything is manual, the process becomes slow, expensive, and draining. If it is over-automated, the company risks losing strong profiles or advancing the wrong ones. Recruitment stops feeling like a precise search for the right people and becomes a constant attempt to balance speed, volume, and quality without a tool that is truly trustworthy.

There is also another layer: many roles require more than simple technical criteria. Communication, behavioral patterns, context behind experience, cultural fit, and development potential do not always appear clearly in automated screening. But reviewing all of that manually at scale is also hard. The HR team ends up in the middle of a heavy process, trying not to be superficial but without enough structure to go deep on every profile.

## Why this is difficult
The difficult part is not only handling volume. The harder issue is evaluating fit in a way that is both scalable and nuanced.

Most simplistic automation works well with explicit and standardized signals, but hiring quality often depends on incomplete, contextual, and non-linear signals. A rigid filter may be efficient at reducing volume while still being poor at identifying the right people.

## Why it matters
When screening fails, the company loses time in interviews with poor-fit candidates, misses promising profiles, and increases the risk of hiring someone who does not actually match the role.

It also overloads recruiting teams, delays hiring, and creates frustration for the hiring area, which starts feeling that the process cannot keep up with business urgency.

## Project opportunity
This is a very strong project problem because it reflects a real tension in modern hiring: scale versus judgment.

A good solution here could help teams structure better screening criteria, preserve human review where it matters, reduce shallow filtering, and make screening more transparent and adaptable. It is also a great portfolio problem because it combines ranking logic, workflow design, explainability, evaluation criteria, and human-in-the-loop review.

## Technical requirements
- Support role-specific screening criteria instead of one fixed screening model
- Allow structured candidate profiles with education, experience, skills, certifications, and free-text context
- Support both manual review and assisted screening workflows
- Preserve explanation for why a candidate was scored, filtered, or flagged
- Allow recruiters to adjust weights and screening rules per role
- Handle missing, unconventional, or non-standard candidate information gracefully
- Support candidate tagging, shortlisting, rejection reasons, and review status
- Keep a historical record of recruiter decisions and screening outcomes
- Allow comparison between automated recommendations and human decisions
- Surface signals beyond keywords when possible, such as role similarity, project relevance, or career progression context
- Support collaboration between recruiter and hiring manager
- Avoid turning the tool into a black box

## Suggested MVP
- Candidate intake and profile parser
- Screening criteria builder by role
- Recruiter review queue
- Candidate scoring with explanation
- Shortlist and rejection workflow
- Comparison view between automatic ranking and recruiter decisions

## Possible extensions
- Bias and fairness review tools
- Human feedback loop for ranking improvement
- Interview outcome back-propagation
- Hiring manager collaboration panel
- Resume normalization across formats
- AI-assisted but explainable fit summaries