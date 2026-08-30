# IAM Access Control Challenge
-----------------------------
## Objective
- Conduct an access review for a fictional organization using 
 Role-Based Access Control (RBAC)
 and the Principle of Least Privilege.
------------------------------
## Skills Demonstrated 
- Identity and Access Management (IAM) 
- Role-Based Access Control (RBAC)
- Principle of Least Privilege 
- Access Reviews
- Risk Assessment
- Security Documentation
-------------------------------
## Scenario 
- Northstar Solutions has requested an access review of employee permissions to identify
inappropriate access and potential violations of the Principle of Least Privilege.
--------------------------------
## Access Review Process
- I first established departments and roles and defined the systems each role was authorized to access.
I then reviewed each employee's current access against the permissions defined for their role and classified
the results as Approved, Review Required, or Access Deficiency.
For identified access discrepancies, I documented the reason for the finding and recommended whether access
should be reviewed, removed, or granted based on the organization's need. 
Finally, I summarized the identified exceptions in a findings sheet and assigned risk levels to help 
prioritize potential access-control issues.
----------------------------------
## Key Findings
- Of the ten employees reviewed, five matched the access requirements defined for their roles 
and five access discrepancies were identified. 
**4** instances of excessive access,
**1** instance of missing access,
**3** High-risk findings,
**1** Medium-risk finding,
**1** Low-risk finding.
**1** notable high-risk finding involved Mike Rodriguez, a Sales Representative who had access
to the Finance App despite the system not being authorized for his role.
Unauthorized access to the financial system could expose sensitive financial information 
and create opportunities for unauthorized viewing or modification of company data.
-----------------------------------------
## Risk Assessment
- I assigned risk levels based on the sensitivity of the systems involved and the potential impact to the organization.
- **High Risk:** Unauthorized access could expose sensitive information or affect critical identity and financial systems.
- **Medium Risk:** Unauthorized access could expose internal security information but presents less direct business impact based on the assumptions of this project.
- **Low Risk:** Missing access primarily creates an operational or productivity issue rather than the risk of unauthorized information exposure.
-------------------------------------------
## Recommendations
1. **Excessive Access:** Access that exceeds an employee's defined role should be reviewed with the appropriate manager or system owner to verify a legitimate business need. Access that cannot be justified should be removed in accordance with the Principle of Least Privilege.
2. **Missing Access:** Employees who are missing access associated with their assigned role should have the business need verified. If approved, the appropriate access should be granted so the employee can perform their job responsibilities.
3. **Periodic Access Reviews:** Conduct periodic access reviews to confirm that employee permissions remain appropriate for their current roles. Access that is no longer required should be removed to reduce excessive permissions and help prevent access or privilege creep. 
----------------------------------------------
## What I Learned
From completing this project, I learned that Identity and Access Management is more than simply granting or removing access. Effective IAM requires understanding an employee's role and identifying permissions that may create unnecessary risk. I also learned how Role-Based Access Control (RBAC) and the Principle of Least Privilege work together to help organizations manage access. An access discrepancy does not always mean access should immediately be removed or granted; the business need should first be verified with the appropriate manager or system owner. Most importantly, this project helped me understand how access reviews can identify excessive or missing permissions and how those findings can be assessed, documented, and remediated. 
