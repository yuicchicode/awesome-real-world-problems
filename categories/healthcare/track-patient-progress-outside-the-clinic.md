# Difficulty tracking the patient’s progress outside the clinic

## Problem summary
Healthcare professionals can assess a patient during the appointment, but often lose visibility into what happens once that patient leaves the clinic. This breaks continuity of care and makes treatment decisions heavily dependent on memory, delayed feedback, and the next in-person visit.

## Real-world report
I can see the patient during the consultation, understand what they are feeling, adjust the treatment, explain what they need to do, and document what happened in that appointment. The problem starts after they leave. From that point on, I often lose visibility into their daily reality.

I do not know whether they are following the treatment properly, taking medication at the right time, improving, getting worse, experiencing side effects, or simply abandoning the plan entirely. When the patient comes back weeks or months later, the information is usually incomplete and based only on memory. They may say they did not improve, but I still do not know whether the treatment failed, whether they did not follow instructions, or whether something changed in the middle of the process.

This makes follow-up care feel disconnected. Important signals may appear between consultations without any structured record. That delays adjustments, weakens the sense of care continuity, and reduces the professional’s ability to evaluate the case accurately.

## Why this is difficult
The hard part is not only collecting information. It is collecting it consistently, without creating too much friction for the patient. Symptoms may change daily, adherence may be irregular, and some patients are not comfortable with detailed manual tracking.

## Why it matters
This affects treatment quality, patient confidence, and decision-making. In more sensitive cases, delayed visibility can lead to worse outcomes and missed opportunities for early intervention.

## Project opportunity
This is an excellent project problem because it combines healthcare workflows, longitudinal tracking, reminders, patient engagement, and role-based access. It can evolve from a simple follow-up tool into a broader patient monitoring ecosystem.

## Technical requirements
- Support at least two user roles: healthcare professional and patient
- Allow structured follow-up logs for symptoms, medication adherence, routine, and observations
- Keep a chronological history of updates
- Support recurring reminders for check-ins and treatment tasks
- Allow configurable alert thresholds for worsening symptoms or missing updates
- Provide a simple patient experience, especially on mobile
- Preserve notes and historical trends for the professional
- Support different kinds of check-in forms depending on treatment type
- Include status tracking for adherence, improvement, regression, and inactivity
- Design for privacy-sensitive data handling

## Suggested MVP
- Patient check-in form
- Daily or weekly symptom tracking
- Medication adherence logging
- Timeline of updates for the professional
- Reminders for follow-ups
- Alerts for missing check-ins

## Possible extensions
- Wearable or device integrations
- AI-generated summaries for follow-up visits
- Risk scoring for worsening cases
- Family or caregiver access
- Exportable treatment history