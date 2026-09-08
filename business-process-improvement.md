<style>
  .back-link {
    display: inline-block;
    margin-bottom: 1.5rem;
    font-size: 0.9rem;
    font-weight: 600;
    color: #d97706;
    text-decoration: none;
  }

  .back-link:hover {
    text-decoration: underline;
  }

  .project-page h2 {
    margin-top: 2.5rem;
    padding-left: 0.85rem;
    border-left: 4px solid #d97706;
    color: #111827;
  }

  .project-page h3 {
    margin-top: 1.75rem;
    color: #111827;
  }

  .project-page img {
    border-radius: 10px;
    border: 1px solid #e5e7eb;
    box-shadow: 0 4px 14px rgba(17, 24, 39, 0.06);
  }

  .project-page em {
    display: block;
    margin-top: 0.5rem;
    font-size: 0.9rem;
    color: #6b7280;
  }

  .tech-pills {
    display: flex;
    flex-wrap: wrap;
    gap: 0.6rem;
    margin: 1rem 0 2rem;
    padding: 0;
    list-style: none;
  }

  .tech-pills li {
    display: inline-block;
    padding: 0.4rem 0.85rem;
    border-radius: 999px;
    background: #fffbeb;
    color: #b45309;
    font-size: 0.9rem;
    font-weight: 600;
  }

  .cost-table {
    width: 100%;
    border-collapse: collapse;
    margin: 1rem 0 1.5rem;
    font-size: 0.95rem;
  }

  .cost-table th {
    background: #fffbeb;
    color: #92400e;
    text-align: left;
    padding: 0.6rem 0.85rem;
    border: 1px solid #fde68a;
  }

  .cost-table td {
    padding: 0.6rem 0.85rem;
    border: 1px solid #f3f4f6;
  }

  .key-takeaways {
    margin-top: 1rem;
    padding: 1.25rem 1.5rem;
    background: #fffbeb;
    border-left: 4px solid #d97706;
    border-radius: 8px;
  }
</style>

<a class="back-link" href="/">&larr; Back to Portfolio</a>

<div class="project-page" markdown="1">

# Business Process Improvement: Tutoring Services Client

## Overview

As part of a semester-long consulting engagement, our team partnered with a small, locally-owned tutoring service to review their current business processes and propose actionable improvements. Working directly with the client's Director of Operations, we conducted stakeholder interviews, mapped out existing workflows using EPC (Event-Driven Process Chain) diagrams, and identified three core processes with clear room for improvement: the tutor application process, individual tutoring session scheduling, and student feedback collection. We then designed improved versions of each process, evaluated third-party software solutions to support them, and delivered a full cost-benefit analysis to help the client make an informed implementation decision.

## Project Goals

- Understand the client's current business processes through direct stakeholder engagement
- Identify inefficiencies and growth-limiting gaps in existing workflows
- Design improved, streamlined versions of each process
- Evaluate and recommend third-party software solutions to support each improvement
- Deliver a cost-benefit analysis to support the client's decision-making
- Present findings and recommendations directly to the client for feedback

## Current State Analysis

Our team began by meeting with the client to understand their business model, current systems, and organizational structure. From there, we mapped out the existing versions of three key processes using EPC diagrams, which allowed us to visually identify bottlenecks and inefficiencies before proposing any changes.

**Tutor Application Process**
The existing process required prospective tutors to navigate an unclear path through the website's "Contact" tab just to find the job application, and the application itself only collected basic contact information — with no way to capture relevant qualifications like GPA or prior tutoring experience.

**Individual Tutoring Session Scheduling**
Scheduling a session required students to manually email a scheduling inbox, then wait for a staff response confirming availability before coordinating directly with a tutor over email. This back-and-forth process introduced delays that could stretch over multiple days.

**Feedback Collection**
There was no structured feedback mechanism at all — the website simply directed users to call or email general contact information, meaning feedback was easily lost among other routine communications.

## Proposed Improvements

**Tutor Application Process**
We proposed adding a dedicated "Apply" section to the main site, routing applicants to an external application platform. This would let the client display detailed job postings, auto-fill applications from an uploaded resume, and flag incomplete or fraudulent submissions — reducing friction for qualified applicants while improving the quality of information collected.

