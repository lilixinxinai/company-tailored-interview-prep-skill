---
name: company-tailored-interview-prep
description: Use when a job seeker needs evidence-based interview preparation for one specific company and role. Connects a redacted resume, the target JD, and sourced company information to create a company brief, candidate evidence map, likely question themes, follow-up drills, and reverse questions; does not invent company facts, write fake experience, or assist covertly during a live interview.
---

# Company Tailored Interview Prep

Prepare the candidate to explain real experience in the context of a real company and role.

## Required Inputs

Confirm:

- one redacted resume;
- one complete target JD;
- exact company or legal entity name and official website when available;
- interview round, format, language, and scheduled time when known;
- any recruiter message or interview instructions the user wants considered.

Handle one company and one role per run. If company identity is ambiguous, stop and resolve it before research.

## Source Rules

Research company facts in this order:

1. The company's official website, product pages, newsroom, filings, and verified recruitment pages.
2. Government registries, regulator disclosures, and other primary public records.
3. Reputable news outlets and dated industry reports.
4. Employee reviews, forums, and social posts only as opinions or leads.

For every material company claim, preserve the source URL, source type, publication date when available, and access date. Mark missing information 未查到, ambiguous information 待核验, and conflicts 来源冲突.

Do not infer company culture, workload, financial health, headcount, strategy, or hiring intent from weak signals.

## Workflow

1. Extract a candidate fact bank from the resume. Preserve titles, dates, scope, tools, outcomes, and exact metrics.
2. Parse the JD into hard requirements, core responsibilities, expected outcomes, tools, and likely evaluation areas.
3. Build a sourced company brief: business model, products, target users, recent verified developments, competitors only when sourced, and role-relevant context.
4. Explain the business-role connection: what problems this role likely supports, separating JD facts from reasoned hypotheses.
5. Map each important evaluation area to 直接证据, 部分证据, or 无证据 in the resume.
6. Produce a 60-second self-introduction outline using only direct evidence. Do not write claims the candidate cannot defend.
7. Create interview question themes across company motivation, resume deep dive, role expertise, business scenarios, and evidence gaps. For each include why it may be asked, an answer structure, usable evidence, likely follow-ups, and verification needs.
8. Create reverse questions that investigate the role's real goals, success measures, team boundaries, current priorities, and unresolved company information.
9. Offer an optional mock-interview mode. Ask one question at a time, follow up on vague or unsupported claims, and assess clarity, relevance, evidence, and reflection. Do not fabricate a model answer for memorization.

## Deliverables

Return these sections in order:

1. 准备边界: confirmed company, role, interview context, and missing inputs.
2. 来源覆盖: sources checked, dates, status, and gaps.
3. 公司与岗位情报: sourced facts, role-relevant interpretation, and clearly labeled hypotheses.
4. 简历证据地图: evaluation area, JD evidence, resume evidence, evidence level, and gap.
5. 一分钟自我介绍提纲: evidence-backed structure, not an invented biography.
6. 高概率问题与追问: question theme, why asked, answer structure, evidence, follow-ups, and verification needs.
7. 反问清单: questions tailored to the company, role, and unresolved facts.
8. 模拟训练方案: ordered drills and evaluation criteria.
9. 待核验与禁用说法: unsupported company claims, candidate gaps, and phrases not to use.

## Safety And Accuracy

- Never invent company facts, products, customers, strategy, financial data, workplace conditions, interview questions, or candidate experience.
- Do not present likely questions as questions the employer will definitely ask.
- Do not promise an interview score, offer, or hiring probability.
- Do not provide covert real-time assistance during an active interview.
- Do not upload or reveal confidential employer, recruiter, candidate, or client information.
- Do not infer protected personal attributes or recommend discriminatory answers.
