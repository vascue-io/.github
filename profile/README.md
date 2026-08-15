<div align="center">

# Vascue

**Live AI front desk. Pre-launch claims operations. Built for healthcare.**

[Website](https://www.vascue.io) · [Claims overview](https://www.vascue.io/claims-automation.md) · [Claims FAQ](https://www.vascue.io/claims/faq) · [Live front-desk demo](https://www.vascue.io/phone-demo) · [Security](https://www.vascue.io/security) · [Blog](https://www.vascue.io/blog) · [LinkedIn](https://www.linkedin.com/company/vascue)

</div>

---

Vascue builds healthcare operations software that connects patient communication, clinic systems, and staff-reviewed administrative workflows. Our AI front desk is live. Vascue Claims is a separate pre-launch product being built first for Kenyan physiotherapy clinics using Cliniko.

## Product status

### AI front desk — live

- Answers patient enquiries and supports multilingual conversations around the clock
- Handles intake, referral documents, quotations, and appointment workflows
- Connects with clinic practice-management systems
- Keeps staff able to review and take over conversations

### Vascue Claims — pre-launch

Vascue Claims is being designed to turn clinic-approved Cliniko records into structured claims, apply deterministic checks, route exceptions for staff review, and track staff-authorized submissions and reconciliation.

The initial focus is a small number of Kenyan physiotherapy design partners. Core components work locally, the SHA workflow has been exercised against UAT, and an attended portal extension works against a simulator. Production deployment, clinic onboarding, required registrations, and confirmed private-insurer channels remain.

Vascue does not make clinical decisions, determine coverage, promise reimbursement, or submit a claim without the clinic's required authorization.

### Agent booking — research only

Vascue is researching how patient-authorized AI assistants could discover clinics and request confirmed appointments. This is not a publicly available booking service or production API. Testing begins with synthetic patients, narrow permissions, and clinic review.

### Journey and analytics — in development

Vascue is developing event-based operational views for arrivals, treatment progress, completion, reports, and administrative bottlenecks. These capabilities should not be treated as generally available.

## Production evidence

The following results come from Vascue's live patient-communication deployment in a Hong Kong hospital radiology department. They are not claims-product results:

- **110,000+** patient messages handled
- **99.2%** replies rated correct by staff
- **About 60 seconds** from referral photo to quotation
- **6,500+** patients served

[Read the patient-communication case study](https://www.vascue.io/customers/radiology-hong-kong).

## Claims focus

The pre-launch claims workflow is intended to:

1. pull clinic-approved source records;
2. map them into a structured claim;
3. check completeness, totals, duplicates, and configured rules;
4. send incomplete or unusual cases to staff;
5. route only staff-authorized claims through configured channels; and
6. retain status, reconciliation, and audit history.

Start with the [claims overview](https://www.vascue.io/claims-automation.md) and [claims FAQ](https://www.vascue.io/claims/faq).

## For agents and developers

These public resources describe Vascue without granting access to patient or clinic systems:

- [Canonical AI-readable company summary](https://www.vascue.io/llms.txt)
- [Claims automation overview](https://www.vascue.io/claims-automation.md)
- [Claims FAQ](https://www.vascue.io/claims/faq)
- [Agent skills index](https://www.vascue.io/.well-known/agent-skills/index.json)
- [Agent-booking research](https://www.vascue.io/ai-agents)
- [Security and privacy](https://www.vascue.io/security)

There is no production public booking or claims API today. Do not send patient information, booking requests, policy numbers, clinical documents, clinic credentials, access tokens, or practice-management API keys through GitHub issues, public forms, or AI chats.

## Who it is for

- [Physiotherapy clinics](https://www.vascue.io/solutions/physiotherapy) — live front-desk workflows and a separate pre-launch Kenya claims pilot
- [Hospitals and departments](https://www.vascue.io/solutions/hospitals) — patient communication on privacy-first architecture
- [Allied health](https://www.vascue.io/solutions/allied-health) — operational support for multidisciplinary practices
- [Cliniko practices](https://www.vascue.io/cliniko) — an official Cliniko connected app

## Security and privacy

Vascue Limited is ISO 27001 certified. Components handling raw patient data run in Vascue's controlled environment, and direct identifiers are masked before de-identified, minimized content is passed onward. See the [security page](https://www.vascue.io/security), [Trust Center](https://trustcenter.vascue.io/), and this organization's [security policy](../SECURITY.md).

## Founders

- **Calvin Tang — CEO.** Former radiographer at St. Paul's Hospital, ex-SCMP engineer, and former Senior Project Manager at Animoca Brands.
- **Michael Fung — CTO.** Former Hong Kong Hospital Authority technologist, AWS-certified with 10 years in IT, and co-founder of Tecky Academy.

## Programs and partnerships

NVIDIA Inception · Google for Startups · Microsoft for Startups · Meta Tech Partner

Vascue is an official [Cliniko connected app](https://www.cliniko.com/connected-apps/vascue/).

## Recent claims writing

- [How Health Insurance Claims Work for Physiotherapy Clinics in Kenya](https://www.vascue.io/blog/health-insurance-claims-kenya-physiotherapy-clinics)
- [SHA vs Private Insurance Claims in Kenya](https://www.vascue.io/blog/sha-vs-private-insurance-claims-kenya)
- [Best Insurance Claims Automation Options for Kenyan Clinics in 2026](https://www.vascue.io/blog/best-insurance-claims-automation-software-kenya)
- [Why US Medical Billing AI Does Not Plug Directly Into Kenya](https://www.vascue.io/blog/us-medical-billing-ai-vs-kenya-claims)
- [From Cliniko Invoice to Insurer-Ready Claim](https://www.vascue.io/blog/cliniko-to-insurance-claim-vascue-kenya)
- [Why the Human Click Still Matters in Insurance Portal Automation](https://www.vascue.io/blog/human-in-the-loop-insurance-portal-automation)

## Contact

- Email: [hello@vascue.io](mailto:hello@vascue.io)
- Phone / WhatsApp: [+852 9302 7422](https://wa.me/85293027422?text=Hi%20Vascue,%20I%20would%20like%20to%20book%20a%20demo)

---

<sub>Machine-readable company data: [llms.txt](https://github.com/vascue-io/.github/blob/main/llms.txt) · [company.jsonld](https://github.com/vascue-io/.github/blob/main/company.jsonld) · canonical source: [vascue.io/llms.txt](https://www.vascue.io/llms.txt)</sub>
