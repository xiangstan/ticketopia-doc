# Product/Market Fit (PMF) Framework

**Product**: Ticketopia

## Target Market  

### **Primary Audience** - Our goal

**Small-to-Midsize Businesses (SMBs)** and **IT teams** in:  

- **Higher Education** – Universities, colleges, and schools needing a simple IT/helpdesk solution.  
- **Nonprofits & Local Government** – Budget-conscious orgs needing a modern, cost-effective ticketing system.  
- **IT Service Providers & MSPs** – Managed IT providers needing a **multi-client** ticketing solution.  
- **Tech & SaaS Startups** – Growing companies with lean IT teams managing internal support.  

### **Secondary Audience** - Nice to have

- **Healthcare Organizations** – Clinics, hospitals, and medical offices with IT helpdesk needs.  
- **Cloud & DevOps Teams** – Companies managing infrastructure & DevOps with integrations (e.g., Ansible, Zabbix).  
- **Retail & E-commerce** – Businesses that need an internal helpdesk for IT or logistics teams.  

---

## Core Hypothesis
*We believe small to midsize organizations, particularly higher education entities and non-profits, struggle with managing support tickets due to expensive enterprise solutions (e.g., ServiceNow, Cherwell, Zendesk) or high-maintenance open-source tools (e.g., osTicket). Our product provides an affordable, modern, and easily customizable ticketing system—available as SaaS or self-hosted—integrating seamlessly with third-party tools like Monday.com, Ansible Tower, SnipeIT, and network monitoring systems (Icinga, Nagios, Zabbix).*  

| **Feature** | **Your Product** | **ServiceNow/Cherwell (Enterprise)** | **osTicket/Spiceworks (Open-Source)** |
|--- |--- |--- |--- |
| **Cost** | ✅ Flat-rate (unlimited users) or per 10-user pricing | ❌ Expensive (per-agent pricing, contracts) | ✅ Free, but high maintenance |
| **Self-Hosting Option** | ✅ Discounted for self-hosted customers (own cloud/on-prem) | ❌ Mostly SaaS, self-hosting is costly | ✅ Self-hosted only (manual updates required) |
| **Hosting Options** | ✅ SaaS & self-hosted (cloud/on-prem) | ❌ SaaS (mostly, costly on-prem options) | ❌ Self-hosted only |
| **Customization** | ✅ Simple branding & modular setup | ❌ Complex, requires consulting | ❌ Requires heavy manual rebranding |
| **Third-Party Integrations** | ✅ Deep integrations (Monday.com, Ansible, SnipeIT, Zabbix, etc.) | ❌ Limited or costly integrations | ❌ Few, requires manual setup |
| **UI/UX** |	✅ Modern, lightweight, user-friendly | ⚠️ Feature-rich but complex for SMBs (steep learning curve) | ❌ Outdated, lacks polish |
| **Setup Time** | ✅ 10-minute onboarding | ❌ Weeks or months | ❌ High effort setup & updates |

### Main Value Propositions

✔ Flat-rate unlimited users (Huge savings vs. per-agent pricing)  
✔ Per 10-user pricing option (Lower entry cost for SMBs)  
✔ Discount for self-hosted customers (Lower cost for AWS/Azure/on-prem)  
✔ Flexible deployment (SaaS or self-hosted)  
✔ Modern UI/UX (Fast, easy-to-use interface)  
✔ Deep integrations (Reduce IT workload by connecting to existing tools)  
✔ Rapid setup (10-minute onboarding vs. weeks/months for competitors)  
✔ Embedded Knowledge Base (Less reliance on external tools like Confluence)  

---

## Target Customer Profile

