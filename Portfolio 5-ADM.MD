# COIT11223 e-portfolio 5: Automated Decision-Making in Government

Kenil Patel | 12322652 | ICT Ethics and Governance in Society, Term 2 2026

## Where I started

Before this unit I saw ADM as a back-office upgrade. On the service desk I set up rules that blocked spam automatically, and nobody asked whether a filter rule was "ethical". I assumed government ADM worked the same way: if the code followed the rule, the decision was fair. These six artefacts trace how that view changed, starting with what ADM is, then an Australian welfare system that kept breaking the law, then how Spain and Denmark are dealing with the same problem.

| # | Artefact | Type | Where | Main unit link |
|---|----------|------|-------|----------------|
| 1 | Mark & Morison (2025) | Journal article | Global | Comparing ethical theories |
| 2 | Targeted Compliance Framework | News article | Australia | Social contract theory, ACS 1.2.4 |
| 3 | Deloitte's AI-written review | News article | Australia | Virtue ethics, ACS 1.2.3 |
| 4 | OAIC ADM transparency rule | Government fact sheet | Australia | Kantianism, ACS 1.2.1 |
| 5 | Spain's BOSCO ruling | NGO website | Spain | Rule utilitarianism |
| 6 | Amnesty's "Automated Malfare" | Conference video | Denmark | Act utilitarianism, ACS 1.2.2 |

---

## Artefact 1: What ADM actually means (journal article, global)

https://doi.org/10.17645/pag.10245

![Diagram comparing how the US, EU and China frame public sector ADM](images/ep5-artefact1-diagram.svg)

### Summary of the artefact
Mark and Morison (2025, p. 2) describe ADM as "any system in which decision‐making authority is partially or fully delegated to algorithms". They compare how the US, the EU and China govern ADM in the public sector and argue that each sees the problem differently: an "innovation gap" in the US, a "trust deficit" in the EU and a "stability risk" in China (Mark & Morison 2025, p. 2). Their conclusion is that all three are drifting towards putting innovation ahead of accountability (Mark & Morison 2025, p. 17).

### Justification on why I chose the artefact
I picked this article because its definition is wide enough to cover both a simple rules engine and a machine learning model, and both appear later in this portfolio. It is also the only artefact that compares whole countries, so it sets the scene before I focus on Australia.

### Reflection
The three framings lined up with the Week 4 theories. The US "innovation gap" reads like act utilitarianism, adding up benefits case by case. The EU's focus on trust is closer to Kant, where people have rights that a calculation cannot override. China's "stability" sounds like a social contract where citizens trade some freedom for order. I learned that a country's ethical starting point, even if it is never stated, shapes the rules ICT professionals end up building systems under.

---

## Artefact 2: When the law changed and the code did not (news article, Australia)

https://www.abc.net.au/news/2025-08-06/commonwealth-ombudsman-finds-payment-cancellation-unlawful/105616010

![Diagram of the Targeted Compliance Framework timeline: 964 payments cancelled after the law changed from must to may](images/ep5-artefact2-diagram.svg)

### Summary of the artefact
Truu (2025) reports on a Commonwealth Ombudsman finding that the Targeted Compliance Framework, the IT system that tracks jobseekers' mutual obligations, automatically cancelled the payments of 964 people between April 2022 and July 2024. Laws passed after Robodebt changed "must cancel" to "may cancel", so a person had to consider each jobseeker's situation first. The system was never updated and kept cancelling on its own.

### Justification on why I chose the artefact
I chose this because it is a current Australian system, not a historical one. Most people know about Robodebt, but fewer know that a similar failure happened afterwards, even with new laws in place. It proves that lessons from one scandal do not automatically reach the code.

### Reflection
What struck me is that the law changed one word and the software did not. The Ombudsman said adequate care and skill were not applied (Truu 2025), which is very close to the ACS value of Competence (1.2.4) (ACS 2014). The Ombudsman's own better practice guide says automated systems must meet the same legal and fairness standards as a human decision maker (Commonwealth Ombudsman 2025). Under social contract theory, welfare is a two-way deal: jobseekers meet their obligations and the government follows its own rules. Here only one side was held to the deal. For me as a future IT worker, keeping a system in line with current law is part of the job, not something to leave to the legal team.

---

## Artefact 3: The review that was written with AI (news article, Australia)

https://fortune.com/2025/10/07/deloitte-ai-australia-government-report-hallucinations-technology-290000-refund

