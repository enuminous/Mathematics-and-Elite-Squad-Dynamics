# The Waiting Room of Maximum Efficiency

*Mathematics and Elite Squad Dynamics · Dispatch 19 · Mathematical satire · 18 November 2026*

*By Matthew Chenoweth Wright | Monolithic LLC*

**Fictional satire.** The office, dialogue, motives, and waiting-room monarchy are invented. The mathematical note distinguishes established queueing results from claims about actual institutions.

By the time my number was called, the waiting room had developed a constitution. Its northern benches favored proportional representation; the vending machine supported hereditary monarchy. At Window One, a clerk processed applications with magnificent efficiency while the director patrolled for evidence of leisure. A three-second pause brought a written warning. “Unused capacity is wasted capacity,” he announced, stepping over a pensioner who had entered as an undergraduate. I had come to renew the journal’s license to describe things as absurd, but the application required a recent example, and by now my original evidence had grandchildren.

**Slack, n.** The disgraceful interval during which a citizen might receive prompt attention.

The director had discovered slack during an inspection. The clerk could process, on average, ten applications per hour, but only nine applicants arrived. This left the clerk unoccupied for approximately one-tenth of the working day—a theft so brazen it appeared on the dashboard in amber.

Management responded with an outreach campaign.

COME EXPERIENCE OUR AVAILABLE CAPACITY, announced the posters.

Arrivals rose to an average of 9.9 per hour. Utilization reached 99 percent. The dashboard turned green. The waiting room acquired a midwife.

An applicant near the radiator began calculating on the back of a rejection letter. Under the office’s advertised queueing model, she explained, the average time from arrival to completed service had increased from one hour to ten.

“But the clerk is busier,” said the director.

“Yes.”

“And we complete more applications.”

“Yes.”

“Then your complaint concerns a success.”

She pointed to the denominator. Ten minus nine was one. Ten minus 9.9 was one-tenth. Taking the reciprocal produced the unwelcome result.

The director summoned the communications team.

**Denominator, n.** That portion of a calculation which has not yet learned to support the organization.

They proposed displaying the reciprocal of waiting time, since a falling number might then be described as streamlined. Legal advised against it. The office settled on measuring Citizen Engagement Hours, which had risen spectacularly without additional staffing.

I objected, then remembered that I had listed the journal’s unfinished manuscripts as “intellectual reserves.” I put my hand down.

The applicant suggested maintaining spare capacity.

“Permanent waste?” asked the director.

“Room for variation.”

He looked wounded. Variation had attended the strategic retreat. It knew the targets.

By afternoon, the queue had established diplomatic relations with the pavement. Management announced a second window. We cheered with the exhausted sincerity of people who had forgotten they were entitled to leave.

The new clerk opened the shutter beneath a sign reading CAPACITY EXPLANATIONS.

“Can you process applications?” I asked.

“No.”

“Can you help us get through faster?”

“No.”

“What can you do?”

“We can explain your delay immediately.”

---

## Mathematical note — genuine result, explicit limits

For an M/M/1 queue with independent Poisson arrivals at rate $\lambda$, independent exponential service times with mean $1/\mu$, one continuously available server, first-come-first-served service, unlimited waiting space, no abandonment, and $\lambda<\mu$, stationary mean time **including service** is

$$
W=\frac{1}{\mu-\lambda}.
$$

Utilization is $\rho=\lambda/\mu$. These are established results under those assumptions; see [MIT OpenCourseWare, *M/M/1 Queue*, 2.854 Introduction to Manufacturing Systems, Fall 2016, pp. 1–2](https://www.ocw.mit.edu/courses/2-854-introduction-to-manufacturing-systems-fall-2016/927056a1af54772a587fd84ad4951e71_MIT2_854F16_Mm1Queue.pdf).

**Toy-model consequences.** With $\mu=10$ applications per hour:

- $\lambda=9$: $\rho=0.9$ and $W=1/(10-9)=1$ hour.
- $\lambda=9.9$: $\rho=0.99$ and $W=1/(10-9.9)=10$ hours.

These are stationary means, not guarantees for an individual applicant or a particular working day.

**Empirical hypothesis.** Whether these assumptions describe any actual institution requires data. No such fit is established here, and a valid model calculation does not validate the social interpretation.

**Invented satirical claims.** The office, its motives, its dialogue, Citizen Engagement Hours, and the waiting-room monarchy are fictional. This is satire, not a peer-reviewed scientific report.

*All bullshit is welcome. Unlabeled bullshit is not.*