<table>
  <tr>
    <th><strong>Trait</strong></th>
    <th><strong>Details</strong></th>
  </tr>
  <tr>
    <td valign="top"><strong>Industry</strong></td>
    <td valign="top">IT-managed services, higher education, non-profits, healthcare, local government, SMBs with IT helpdesk needs</td>
  </tr>
  <tr>
    <td valign="top"><strong>Company Size</strong></td>
    <td valign="top">10–500 employees (SMBs, universities, nonprofits, and IT teams in larger orgs)</td>
  </tr>
  <tr>
    <td valign="top"><strong>Pain Points</strong></td>
    <td valign="top">
      - High ticket volume, manual tracking in emails/spreadsheets<br>
      - No dedicated IT admin or limited IT staff<br>
      - Open-source options require heavy customization & maintenance<br>
      - Enterprise solutions (ServiceNow, Cherwell) are too complex and expensive
    </td>
  </tr>
  <tr>
    <td valign="top"><strong>Current Solutions</strong></td>
    <td valign="top">
      - Email, spreadsheets, Slack/Teams messages<br>
      - osTicket, Spiceworks (difficult to customize)<br>
      - ServiceNow, Zendesk, Cherwell (costly & overkill for SMBs)
    </td>
  </tr>
  <tr>
    <td valign="top"><strong>Tech Stack Used</strong></td>
    <td valign="top">
      - Likely using <strong>Microsoft 365</strong>, Google Workspace, Slack, Teams<br>
      - May already use <strong>Snipe-IT, Ansible Tower, Zabbix, Nagios, SolarWinds</strong> for IT operations
    </td>
  </tr>
  <tr>
    <td valign="top"><strong>Budget Concerns</strong></td>
    <td valign="top">
      - Limited IT budget; prefers <strong>flat-rate or affordable pricing</strong><br>
      - Wants predictable costs (not per-agent pricing like Zendesk)
    </td>
  </tr>
  <tr>
    <td valign="top"><strong>Key Decision Makers</strong></td>
    <td valign="top">IT managers, sysadmins, CTOs, operations managers, office managers at SMBs and non-profits</td>
  </tr>
  <tr>
    <td valign="top"><strong>Hosting Preferences</strong></td>
    <td valign="top">
      - Some prefer <strong>fully managed SaaS</strong> for convenience<br>
      - Others need <strong>self-hosted/on-prem</strong> for compliance or cost reasons
    </td>
  </tr>
</table>

---

## Key Metrics to Track PMF

| **Metric** | **Target** | **Tool** |
|--- |--- |--- |
| **Retention (30-day)** | >30% | Mixpanel/Amplitude |
| **% "Very disappointed"** | >40% | SurveyMonkey/Typeform |
| **Trial → Paid Conversion** | >10% | Stripe/Dashboard |
| **Net Promoter Score (NPS)** | >30 | Delighted |
| **Customer Satisfaction (CSAT)**| >80% | SurveyMonkey/Qualtrics |
| **Customer Lifetime Value (CLTV)** | >$X per customer| Stripe/HubSpot |
| **User Engagement (DAU/WAU/MAU)** | >X daily/weekly/monthly active users | Mixpanel/Amplitude |
| **Churn Rate** | <5% | Stripe/Amplitude |
| **Feature Adoption Rate** | >X% of users using a feature | Mixpanel/Amplitude |
| **Customer Acquisition Cost (CAC)** | <$X per customer | Stripe/HubSpot |

*From Sean Ellis Test: "How would you feel if you couldn’t use this product anymore?"*

---

## MVP Features (Prioritized)

### 1. **Must-Have**  
   - **Multi-channel ticket creation**: Allow users to create tickets via email and web forms.  
   - **Basic assignment & status tracking**: Enable assigning tickets to team members and tracking their status (e.g., Open, In Progress, Closed).  
   - **Slack/Teams/Discord notifications**: Integrate with Slack, Microsoft Teams and Discord to send ticket updates and notifications for better collaboration.  
   - **Time tracking for each ticket**: Lets IT staff track the time spent on each ticket, improving visibility into resource allocation, helping with billing, and providing insights into team productivity.

### 2. **Nice-to-Have**  
   - **Reporting dashboard**: Provide a simple, visual dashboard to track ticket volume, response times, and resolutions.  
   - **API for custom integrations**: Enable easy integration with third-party tools (e.g., Monday.com, Ansible Tower, SnipeIT) via a well-documented API.  
   - **Migration tool for osTicket/Spiceworks users**: Offer a migration tool to easily transfer ticket data from osTicket or Spiceworks into the new system to facilitate a smooth transition.  