![Diagram showing the chain from the automated welfare system to Deloitte's AI-assisted review and the errors found](images/ep5-artefact3-diagram.svg)

### Summary of the artefact
Paoli (2025) reports that Deloitte was paid about A$440,000 to review the same Targeted Compliance Framework. A University of Sydney researcher, Chris Rudge, found that the 237-page report cited research and a book that do not exist and included a made-up quote from a Federal Court judgment. The corrected version disclosed that Azure OpenAI had been used, and Deloitte agreed to a partial refund.

### Justification on why I chose the artefact
I chose this because it looks at the system from Artefact 2 from a different angle. The review that was meant to hold an automated system to account was itself produced with an automated tool, and nobody checked it properly before it was published on a government website.

### Reflection
This one felt personal, because I use AI tools for study and work and I include an AI use statement in every e-portfolio. Virtue ethics asks what an honest, careful professional would do, and the answer here is to check every reference before your name goes on the report. ACS value 1.2.3 Honesty expects us not to mislead the people who rely on our work (ACS 2014). The lesson I am taking into ICT is simple: AI can help draft, but a human has to own and verify the output.

---

## Artefact 4: Australia's new ADM transparency rule (government fact sheet, Australia)

https://www.oaic.gov.au/__data/assets/pdf_file/0020/269012/APP-1.7-1.9-Transparency-Obligation-Supplementary-Government-Fact-Sheet.PDF

![Diagram comparing what the new Privacy Act ADM rule requires of agencies against what it leaves out](images/ep5-artefact4-diagram.svg)

### Summary of the artefact
This OAIC (2026) fact sheet explains how government agencies must meet new Privacy Act obligations starting on 10 December 2026. Agencies must state in their privacy policies what kinds of personal information their computer programs use and what kinds of decisions those programs make or substantially inform. It says agencies "should clearly state the types of ADM they use to make automated decisions, not just artificial intelligence (AI)" (OAIC 2026, p. 2).

### Justification on why I chose the artefact
I chose this because it is the most current artefact in my portfolio. The rule starts later this year, which shows Australia's response to ADM is still being written. Its examples, including visa risk scoring and support payment eligibility, connect directly to the government systems this e-portfolio covers.

### Reflection
At first I thought this fixed the problem, but the rule only requires disclosure. It does not give people a right to challenge a decision (Rountree, Bloch & Guyot 2026). From a Kantian view, telling someone a program judged them without giving them a way to respond still treats them as a case number rather than a rational person. ACS value 1.2.1 asks us to put the public interest first (ACS 2014). If I build one of these systems, I would treat the disclosure rule as the minimum and also design a clear way to appeal.

---

## Artefact 5: Spain is forced to open up BOSCO (NGO website, Spain)

https://civio.es/novedades/2025/09/18/civio-pulls-back-the-curtain-on-public-algorithms-spains-supreme-court-orders-the-government-to-release-boscos-source-code/

![Timeline of Civio's seven-year fight for BOSCO's source code, ending in the 2025 Supreme Court order](images/ep5-artefact5-diagram.svg)

### Summary of the artefact
Civio (2025), a Spanish non-profit, reports that Spain's Supreme Court ordered the government to release the source code of BOSCO, the program that decides who receives a discount on their electricity bill. The government had refused since 2018, citing national security and intellectual property. The court rejected those reasons and said public authorities must explain in an understandable way how the algorithms that affect citizens work.

### Justification on why I chose the artefact
I chose this as my overseas government system because it is the opposite of the secrecy in Denmark (Artefact 6), and the push came from a court rather than a regulator. It also took a small non-profit seven years to win, which shows how hard transparency is to get.

### Reflection
As a cyber security student, the part that stood out was the court's point that independent scrutiny can expose "unnoticed vulnerabilities" (Civio 2025). That is the same argument I made in my Assessment 1 video on vulnerability disclosure. Using rule utilitarianism, a general rule that public decision-making code must be open to scrutiny produces more good over time than secrecy decided case by case, because errors get caught before they reach thousands of people. It made me see that transparency and security are not opposites.

---

## Artefact 6: Denmark's welfare algorithms (conference talk video, Denmark)

https://media.ccc.de/v/38c3-automated-malfare-discriminatory-effects-of-welfare-automation

![Diagram of how personal data such as ties to non-EEA countries feeds Denmark's fraud models](images/ep5-artefact6-diagram.svg)

### Summary of the artefact
In this talk at the 38th Chaos Communication Congress, Amnesty International's digital team (Amnesty International 2024a) presents research on welfare automation in several countries. In Denmark, the welfare agency Udbetaling Danmark uses dozens of algorithms that combine personal data to flag possible fraud. One model, "Model Abroad", targets people with ties to countries outside the European Economic Area (Amnesty International 2024b). Amnesty argues the system may amount to social scoring, which the EU AI Act bans.

### Justification on why I chose the artefact
I chose a video so the portfolio is not only text, and because hearing the researchers explain how they investigated the system made the Danish case clearer than reading about it. It also shows that ADM problems are spreading across countries rather than staying in one.

### Reflection
This one hit close to home. I moved to Sydney from India this year, so I have strong ties to a country outside where I now live. Under a model that treats "foreign affiliation" as a risk signal, someone like me could be flagged without doing anything wrong. An act utilitarian might argue that flagging many people to catch a few frauds is worth it overall, but this case shows the weakness of that theory: the harm keeps landing on the same minority. ACS value 1.2.2 asks us to consider how our work affects people's quality of life (ACS 2014). I now think a model should be tested on who it flags, not only on how accurate it is.

---

## What changed for me

I started this unit thinking ADM was neutral. I now see every automated decision as carrying the choices of the people who designed it, approved it and kept it running. Across these six artefacts, the harm came from a law the code ignored, a review nobody checked, a rule with no appeal and data that treats some people as suspects by default. Mark and Morison (2025, p. 17) warn that governments are favouring innovation over accountability. As someone heading into cyber security, I want to be the person in the room who asks three questions: does the system match the current law, has a human verified the output, and who does it flag?

---

## AI usage statement

I used Claude, an AI assistant, to help search for candidate sources, check facts against the original pages, plan the structure, draft the text and generate the six diagrams. I chose the final six artefacts, opened and checked every source and reference myself, and edited the summaries and reflections so they reflect my own views and experience.

---

## References

Amnesty International 2024a, *Automated malfare: discriminatory effects of welfare automation*, video, 38th Chaos Communication Congress, media.ccc.de, 28 December, viewed 13 October 2026, <https://media.ccc.de/v/38c3-automated-malfare-discriminatory-effects-of-welfare-automation>.

Amnesty International 2024b, 'Denmark/EU: AI-powered welfare system fuels mass surveillance and risks discriminating against marginalized groups', *Amnesty International USA*, 13 November, viewed 13 October 2026, <https://www.amnestyusa.org/press-releases/denmark-eu-ai-powered-welfare-system-fuels-mass-surveillance-and-risks-discriminating-against-marginalized-groups/>.

Australian Computer Society (ACS) 2014, *ACS code of professional conduct*, version 2.1, ACS, Sydney, viewed 13 October 2026, <https://www.acs.org.au/content/dam/acs/rules-and-regulations/Code-of-Professional-Conduct_v2.1.pdf>.

Civio 2025, 'Civio pulls back the curtain on public algorithms: Spain's Supreme Court orders the Government to release BOSCO's source code', *Civio*, 18 September, viewed 13 October 2026, <https://civio.es/novedades/2025/09/18/civio-pulls-back-the-curtain-on-public-algorithms-spains-supreme-court-orders-the-government-to-release-boscos-source-code/>.

Commonwealth Ombudsman 2025, *Automated decision-making: better practice guide*, Commonwealth Ombudsman, Canberra, viewed 13 October 2026, <https://www.ombudsman.gov.au/__data/assets/pdf_file/0025/317437/Automated-Decision-Making-Better-Practice-Guide-March-2025.pdf>.

Mark, D & Morison, J 2025, 'Governing AI decision-making: balancing innovation and accountability', *Politics and Governance*, vol. 13, article 10245, viewed 13 October 2026, <https://doi.org/10.17645/pag.10245>.

Office of the Australian Information Commissioner (OAIC) 2026, *APP 1.7-1.9 transparency obligation: supplementary fact sheet for government agencies*, OAIC, Sydney, viewed 13 October 2026, <https://www.oaic.gov.au/__data/assets/pdf_file/0020/269012/APP-1.7-1.9-Transparency-Obligation-Supplementary-Government-Fact-Sheet.PDF>.

Paoli, N 2025, 'Deloitte was caught using AI in $290,000 report to help the Australian government crack down on welfare after a researcher flagged hallucinations', *Fortune*, 7 October, viewed 13 October 2026, <https://fortune.com/2025/10/07/deloitte-ai-australia-government-report-hallucinations-technology-290000-refund>.

Rountree, D, Bloch, V & Guyot, I 2026, 'Mandatory automated decision-making disclosure requirements are coming: key takeaways from the OAIC guidance', *Allens*, 2 October, viewed 13 October 2026, <https://www.allens.com.au/insights-news/insights/2026/10/mandatory-automated-decision-making-disclosure-requirements-are-coming-key-takeaways-from-the-oaic-guidance/>.

Truu, M 2025, 'Automatic systems unlawfully cancelled 964 jobseekers' payments in two years, watchdog finds', *ABC News*, 6 August, viewed 13 October 2026, <https://www.abc.net.au/news/2025-08-06/commonwealth-ombudsman-finds-payment-cancellation-unlawful/105616010>.
