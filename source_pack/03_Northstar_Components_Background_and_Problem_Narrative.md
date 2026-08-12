# Northstar Components AS — Company Background and Problem Narrative

> **Fictional teaching case.** Northstar Components AS, its people, and all figures below are invented for this workshop. If you are using this as a design exercise, read this narrative before opening the filled Canvas example.

## A short history of the company

Northstar Components AS began in Kongsberg in 1998 as a small machining company founded by two engineers and a toolmaker. Its first customers were Norwegian manufacturers that needed short production runs of precision metal parts. The company built its reputation on dependable delivery, practical engineering support, and the ability to handle products that were too specialized for high-volume suppliers.

During the 2000s, Northstar moved beyond individual parts and began producing complete mechanical and electromechanical subassemblies. Its customers now operate in maritime technology, energy, industrial automation, and advanced manufacturing. The company has approximately 180 employees and runs production across three shifts. Some customer orders are repeated every month, while others involve small batches with frequent engineering changes.

Northstar has invested steadily in CNC machines, robotic assembly, digital production planning, machine monitoring, and computerized maintenance. However, these systems were introduced at different times and for different purposes. They work well individually, but information does not always move smoothly between them. Like many established industrial companies, Northstar is therefore both highly automated and surprisingly dependent on people copying, interpreting, and passing information from one system to another.

Assembly Line 2 illustrates this tension. The line produces several variants of actuator modules, so priorities, equipment conditions, open maintenance work, and quality issues can change within a single shift. A good handover between supervisors is essential to keeping the next shift informed.

## The problem, as the Production Manager explains it

**Speaker: Ingrid Solberg, Production Manager**

> Let me describe the situation as we experience it.
>
> At the end of every shift, the outgoing supervisor on Assembly Line 2 prepares a handover for the incoming supervisor. It should explain what we produced, what is still in progress, which alarms occurred, whether maintenance work is open, and which actions the next shift must follow up.
>
> The difficulty is that the information is not in one place. Production quantities and order status are in the production system. Machine alarms are shown in a monitoring dashboard. Maintenance has its own ticket system. We also have an approved shift log for comments and unresolved actions. The supervisor moves between these systems, decides what matters, and writes a handover brief.
>
> Most supervisors are experienced and know the line well, but each person has developed a slightly different way of doing this. Some start with production status; others start with alarms. One person writes a detailed narrative, while another uses short bullet points. If the next supervisor is standing nearby, part of the handover may also be explained orally. That works until somebody is delayed, absent, or needs to check later what was actually said.
>
> We reviewed ten recent handovers as a small internal exercise. The median preparation time was about 35 minutes. Three of the ten briefs omitted at least one open action or did not include a reference that allowed the reader to find the original record. We also found that urgent items could appear in different places depending on who wrote the brief.
>
> I do not want to exaggerate this. We have not had a major incident caused by a handover. Still, the process is fragile. If an open maintenance action is missed, work may be repeated or delayed. If equipment status is described inaccurately, the incoming supervisor may begin the shift with the wrong understanding. The consequence could be wasted time, a production interruption, or—in a more serious situation—a safety concern.
>
> Some colleagues have suggested using generative AI to assemble and summarize the information. That may be useful, but I am cautious. A fluent summary can sound certain even when it has misunderstood a record. I would be especially concerned if a generated brief claimed that equipment was safe or available to operate without an approved source and confirmation from the responsible person.
>
> We also need to be careful about information boundaries. The handover should use approved operational records for Assembly Line 2. It should not pull in employee performance comments, absence information, customer correspondence, commercial details, security credentials, or informal chat messages simply because those are available somewhere in the company.
>
> I am not asking for a fully automated solution. I want to know whether there is a small, controlled way to test whether AI can reduce the work of finding and organizing information without weakening accuracy or accountability. The supervisor must still understand the situation and remain responsible for what is released to the next shift.
>
> If we run a pilot, I need more than a promise that it will save time. I need to know what information it may use, what it must never do, who checks the result, how we will measure whether the test helped, and what kind of mistake would make us pause immediately.

## Your design task

Use Ingrid’s account to design a **Slim AI Opportunity Canvas** for Northstar Components AS. Treat the narrative as an initial management briefing, not as a complete technical specification. Where the evidence is incomplete, state what the team would need to measure, verify, or clarify before a real pilot.

Your proposal should be useful enough to test, but narrow enough to stop, review, and reverse safely.