**Individual Tutoring Session Scheduling**
We proposed integrating a live scheduling tool directly into the website, allowing students to view real-time tutor availability, select a time slot, and complete payment immediately — eliminating the manual email back-and-forth entirely. Tutor calendars would sync automatically with common platforms like Google Calendar, Outlook, and Slack.

**Feedback Collection**
We proposed a dedicated feedback form embedded directly into the site, capturing structured ratings and comments rather than relying on unstructured emails or calls. We also recommended an optional field inviting suggestions for additional course offerings, giving the client a lightweight way to gauge demand for future service expansion.

## Cost-Benefit Analysis

For the two process improvements requiring paid third-party software, we built out a full cost-benefit comparison to help the client weigh investment against expected impact.

**Tutor Application Platform**

<table class="cost-table">
<tr><th>Category</th><th>Details</th><th>Estimated Cost</th></tr>
<tr><td>Subscription</td><td>Annual fee</td><td>$12,000/year</td></tr>
<tr><td>Setup</td><td>Initial setup</td><td>$1,000 (one-time)</td></tr>
<tr><td>Website Integration</td><td>Linking to platform</td><td>$1,000 (one-time)</td></tr>
<tr><td>Staff Training</td><td>Training sessions</td><td>$1,000 (one-time)</td></tr>
<tr><td>Maintenance</td><td>Annual support</td><td>$1,000/year</td></tr>
</table>

This option offered strong security features (dual authentication, encrypted data transfer), centralized applicant data management, and scalability as the client's tutor roster grows — but came with a meaningfully higher price tag, both up front and in ongoing subscription costs.

**Scheduling Platform**

<table class="cost-table">
<tr><th>Category</th><th>Details</th><th>Estimated Cost</th></tr>
<tr><td>Subscription</td><td>Annual fee</td><td>$14.40/month/tutor (~$172.80/year/tutor)</td></tr>
<tr><td>Website Integration</td><td>Embedding the calendar system</td><td>$500 (one-time)</td></tr>
<tr><td>Staff Training</td><td>Training sessions</td><td>$200 (one-time)</td></tr>
<tr><td>Maintenance</td><td>Annual support</td><td>$100/year</td></tr>
</table>

This option was significantly more affordable and simpler to integrate with the client's existing website platform, with strong ease-of-use for both tutors and students, though it came with a shorter adjustment period as staff transitioned to the new workflow.

Ultimately, we presented both options with their respective trade-offs rather than a single blanket recommendation, since the right choice depended on the client's budget priorities and appetite for a larger infrastructure investment versus a lighter-weight improvement.

## Client Feedback

We presented our findings and proposed solutions directly to the client in a final meeting. Feedback was largely positive: the client's leadership team was enthusiastic about the security and centralization benefits of the tutor application platform, though they flagged concerns about its ongoing cost and maintenance complexity. The scheduling platform recommendation was met with strong approval, particularly for its ease of use and reduced administrative burden — tutors and students alike responded well to the idea of self-service scheduling. Some feedback suggested further personalization, such as the ability to filter or select tutors by expertise, which we noted as a potential area for future iteration beyond the scope of this engagement.

## Results

The engagement delivered three fully mapped process improvements, each paired with a concrete implementation path and a transparent cost breakdown — giving the client the information needed to move forward at whatever pace fit their budget and growth plans. The scheduling and feedback improvements, in particular, offered strong impact relative to their cost, while the tutor application platform was framed as a larger, longer-term investment tied to the client's growth trajectory.

## Technologies

<ul class="tech-pills">
  <li>Process Mapping</li>
  <li>EPC Diagrams</li>
  <li>Cost-Benefit Analysis</li>
  <li>Stakeholder Interviews</li>
  <li>Business Process Consulting</li>
</ul>

## Key Takeaways

<div class="key-takeaways" markdown="1">

This project was a genuine introduction to what client-facing consulting work actually looks like — translating a stakeholder's pain points into a structured process map, and then a structured map into a concrete, costed recommendation. It reinforced that a good recommendation isn't just "the better option" in the abstract; it has to account for the client's actual budget, priorities, and appetite for change. Presenting two viable paths rather than a single verdict, and being transparent about the trade-offs of each, felt like a more honest and more useful way to support a real business decision. Working through this as a team also underscored how much a good client relationship shapes the quality of the final recommendation — the improvements we proposed were only as strong as our understanding of the client's actual day-to-day operations, which came directly from the time we invested in stakeholder conversations.

</div>

</div>
