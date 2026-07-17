# My Notes — Mercy Igba

\---

## Key Concepts I Learned

<!-- Write the main ideas covered in today's session -->



Last class I gained a better understanding of how organizations control and secure access to their resources using Microsoft technologies.

* How access decisions are made by assessing factors such as who is signing in, the type of device being used, where the request is coming from, the application being accessed, and the level of risk involved. Depending on these conditions, access may be approved, denied, or require an extra verification step. This is call Conditional Access Policy
* Privilege Identity Management manages administrative permissions more securely by granting elevated access only when it is needed, rather than assigning it permanently. This approach helps reduce unnecessary security exposure.
* API Plugins enable Microsoft 365 Copilot to interact with external business systems through connectors that allow it to exchange information with other applications in a secure manner.
* I compared the two supported approaches for securing these connections. The API Key Authentication relies on a single secret shared between systems, while OAuth 2.0 Authentication verifies each individual user through Microsoft Entra ID and issues temporary tokens that provide secure, user-specific access.

\---

## Lab / Hands-On Work

<!-- Describe what you did in the lab. Include steps, commands, or screenshots descriptions -->

### What I did

* I accessed the Microsoft Entra admin center and opened the Conditional Access section under Policies. I created a new policy, assigned a name, and targeted a designated test account. I then configured the access requirements to enforce multifactor authentication before granting access. After confirming the configuration, I enabled the policy for the selected user. I also followed the mentor's demonstration in some ways
* For Privileged Identity Management (PIM), I followed the mentor's demonstration to understand the configuration process



### What happened / Result

The conditional access configuration was successful

### Challenges I faced

It took me some time  to understand how conditional Access works before I was confident enough to enable the policy successfully.

\---

## My Takeaways

<!-- What was most valuable to you personally from this session? -->



* Secure access should be based on multiple security checks, not just passwords.
* I learned that Just-in-Time access helps reduce security risks by limiting permanent admin privileges.

The importance of patience in troubleshooting. When an action doesn't work as expected, the best approach is to examine each step carefully until the source of the issue is identified.



Questions I Still Have

<!-- Anything you want to follow up on or ask the mentor -->

* 
* 

\---

## Resources I Found Useful

<!-- Any links, docs, or Microsoft Learn modules you found helpful -->

* Microsoft Cloud \& AI Security Bootcamp 2026 (Microsoft Naija Security User Group) Session Recording (Internal Resource)

\---

*Submitted by: Mercy Igba · Mercyigba*

