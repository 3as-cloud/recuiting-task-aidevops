# Alpha Edge Booking Guideline

This booking guideline ensures that engineers know how to track their efforts correctly in projects.

---

## General Guidelines

- **Time Tracking**: Every hour should be booked in 15-minute increments (quarter-hour detail).
- **Description Format**: Use the following format for descriptions:

```
[ticket number]: description
```

- **Booking Containers**: There are two booking containers for the customer:
- **Alpha Edge Ops FP** (Fixed Price)
- **Alpha Edge Change T&M** (Time & Materials)

---

## Alpha Edge Ops FP (Fixed Price)

### Tasks to Book Under This Container:

**Alpha Edge JF Weekly**
- Attend the Alpha Edge Jour Fixe Weekly meetings.

**Kubernetes Upgrades**
- Perform updates to Kubernetes clusters, including updates to EKS (Elastic Kubernetes Service) add-ons.

**Infrastructure Troubleshooting**
- Handle issues related to the infrastructure.
  - *Note*: If the root cause is application software, book the task under **Alpha Edge Change T&M**.

**Application Troubleshooting**
- Address problems caused by our team or general infrastructure issues affecting applications.

**Internal Team Meetings**
- Participate in internal engineering team meetings (e.g., syncing about current tasks).

**Knowledge Transfer**
- Share expertise and knowledge among engineering team members.

**Task Grooming and Refinement**
- Groom and refine tasks that are part of the Fixed Price (FP) container.

**User Offboarding**
- Manage the removal of users and deactivation of accounts as needed.

**Monitoring and Alerting Improvements**
- Implement changes and enhancements to monitoring and alerting systems.

**Onboarding Activities**
- Conduct tasks related to the internal onboarding of new team members.

---

## Alpha Edge Change T&M (Time & Materials)

### Tasks to Book Under This Container:

**Regular Meetings**
- Attend meetings besides the Jour Fixe, such as:
  - Alpha Edge Standup
  - Alpha Edge CI/CD sessions
  - Alpha Edge Team Retrospective

**Customer-Requested Improvements and Changes**
- Implement improvements and changes requested by customers or other development teams.
- Activities include creating concepts, performing code reviews, attending meetings, and drafting documentation.

**Upgrades to Additional Components**
- Upgrade components not previously listed (e.g., ArgoCD).

**CI/CD Improvements and Fixes**
- Work on Continuous Integration/Continuous Delivery improvements and fixes, provided the issues were not caused by our team.

**Task Grooming and Refinement**
- Groom and refine tickets and tasks that are part of the Time & Materials (T&M) container (change management).

---

## Notes for Starters

- **Booking Accuracy**: Always ensure you're booking your time under the correct container based on the task.
- **Seek Clarification**: If unsure where a task should be booked, consult with your team lead or a senior engineer.
- **Detailed Descriptions**: Include clear and concise descriptions with the relevant ticket number for traceability.
- **Meeting Participation**: Be aware of which meetings are billable under Fixed Price and which are under Time & Materials.

---

## Examples

- **Fixed Price Booking Example**:
```
[AE-102]: Performed Kubernetes upgrade on the staging environment.
```

- **Time & Materials Booking Example**:
```
[AE-205]: Attended Alpha Edge CI/CD session to discuss pipeline enhancements.
```

---

If you have any questions about this guideline or need further clarification, please reach out to your team lead.

