### Hi there 👋

[OpenDR](https://github.com/opendr-io) is a think-tank comprised of longtime security researchers and data scientists, with north of two centuries combined experience, active in the research community. Whenever we have some time, we start building. We have several current projects and products:

[CAUSALITY](https://github.com/opendr-io/causality) contains the output of a model predicting which CVEs are going to become 'hot' and get added to one or more watch-lists. This is the project presented at OWASP BASC. As of July, the model has made 33 correct predictions with early warning times as long as 137 days. This early wanring time allows us to actually shift "left of boom" and live our best lives. Every incident response we turn into incident avoidance gives time back to busy DevOPS teams while removing business risk.

[OpenDR](https://github.com/opendr-io/opendr) is a psutil based FOSS EDR alternative for Linux, MacOS and Windows. It generates most of what you would get from an EDR / OSquery like tool with lower cost of ownership and faster deployment. OpenDR can go places conventional EDR tooling can't go because it needs only Python 3.x and pip. We are adding an AI-based threat hunting component and there are some hunting notebooks, including one that uses AI, in the project.

If you're looking for the thing we presented at DEF CON / BLACKHAT, [PROTOSTAR](https://github.com/opendr-io/protostar-web) (originally code named 'skynet') this is our implementation of two things we believe 1) there are far better ways to take on the problem of alert fatigue and signal loss and 2) there are better ways to apply AI to alert processing and threat detection. PROTOSTAR uses a knowledge graph that is asymptotically efficient in polynomial time, processing tens of thousands of alerts per minute. It is effective at turning raw alert data into high signal with or without AI. Unlike many such tools, our pipelines allow for AI model processing of entire detection artifact streams at acceptable cost. Unlike many We did a release at DEF CON 2024, presented twice at Blackhat MEA, and are continuing to present at cons.

If you're looking for the ML based cloud persistence and exfiltration hunting project presented at RSA, [DUNE](https://github.com/opendr-io/dune) is a project for applying machine learning to threat hunting and detection with an initial focus on exfiltration. Most of the tools in there are FOSS but not all (we have dashboards for some popular products in addition to notebooks.)

There are also a few private projects. We're working on a tuned model for the PROTOSTAR project and an AI based threat hunting and detection component for the OpenDR project. We're also working on an AI based insider threat hunting and detection project. These will probably never be open sourced but please hit us up if you would like to use them: info at `info at opendr dot io.`


