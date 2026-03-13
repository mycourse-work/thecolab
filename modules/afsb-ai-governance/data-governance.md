# Data Governance Essentials

Data governance sounds technical, but it boils down to four questions: What data do you have? Where is it? Who can access it? How is it protected? If you can answer those questions, you're doing data governance — even if you never use the term.

When AI enters the picture, data governance becomes more important because AI tools are hungry for data. They process it, learn from it, and sometimes store it in places you didn't expect. This lesson gives you a practical framework for keeping your data under control.

## Types of Data in Your Business

Before you can govern your data, you need to know what you've got. Most small businesses handle four broad categories:

| Data Type | Examples | Sensitivity |
|-----------|----------|-------------|
| **Customer data** | Names, emails, phone numbers, purchase history, communications | High |
| **Financial data** | Bank details, invoices, tax records, payroll | High |
| **Employee data** | Personal details, performance records, health info, contracts | High |
| **Business intelligence** | Sales trends, marketing analytics, operational metrics, strategies | Medium |

You probably also have **public data** — things on your website, published marketing content, social media posts. This is low sensitivity and generally fine to use with AI tools.

## Data Classification: A Simple System

Data classification is about deciding what level of protection different data needs. Enterprise companies have complex classification schemes. You need four levels:

| Classification | What It Includes | AI Rule |
|---------------|-----------------|---------|
| **Public** | Website content, published marketing, social media | Safe to use with any AI tool |
| **Internal** | Meeting notes, internal comms, process docs, general business info | OK with approved business-tier AI tools |
| **Confidential** | Customer personal data, financial records, employee details, contracts | Business-tier AI only, with caution — anonymise where possible |
| **Restricted** | Passwords, health information, bank account numbers, legal matters, trade secrets | Never put into AI tools |

> **Rule of thumb:** If you'd be uncomfortable seeing the data on the front page of the NZ Herald, it's at least Confidential. If it could cause real harm to someone, it's Restricted.

Print this table out or save it somewhere visible. When someone on your team is about to paste data into an AI tool, this gives them a quick reference for whether they should.

## What NOT to Put Into AI Tools

This list should be in your AI policy and understood by everyone on your team:

- **Passwords and access credentials** — ever, for any reason
- **Health information** — staff or customer medical details, ACC claims
- **Unredacted financial details** — bank account numbers, credit card numbers, IRD numbers
- **Confidential contracts** — commercial terms, legal agreements (unless using an enterprise-grade legal AI with appropriate protections)
- **Trade secrets** — proprietary processes, formulas, competitive strategies
- **Personal information that isn't necessary** — if you're asking AI to draft a customer email, you need their name but not their home address

> **Warning:** Even with business-tier AI tools, apply the principle of minimum necessary data. Only provide the AI with the specific information it needs for the task. Remove everything else before submitting.

## AWS NZ Region: Solving Data Sovereignty

One of the biggest data governance concerns for NZ businesses has been where their data goes. Most AI tools process data on US servers, raising questions under the Privacy Act's cross-border transfer rules (IPP 12).

That's changing. **AWS launched its NZ region in 2025** with a NZ$7.5 billion investment. This means businesses can now choose to process and store data within New Zealand for services built on AWS infrastructure.

What this means practically:

- Some AI tools and cloud services can now offer NZ-based data processing.
- If data sovereignty is a concern for your business or your customers, look for tools that use the AWS NZ region.
- This doesn't automatically make every AI tool NZ-hosted — the tool provider has to specifically choose to use the NZ region.
- For many small businesses, using business-tier accounts with strong data protection agreements on US-based services is still perfectly acceptable under the Privacy Act.

Data sovereignty matters most when you're handling sensitive personal information, government contracts, or serving customers who specifically require NZ-based data storage.

## Business-Tier Accounts: Non-Negotiable

This point has come up in earlier modules, and it bears repeating here because it's a core data governance decision.

**Free-tier AI tools typically use your inputs to train their models.** That means your customer data, financial details, and business information could become part of the AI's training data — accessible in some form to other users.

**Business-tier accounts typically don't.** They come with data processing agreements that specify your data won't be used for training, will be handled according to privacy requirements, and will be deleted according to agreed schedules.

| Feature | Free Tier | Business Tier |
|---------|-----------|---------------|
| Data used for training | Usually yes | Usually no |
| Data processing agreement | No | Yes |
| Admin controls | No | Yes |
| Audit logs | No | Often yes |
| Multi-factor authentication | Sometimes | Yes |
| Cost | Free | $17-30/user/month |

For any AI tool that touches business data — even Internal-classified data — use a business-tier account. The cost is small compared to the risk.

## Practical Security Measures

Data governance isn't just about policy — it's about practical security. Here are the essentials:

| Measure | What to Do |
|---------|-----------|
| **MFA** | Turn on multi-factor authentication for every AI tool and business account. This is the single most effective security step. |
| **Access controls** | Limit AI tool access by role. Your marketing person doesn't need the financial analysis tool. |
| **Strong passwords** | Use a password manager (1Password, Bitwarden). No shared passwords. No sticky notes. |
| **Regular reviews** | Revoke access immediately when someone leaves. Review access rights at least quarterly. |
| **Secure devices** | Only access AI tools from devices with up-to-date OS, endpoint protection, and encrypted storage. |

## Data Retention: How Long to Keep AI Logs

How long should you keep records of AI interactions? There's no single NZ law that specifies a retention period for AI logs, but here are practical guidelines:

| Record Type | Suggested Retention | Why |
|-------------|-------------------|-----|
| AI register | Ongoing (update regularly) | You always need to know your current tools |
| Incident records | 7 years minimum | Aligns with general business record-keeping and limitation periods |
| Decision logs | 3-7 years | Depends on the decision type — financial decisions follow tax record rules |
| Routine AI interaction logs | 12 months | Long enough to investigate issues, not so long you're storing unnecessary data |
| Customer-affecting AI outputs | Match your general record retention policy | Consistency with your other business records |

> **Tip:** Check whether your AI tools automatically retain conversation history and for how long. Some tools store everything indefinitely. Others delete after 30 days. Know what your tools do and whether that aligns with your needs.

## Bringing It All Together

Here's a practical data governance checklist for your business:

- [ ] Classified your data into Public, Internal, Confidential, and Restricted categories
- [ ] Created a "do not share with AI" list and communicated it to your team
- [ ] Using business-tier accounts for all AI tools that touch business data
- [ ] MFA enabled on all AI tools and business accounts
- [ ] Access controls in place — people only access what they need
- [ ] Password manager in use, no shared passwords
- [ ] Review schedule set for access rights and AI tool terms
- [ ] Data retention approach documented
- [ ] Offboarding process includes revoking AI tool access

## Key Takeaways

- Data governance means knowing what data you have, where it is, who can access it, and how it's protected.
- Use a simple four-level classification: Public, Internal, Confidential, Restricted. Never put Restricted data into AI tools.
- Business-tier AI accounts are non-negotiable for any tool that touches business data — free tiers typically use your data for training.
- The AWS NZ Region (2025) means NZ-based data processing is now possible for some tools, helping with data sovereignty concerns.
- MFA, access controls, and regular access reviews are your core security measures.
- Set clear data retention periods and know how long your AI tools store your interactions.
