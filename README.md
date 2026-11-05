From Votes to Execution



An Open Protocol for Verifiable, Expert-Informed Collective Governance



Public-domain concept proposal — CC0 1.0



Abstract



Modern representative systems allow citizens to select political representatives, but the relationship between citizens' preferences and the decisions ultimately made in their name can remain indirect, intermittent, and difficult to verify.



Digital participation platforms have made it easier to propose policies, deliberate, and vote. Yet an important design challenge remains: how can collective preferences, expert analysis, transparent decision procedures, and verifiable implementation be connected within a coherent governance process?



This proposal outlines an open, adaptable protocol for collective governance. It combines verified eligibility, privacy-preserving participation, structured expert review, public deliberation, auditable voting, and transparent follow-through on adopted decisions.



The proposal does not assume that blockchain is necessary for every component, that majority voting is sufficient for legitimate governance, or that an online vote automatically has legal force. Instead, it invites researchers, civic organizations, universities, developers, and public institutions to evaluate, improve, implement, and freely reuse the model.



The long-term ambition is to make meaningful participation in collective decision-making more continuous, accessible, accountable, and verifiable.



1. The problem



Representative democracy addresses a fundamental coordination problem: large populations cannot deliberate and decide every public matter through continuous direct participation.



However, delegation creates a second problem. Citizens may have limited practical means to express preferences between elections, evaluate proposals before adoption, monitor whether commitments are fulfilled, or challenge a decision through a transparent, repeatable process.



Digital platforms can reduce the cost of participation, but publishing proposals or collecting votes is not sufficient by itself. A complete decision process must also address:



- Who is eligible to participate?

- How can duplicate or fraudulent participation be limited?

- How can participants assess technical, financial, legal, and social consequences?

- How can dissenting views and minority rights be protected?

- How can voting integrity be independently checked?

- Who is responsible for implementing an adopted decision?

- What happens when implementation is delayed, rejected, or impossible?



The central research question is therefore not simply how to digitize voting. It is how to connect participation, deliberation, decision, implementation, and accountability in one coherent and auditable process.



2. Proposed concept



The proposed system is an open governance protocol that can be adopted by different communities and institutions.



It is not intended to begin as a sovereign state, a replacement for every existing government, or a cryptocurrency project. Its initial purpose is to provide reusable rules and technical components for making collective decisions.



A complete process would contain the following stages.



Stage A — Proposal submission



Eligible participants submit proposals concerning policies, rules, projects, budgets, or institutional changes. Each proposal follows a standardized format describing the problem, intended outcome, proposed action, expected costs, assumptions, and possible alternatives.



Duplicate proposals may be consolidated transparently, without silently eliminating unpopular or minority viewpoints.



Stage B — Eligibility and procedural validation



The system checks whether the proposal satisfies published procedural requirements. These checks should be reproducible and appealable.



Eligibility requirements depend on the adopting institution. A voluntary international community, a university, a cooperative, and a national electorate have different legal and administrative requirements.



Stage C — Expert-informed review



Relevant specialists examine the proposal within their areas of competence. A financial proposal may require economic and fiscal analysis; a public-health proposal may require clinical and public-health expertise; a legal reform may require constitutional and statutory analysis.



Reviewers publish supporting evidence, assumptions, uncertainties, conflicts of interest, and reasoned conclusions.



Expert review should inform decisions, not automatically replace collective judgment. The protocol should provide a transparent route for challenging procedural errors, requesting additional analysis, and presenting minority reports.



Stage D — Public deliberation



Participants receive accessible explanations of the proposal, including arguments for and against it, material trade-offs, expected costs, and unresolved questions.



Where practical, deliberation should precede voting. The system should distinguish verified facts from estimates, forecasts, and opinions.



Stage E — Voting



Voting rules are established before the vote begins. They specify eligibility, the approval threshold, any quorum, the treatment of abstentions, the voting period, and procedures for challenges or recounts.



The system records enough information to enable independent verification of the outcome while protecting individual voting choices.



A simple majority may be suitable for some internal decisions, but it is not universally appropriate. Constitutional rules, minority protections, high-impact decisions, and legal requirements may demand additional safeguards.



Stage F — Decision status and implementation



