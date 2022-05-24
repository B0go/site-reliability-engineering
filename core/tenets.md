# The tenets of SRE

This file contains the tenets of Site Reliability Engineering. Its content is highly based in the Site Reliability Engineering Book that is available to read for free [here](https://sre.google/sre-book/table-of-contents/)


### Ensuring durable focus on engineering

This tenet describes how important it is to maintain the focus in handling problems and tasks using engineering practices. To drive that, SRE teams rely on metrics that observe what kind of work is being executed by the team and create a goal (or limit) to some of them, for example, limiting the number of manual tasks to 50% of all work.

What kind of work is executed by a specific SRE team varies from company to company, depending on its size and other factors. The statement that SRE should focus 50% of the time "developing solutions" may sound confusing because it is common for smaller teams to spend more time provisioning, configuring, and using great tools already available in the community (Kubernetes, Prometheus, Jaeger to name a few), but in my experience the main goal of this tenet is to guarantee that we acknowledge the work that we currently do and use this information to drive decisions on what we do next, keeping in mind that there is a good chance that a manual task will not scale long term and generates a lot of harmful side effects to the team and the company.



 Tenets of SRE
  -  Ensuring focus on engineering
  -  Maximum velocity based on SLO
  -  Monitoring (and automating actions triggered by monitoring)
  -  Emergency response - playbooks, MTTE and MTTD
  -  Change management (prog rollouts, detect problems, roll back)
  -  Demand forecasting and capacity planning
  -  Provisioning (provisioning capacity only when needed)
  -  Efficiency and performance
