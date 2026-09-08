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

  .metric-callout {
    display: flex;
    flex-wrap: wrap;
    gap: 0.75rem;
    margin: 1rem 0 1.5rem;
  }

  .metric-callout div {
    flex: 1;
    min-width: 160px;
    padding: 0.9rem 1rem;
    background: #fffbeb;
    border: 1px solid #fde68a;
    border-radius: 8px;
  }

  .metric-callout strong {
    display: block;
    font-size: 1.3rem;
    color: #92400e;
  }

  .metric-callout span {
    font-size: 0.85rem;
    color: #6b7280;
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

As part of a semester-long consulting engagement, I participated in a group project that partnered with a small, locally-owned tutoring service to analyze their current business processes and identify opportunities for improvement. We worked directly with the client's Director of Operations to conduct stakeholder interviews, map existing workflows using Event-Driven Process Chain (EPC) diagrams, and diagnose three core processes with measurable inefficiencies. We focused on the tutor application process, tutoring session scheduling, and student feedback collection. From there, we evaluated third-party solutions by conducting a cost-benefit analysis to support the client's final decision.

## Project Goals

- Diagnose inefficiencies in current business processes through structured stakeholder analysis
- Translate qualitative interview findings into visual process maps for objective comparison
- Evaluate competing software solutions using a consistent cost framework
- Quantify the cost and projected impact of each proposed improvement
- Deliver findings that support, rather than dictate, the client's final decision

## Current State Analysis

Analysis began with  interviews with the client's leadership to understand their business model, systems, and sources of frustration within the organization. We translated these qualitative findings into EPC diagrams for three key processes, since visualizing each of these processes let us identify exactly where delays occurred.

**Tutor Application Process**
Mapping the process showed that applicants had to navigate through an unrelated "Contact" tab just to find the job application link, and the form itself captured only contact information and had nothing  to collect any other useful data like GPA or prior tutoring experience. There was no structured way to screen or compare applicants.

**Individual Tutoring Session Scheduling**
Process mapping revealed a that scheduling relied on manual emails between a tutor and student before a session could be confirmed. We flagged this as the primary source of scheduling delays, since the process had no defined turnaround time and relied entirely on staff availability to relay information back and forth.

**Feedback Collection**
There was no structured intake process, as feedback arrived as unstructured emails or calls. The client had no way to aggregate, quantify, or trend feedback over time.

## Proposed Improvements

**Tutor Application Process**
We proposed routing applicants to a dedicated third-party application platform that was capable of collecting structured, comparable data on every application and automatically flagging any incomplete submissions.

**Individual Tutoring Session Scheduling**
We proposed replacing the manual email exchange with a live scheduling integration, which would allow students to view real-time tutor availability and confirm a session in a single step.

**Feedback Collection**
We proposed a structured feedback form capturing satisfaction ratings, service type, and open comments to give the client a readable dataset rather than unstructured reviews.

**Example EPC Diagram**

*Above is the proposed process for scheduling tutoring sessions and removing the manual setup between client and student*

## Cost-Benefit Analysis

To support an objective comparison rather than a subjective preference, we built a structured cost breakdown for each proposed software solution, evaluating both one-time and recurring costs side by side.

<div class="metric-callout">
  <div><strong>~$15,000</strong><span>Est. Year 1 cost — application platform</span></div>
  <div><strong>~$2,150</strong><span>Est. Year 1 cost — scheduling platform</span></div>
  <div><strong>3</strong><span>Core processes analyzed</span></div>
</div>

**Tutor Application Platform**

<table class="cost-table">
<tr><th>Category</th><th>Details</th><th>Estimated Cost</th></tr>
<tr><td>Subscription</td><td>Annual fee</td><td>$12,000/year</td></tr>
<tr><td>Setup</td><td>Initial setup</td><td>$1,000 (one-time)</td></tr>
<tr><td>Website Integration</td><td>Linking to platform</td><td>$1,000 (one-time)</td></tr>
<tr><td>Staff Training</td><td>Training sessions</td><td>$1,000 (one-time)</td></tr>
<tr><td>Maintenance</td><td>Annual support</td><td>$1,000/year</td></tr>
</table>

This option scored highest on security and scalability due to its use of dual authentication, encrypted data transfer, and centralized applicant records. But, analysis showed a substantially higher total cost of ownership, driven primarily by its recurring annual subscription rather than one-time implementation costs.

**Scheduling Platform**

<table class="cost-table">
<tr><th>Category</th><th>Details</th><th>Estimated Cost</th></tr>
<tr><td>Subscription</td><td>Annual fee</td><td>$14.40/month/tutor (~$172.80/year/tutor)</td></tr>
<tr><td>Website Integration</td><td>Embedding the calendar system</td><td>$500 (one-time)</td></tr>
<tr><td>Staff Training</td><td>Training sessions</td><td>$200 (one-time)</td></tr>
<tr><td>Maintenance</td><td>Annual support</td><td>$100/year</td></tr>
</table>

By contrast, this option's cost scaled with tutor headcount rather than a flat enterprise fee, making it substantially cheaper at the client's current size and lower-risk to pilot before a larger commitment.

Rather than issuing a single blanket recommendation, we presented both options with their quantified trade-offs, since the right choice ultimately depended on the client's budget constraints and risk tolerance.

## Client Feedback

We presented our analysis and recommendations directly to the client in a final meeting, incorporating feedback from our meetings throughout the engagement. The client's leadership had a positive response to the application platform's security and scalability, through they flagged the cost as a longer-term consideration rather than an immediate priority. The scheduling platform was met with a strong approval given its lower cot and ease of use. Both tutors and students responded well to the proposal of automated, self-service scheduling. Feedback also brought up a potential future addition for filtering tutors by expertise or rating, which was noted for a future implementation.

## Results

Our engagement delivered three fully diagnosed process gaps, each with a quantified improvement path. By grounding every proposal in a structured cost comparison, we gave the client a clear way to prioritize: the scheduling and feedback improvements offered strong impact at low cost and were positioned as near-term wins, while the tutor application platform was a larger investment to revisit as the client's staffing needs grow.

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

Working through this project showed me that proper consulting and analysis requires going beyond identifying the problem, but also necessitates comparable solutions so the client can make an informed decision. Translating loosely described pain points into EPC diagrams was a useful way to help us visualize the problems at hand. It was extremely useful in identifying exactly where processes broke down, as well as show stakeholders where they could be improved. Building out the cost-benefit analysis allowed us to quantify solutions and clearly show trade-offs. This form of analysis felt like a more honest and useful way to support a real business decision. Working as a team on and assisting a real organization reinforced how crucial our collective quality of analysis had to be in order to drive positive results and make a difference for this cleint.

</div>

</div>