The result is assigned an explicit status, such as advisory recommendation, internally binding community decision, or formally adopted institutional decision.



Where implementation is possible, the responsible institution, required resources, milestones, and review dates are recorded. Subsequent reports distinguish completed actions from partial implementation, rejection, delay, and unresolved status.



A digital result does not acquire legal authority merely because it has received votes. Binding effect must arise from a valid legal or institutional framework.



Stage G — Audit and correction



The process maintains an auditable record of proposal versions, procedural rules, published analyses, voting totals, challenges, corrections, and implementation updates.



The system should make errors detectable and correctable. Transparency must not require exposing voters' identities or sensitive personal information.



3. Identity, privacy, and security



Blockchain technology may be useful for particular components, such as publishing tamper-evident commitments to records or distributing control over verification. It is not a complete identity, privacy, or voting-security solution.



The protocol should separate four concerns:



1. Eligibility: establishing that a participant meets the applicable requirements.

2. Uniqueness: limiting multiple participation by the same eligible person in the same decision.

3. Ballot secrecy: preventing the public or administrators from linking an individual's identity to their voting choice.

4. Outcome verification: enabling independent checks that valid votes were counted according to the published rules.



Personal identity documents and sensitive records should not be placed on a public blockchain. Privacy-preserving credentials, cryptographic proofs, secure authentication, and independent security audits may be relevant, but their suitability must be established through threat modelling and testing.



The system must not claim to be impossible to hack or manipulate. Its security documentation should describe assumptions, known limitations, attack scenarios, and recovery procedures.



4. Expert committees and collective legitimacy



Expertise and democratic legitimacy solve different problems.



Experts can help evaluate evidence, feasibility, uncertainty, costs, and likely consequences. Citizens can express priorities, values, preferences, and judgments about trade-offs. Neither contribution should be treated as a complete substitute for the other.



Committee membership should use transparent qualification criteria, verifiable credentials where available, conflict-of-interest disclosures, and procedures for challenging appointments or decisions.



The protocol should avoid creating a permanent expert class with unreviewable authority. It should also avoid assuming that every technically complex issue can be resolved through an unqualified majority vote.



Different decision categories may require different procedures. These categories and their rules should be published before decisions are made.



5. Constitutional safeguards and minority rights



A system that gives majorities unrestricted power can reproduce serious forms of injustice.



Any implementation intended to exercise meaningful authority should define limits on the decisions that can be taken by ordinary majority vote. These limits may include fundamental rights, due process, privacy, protection from discrimination, and independent mechanisms for reviewing procedural violations.



The protocol should also provide for dissenting opinions, appeals, conflicts of interest, and the possibility of correcting or reversing decisions through predefined procedures.



The exact safeguards must be adapted to the legal and institutional context in which the protocol is used.



6. Implementation model



The proposal recommends an incremental path rather than an immediate attempt to create a fully functioning online government.



Phase 1 — Research and specification



Document existing systems, identify the features they already provide, and define the unresolved requirements. Publish a protocol specification and a threat model.



Phase 2 — Institutional or community pilot



Test the process within a voluntary association, university group, cooperative, or other community whose members can legitimately agree to the applicable rules.



Use non-sensitive test data initially. Evaluate usability, accessibility, participation, fairness, dispute resolution, security, and the clarity of implementation responsibilities.



Phase 3 — Independent evaluation



Invite technical, legal, economic, privacy, and democratic-governance specialists to review the design. Publish failures and limitations alongside successful results.



Phase 4 — Reusable open infrastructure



Where the pilot justifies further development, release reusable components, documentation, test cases, and implementation guidance under appropriate open licenses.



Phase 5 — Institutional adoption



Explore adoption by organizations or public institutions only where a valid legal basis, accountable governance structure, and appropriate security standards exist.



National elections, referendums, and legally binding public decisions require substantially stronger safeguards than a voluntary community pilot.



7. Relationship to existing work



This proposal does not claim to originate digital participatory democracy, blockchain governance, electronic voting, expert deliberation, or open-source civic technology.



Existing projects provide important foundations and reference points.



- Decidim provides open-source infrastructure for participatory democracy, including proposals, deliberation, voting, and institutional participation.

