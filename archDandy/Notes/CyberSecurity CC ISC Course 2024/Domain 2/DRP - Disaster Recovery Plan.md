#section3 #cybersecurity 

Our **DRP (Disaster Recovery Plan)** should answer at least three basic questions:
	- What is the objective and purpose?
	- Who will be the people or teams who will be responsible in case any disruptions happen?
	- What will these people do (our procedures) when the disaster hits?

DRP has a life cycle of **Mitigation, Preparation, Response and Recovery.**
**Mitigation:** Reduce the Impact, and likeliness of a disaster.
	- Pre-disaster.
	- Mitigation.
	- Implementations.

**Preparation:** Build programs, procedures and tools for our response.
	- Education.
	- Plans.
	- Processes & Training.

[[Simulated Tests]]

**Response:** How we react in a disaster, following the procedures.

**Recovery:** Reestablish basic functionality and get back to full production.

![[Pasted image 20241203183037.png]]

## **DRP - Disaster Recovery Plan. 
PART 2

**BIA (BUSINESS IMPACT ANALYSIS)** 
Identifies critical and non-critical organizations systems, functions and activities.
	- **RPO (RECOVERY POINT OBJECTIVE):** The acceptable amount of data that can not be recovered.
	- **MTD (MAXIMUM TOLERABLE DOWNTIME)**: The time to rebuild the system and configure it for reinsertion into production must be less than or equal to our MTD. 
		- **RTO (RECOVERY TIME OBJECTIVE) (hardware):** The amount of time to restore the system (hardware).
		- **WRT (WORK RECOVERY TIME) (software):** How much time is required to configure a recovered system.
			**MTD >= RTO + WRT**
	- **MTBF (MEAN TIME BETWEEN FAILURES):** How long a new or repaired system.
	- **MTTR (MEAN TIME TO REPAIR):** How long it will take to recover a failed system.
	- **MOR (MINIMUM OPERATING REQUIREMENTS):** The minimum environmental and connectivity requirements for our critical systems to function

## **DRP - Disaster Recovery Plan. 
PART 3**

**RECOVERY STRATEGIES:**
From our MTD we can determine our approach to how we handle disasters and the safeguards we put in place to mitigate or recover from them.
	- **REDUNDANT SITE:** Complete identical site to our production, receives a real time copy of our data.
	- **HOT SITE:** Similar to the redundant site, but only houses critical applications and systems.
	- **WARM SITE:** Similar to the hot site, but not with real or near-real time data.
	- **COLD SITE:** A smaller but full data center, with redundant UPS's, HVAC's, ISP's generators,...
	- **RECIPROCAL AGREEMENT SITE:** Your organization has a contract with another organization that they will give you space in their data center in a disaster event and vice versa.
	- **Subscription/Cloud Site:** We pay someone else to have a minimal or full replica of our production environment up and running within a certain number of hours (SLA).
	- **MOBILE SITE:** Basically, a data center on wheels, often a container or trailer that can be moved wherever by a truck.

## DRP - Disaster Recovery Plan.
**PART 4**

Once we have had and recovered from a disruption or we have done our fail over test we do a lessons learned.

**LESSONS LEARNED:** 
This phase is often overlooked, we removed the problem, we have implemented new controls and safeguards.
	**!!!IMPORTANT!!!** We only use our **BCP/DRP's** when our other countermeasures have failed. This makes the plans even more important. 
	**REMEMBER 72% OF BUSINESS WITH MAJOR DATA LOSS CLOSED.**

When we make and maintain the plans there are some common pitfalls we want to avoid:
	- Lack of Senior leadership support.
	- Too narrow scope.
	- Not keeping the **BCP/DRP** plans up to date.

The plans needs to be continually updated.
	- Plans should be reviewed and updated at least every 12 months.
	- When we update the plans, older copies are retrieved and destroyed, and current versions are distributed.
