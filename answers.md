### Task 1: Data Quality, Security & Onboarding Review

1. **Security & Data Quality Anomalies:**  
a, Test account should not contain real user name. (Jane Smith - Test Account) In order to avoid misunderstandings, it should be more clrearer that there's no real user behind the account. It has been created only for testing reasons.
b, Invalid creation date. name: "billing-system" owner: "Finance IT" creation_date: "2025-02-30"  This cannot be true.
c, Providing access to "payment-gateway" for external user can casue a security risk. As sensitive info such as finance related topics should not be handled by a third party.

2. **Onboarding Decisions:**
* *New User A:* Mark Kovacs (`mark.kovacs@aldi-sued.com`), Role: Developer, Repo: `payment-gateway` Email is valid. Required access matches to the developer level. PROCEED
* *New User B:* Stefan Müller (`stefan.mueller@adli-seud.com`), Role: Maintainer, Repos: `auth-service`, `core-api` Invalid email. It can be a false account, which has been created for a possible cyberattack. REJECT
* *New User C:* Anna Schmidt (`anna.schmidt@aldi-sued.com`), Role: Owner, Repo: `billing-system` Email is valid, but the user would require the Owner role to a sensitve pool of data. Approval would be needed in this case. HOLD FOR APPROVAL
* *New User D:* Thomas Weber (`thomas.weber@aldi-sued.com`), Role: Developer, Repo: `core-api` Email is valid. Required access matches to the developer level. PROCEED
* *New User E:* Kevin Smith (`kevin.smith@aldi-sued.com`), Role: System-Admin-All, Repo: `frontend-ui` Email is valid. User requires access to a basic frontend user platform with a System Admin role. The Principle of Least Privilege is not applied here as the most highest role is combined with basic access request. REJECT

### Task 2: Operational Support & License Management

1. **First Steps & Troubleshooting:**
a, Visit Gitlab support page/contact the support agents whether  there is a notifictaion stating that it is a global issue and they are working on it now or not.
b, If only our company is affected, then i would collect more details about the issue, when it has started; other functions, accesses are working fine or not, estimate the possible businsess impact and contact again Gitlab support to report emergency/major issue and provide a temporary solution.
c, I would also check how many colleagues are out of office or on longer leave. In this case if we cannot provide quick solutions for this problem, those licences can be used temporarily by the currently working developers.

2. **Prioritization:**
I would prioritize Developers with Active account such as Emma Watson, John Doe or Bruce Wayne.
Licences can be revoked immediately: a, Jane Smith - Test Account b, David Miller - inactive account c, Clark Kent - On leave d, Jane Doe - reporter ( does not require coding tools for her tasks)

3. **Escalation & Help:**
I would contact the IT Manger with this problem providing the following details: a, business impact ( 40+ devs cannot work, it can cause delivery delays-->possible financial impact ) b, information/experiences i have collected from the Github support and from our developers c, possible work arounds how we could handle the situation temporarily

4. **User Communication:**
Hi All,
We are currently experiencing an unexpected license problem with our AI code assistant plugin, causing the following error: "License expired or quota exceeded".
We are actively working on the solution to unblock everyone as quickly as possible. Until then, please focus on non-coding duties, such as:
• Reading training materials
• Knowledge sharing
• Documentation tasks
Feel free to contact me with questions. Thank you for your patience!