- Bitcoin provides a foundational example of a decentralized transaction-verification system, but its consensus mechanism does not itself solve political legitimacy or policy evaluation.

- Deliberative-democracy research and practice offer methods for structured public reasoning, informed discussion, and the consideration of competing perspectives.



The proposed contribution is a research agenda for connecting these concerns into an explicit, modular process with particular attention to eligibility, privacy, expert review, auditable voting, decision status, and implementation tracking.



Whether this combination constitutes a novel technical or institutional contribution remains an open research question. A systematic review and comparison with existing systems is required before making any claim of originality.



8. Research questions



The following questions should guide development and evaluation.



1. Can eligibility and uniqueness be verified without unnecessarily exposing personal identity?

2. Which components benefit from distributed ledgers, and which are better implemented using conventional databases or other cryptographic techniques?

3. How can ballot secrecy and independently verifiable outcomes be achieved together?

4. What qualification and conflict-of-interest rules make expert review credible without allowing experts to monopolize authority?

5. Which decisions should be advisory, internally binding, or legally binding?

6. How should the system protect minority rights and handle contested or irreversible decisions?

7. What mechanisms can connect a recorded decision to an accountable implementation process?

8. How can the system remain accessible to people with limited digital literacy, unreliable connectivity, disabilities, or limited access to identity documents?

9. What forms of governance, oversight, and independent auditing are necessary to prevent capture by administrators, funders, or powerful participants?

10. Under what conditions does the system improve participation, decision quality, accountability, or public trust compared with existing alternatives?



These questions should be answered through research and evaluation, not assumptions.



9. Evaluation criteria



A pilot should be evaluated against explicit measures, including:



- The proportion of proposals meeting published procedural requirements.

- The accuracy and completeness of expert reviews.

- The incidence of duplicate participation and procedural violations.

- The ability of independent reviewers to verify voting outcomes.

- The frequency and resolution of appeals.

- Participants' understanding of proposals and decision rules.

- Accessibility across different demographic and technical circumstances.

- The transparency of implementation status.

- The cost of operating and maintaining the system.

- The ability to identify, correct, and document errors.



Evaluation should include negative findings. A system should not be considered successful merely because it attracts participants or produces a high volume of votes.



10. Open development and public benefit



The concept is intended for unrestricted reuse and further development.



Researchers, developers, universities, civic organizations, public institutions, and independent communities are invited to:



- Critically assess the proposal and its relationship to existing work.

- Identify prior research, implementations, and unresolved problems.

- Propose alternative designs and technical standards.

- Develop independent pilots and publish their results.

- Translate and adapt the framework to different legal and cultural contexts.

- Reuse, modify, or replace any component that proves ineffective.



No institution is asked to endorse the proposal merely because it is presented here. The appropriate response is independent scrutiny, experimentation, and evidence-based evaluation.



Conclusion



Digital governance should not be judged by how sophisticated its interface or underlying technology appears. It should be judged by whether people can participate meaningfully, whether decisions are made through fair and understandable procedures, whether results can be independently checked, and whether responsible institutions follow through.



An open protocol connecting proposal submission, expert-informed deliberation, privacy-preserving participation, verifiable voting, and implementation accountability could provide a useful framework for experimentation.



Its value remains to be demonstrated. Its design should remain open to criticism, comparison, modification, and replacement.



The invitation is simple: study the proposal, compare it with existing systems, test its assumptions, and develop whatever proves useful.



Public-domain dedication: This concept document is intended to be released under the CC0 1.0 Universal Public Domain Dedication, to the extent permitted by law. No exclusive ownership of the document's text is claimed. Existing works, third-party materials, trademarks, patents, privacy rights, and other rights are not transferred or waived by this statement.



Selected references



- Nakamoto, S. Bitcoin: A Peer-to-Peer Electronic Cash System. https://bitcoin.org/bitcoin.pdf

- Decidim. Open-source participatory democracy infrastructure. https://decidim.org/

- Decidim Documentation. What is Decidim? https://docs.decidim.org/en/develop/whitepaper/what-is-decidim.html

- Creative Commons. CC0 1.0 Universal. https://creativecommons.org/publicdomain/zero/1.0/

- Democracy R&D. International network for deliberative democracy. https://democracyrd.org/ 