---

## Competitive Differentiation  

| **Competitor**  | **Weakness**                                    | **Our Edge**                                    |
|----------------|------------------------------------------------|------------------------------------------------|
| **ServiceNow**  | Expensive, overkill for SMBs, complex setup   | Affordable, no IT team needed, quick deployment |
| **Zendesk**     | Per-agent pricing, high total cost            | Flat monthly rate, unlimited IT user option    |
| **Freshdesk**   | Complex setup, hidden costs                   | 10-minute onboarding, transparent pricing      |
| **osTicket**    | Outdated UI, lacks integrations, manual updates | Modern UX, Slack/Teams/Discord notifications, built-in integrations |
| **Spiceworks**  | Ad-supported, limited cloud support           | No ads, full cloud/self-hosted flexibility     |
| **Cherwell**    | Outdated UX, long implementation time         | Modern UI, rapid deployment, lower cost       |

### Key Differentiators:
✔ **Flat-rate pricing** (no per-agent costs)  
✔ **Flexible hosting** (SaaS or self-hosted)  
✔ **Modern UX/UI** (intuitive and easy to use)  
✔ **Multi-channel notifications** (Slack, Teams, Discord)  
✔ **Built-in time tracking** (track IT staff effort per ticket)  
✔ **Seamless third-party integrations** (Monday.com, Ansible, SnipeIT, Zabbix, etc.)  
✔ **Fast setup & onboarding** (up and running in minutes)  

---

## Validation Plan  

### Surveys  

- **Template Questions:**  
  > *"What’s your biggest struggle with [current tool]?"*  
  > *"Would you pay $[X]/month for [key benefit]?"*  
  > *"How do you currently manage IT tickets and knowledge base content?"*  

### Customer Interviews  

- **Key Questions:**  
  - *"Walk me through your ticket management process. What works? What’s frustrating?"*  
  - *"What would make you switch tools today?"*  
  - *"How do you track time spent on IT tickets?"*  
  - *"What integrations would make your workflow easier?"*  

### Landing Page Test  

- **A/B Test Copy:**  
  - *"The ticketing system for SMBs who hate enterprise software."*  
  - *"Slack/Teams/Discord-friendly support—no IT degree required."*  
  - *"Ditch spreadsheets. Track IT work effortlessly."*  

### Survey Questions for Open-Source Users  

- *"What’s the biggest hassle of using osTicket/Spiceworks?"*  
- *"Would you pay to avoid [specific pain]?"*  
- *"If you could improve one thing about your current system, what would it be?"*  
- *"Have you tried modifying your current system? If so, what challenges did you face?"*  

### Landing Page Messaging  

**A/B Test Headlines:**  
- *"Ditch osTicket’s headaches—try our cloud alternative."*  
- *"Spiceworks without the ads or network scans."*  
- *"A ticketing system that works without IT micromanagement."*  
- *"Track tickets, manage time, and integrate seamlessly."*  

---

## Risks & Next Steps

| **Risk** | **Mitigation Strategy** |
|--- |--- |
| Low willingness to pay  | Test pricing tiers early; compare against alternatives |
| Low retention | Improve onboarding with tutorials & guided setup |
| Feature creep | Stick to MVP; prioritize via customer feedback & voting |
| Migration friction | Build easy import tools for osTicket/Spiceworks users |
| Migration friction (Enterprise) | Develop **data mapping guides** & offer **import scripts** for Cherwell |
| Market awareness | Use targeted content & partnerships for outreach |

**Next Steps**:  

- [ ] Conduct **10+ customer interviews** by [date].  
- [ ] Launch **MVP** with essential features.  
- [ ] A/B test **pricing models** with real users.  
- [ ] Gather feedback from **open-source users** on migration pain points.  
- [ ] Interview **ex-Cherwell users** to identify critical migration needs.  
- [ ] Develop **data import guides** and assess automation potential.  
- [ ] Run **landing page test** to gauge interest & conversions.  