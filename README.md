# IT Support Ticketing Simulation

A practical IT support lab demonstrating first-line service desk ticket handling using Spiceworks Cloud Help Desk.

The project simulated realistic user support incidents and combined technical troubleshooting with ticket logging, prioritisation, internal documentation, user communication and ticket-status management.

The technical troubleshooting actions documented in the tickets were performed in a controlled lab environment, while Spiceworks was used to record and manage the incidents as a support technician would on a service desk.

## Lab Objectives

The objectives of this project were to practise:

- Logging IT support incidents
- Reviewing user-reported issues
- Assessing impact and urgency
- Assigning appropriate ticket priorities
- Performing first-line troubleshooting
- Recording internal technician notes
- Writing clear user-facing responses
- Updating ticket statuses
- Managing tickets through a support lifecycle
- Requesting user confirmation where appropriate
- Documenting troubleshooting and resolution steps
- Developing practical first-line service desk skills

## Environment

- Spiceworks Cloud Help Desk
- Windows lab environment
- Active Directory lab environment
- Simulated end-user support requests
- Internal technician notes
- Public user responses
- Ticket priority management
- Ticket status management

---

## Ticket Handling Workflow

The support process followed a structured ticket lifecycle:

1. User reports an IT issue
2. Support request is logged in Spiceworks
3. Impact and urgency are assessed
4. An appropriate priority is assigned
5. Initial troubleshooting is performed
6. Technical findings are documented using internal notes
7. The user is updated through a public response
8. Ticket status is changed where appropriate
9. User confirmation is requested if required
10. The ticket is closed once the issue is considered resolved

The lab used different ticket priorities and statuses to practise organising and managing multiple support requests.

---

## Ticket Overview

The Spiceworks ticket queue contained several support incidents with different priorities and statuses.

![Spiceworks ticket overview](screenshots/Tickets.png)

This provided practical experience reviewing multiple support requests and identifying which incidents should receive attention first.

---

# Ticket 1: VPN Not Connecting

## User Issue

A simulated user reported that they were unable to connect to the organisation's VPN.

The incident was treated as **High Priority** because loss of VPN connectivity could prevent a remote user from accessing systems required for work.

## Troubleshooting

The VPN issue was investigated in the lab environment.

Troubleshooting included:

- Reviewing the reported VPN connectivity problem
- Checking VPN-related information and logs
- Identifying a likely client configuration issue
- Providing an updated VPN profile/configuration for the user to test

## Internal Technician Note

An internal note was added in Spiceworks to record the investigation and suspected cause.

![VPN internal technician note](screenshots/Bob_Internal_note.png)

Internal notes were used to record technical information that would be useful to another support technician without exposing unnecessary troubleshooting detail to the user.

## User Communication

A separate public response was created to update the user.

The user was informed that an updated VPN profile had been provided and was asked to test the connection again.

![VPN user response and waiting status](screenshots/Bob_waiting.png)

The ticket was moved to a **Waiting** state while confirmation from the user was pending.

## Ticket Outcome

- **Priority:** High
- **Issue:** VPN not connecting
- **Investigation:** VPN connectivity and client configuration reviewed
- **Resolution action:** Updated VPN profile/configuration provided
- **User action:** Test VPN connectivity again
- **Status:** Waiting for user response

## Support Skills Demonstrated

This scenario demonstrated:

- Prioritising a potentially business-impacting incident
- VPN troubleshooting
- Reviewing technical information and logs
- Identifying a likely configuration issue
- Recording technician-only investigation notes
- Communicating next steps clearly to a user
- Using a Waiting status when user confirmation is required

---

# Ticket 2: Password Reset

## User Issue

A simulated user required assistance accessing their account.

The support request required a password reset and was assigned **Medium Priority**.

## Troubleshooting and Resolution

The password-reset process was performed using the Active Directory lab environment.

The support workflow included:

- Reviewing the account-access request
- Following a simulated user identity-verification step
- Locating the user account in Active Directory
- Resetting the user's password
- Recording the completed action in the ticket
- Informing the user that the account-access action had been completed

## Internal Technician Note

The internal note documented the account-access investigation and password-reset action.

![Password reset internal note](screenshots/Internal_note.png)

The technical password-reset task was performed in the Active Directory lab environment, while Spiceworks was used to document the service desk workflow.

## User Communication

A public response was added to inform the user that the password-reset action had been completed and that they could proceed with the next login step.

![Password reset public response](screenshots/Public_response.png)

The ticket was then moved to a closed state.

## Ticket Outcome

- **Priority:** Medium
- **Issue:** Account access / password reset
- **Technical action:** Password reset performed in Active Directory
- **Documentation:** Internal technician note recorded
- **User communication:** User informed of the completed action
- **Status:** Closed

## Support Skills Demonstrated

This scenario demonstrated:

- Handling an account-access support request
- Active Directory user-account support
- Password-reset workflow
- Identity and access management fundamentals
- Documenting completed technical actions
- Separating internal technical notes from user communication
- Progressing a support ticket through to closure

---

# Ticket 3: Outlook Search Not Working

## User Issue

A simulated user reported that Outlook search was not functioning correctly.

The incident was assigned **Low Priority** because the user could still access email, but part of the application's functionality was unavailable.

## Troubleshooting

The Outlook issue was investigated as part of the lab exercise.

Troubleshooting included:

- Reviewing the reported Outlook search problem
- Investigating Outlook indexing
- Rebuilding the Outlook search index
- Re-synchronising the mailbox
- Asking the user to test Outlook search again after the troubleshooting steps

## Internal Technician Note

The internal note documented the Outlook investigation and the technical steps that had been performed.

![Outlook internal technician note](screenshots/David_Internal_note.png)

## User Communication

A public response was created asking the user to test Outlook search again after the repair steps.

![Outlook public response](screenshots/David_public_response.png)

This demonstrated the importance of asking the user to verify functionality rather than assuming that an incident is resolved immediately after a technical change.

## Ticket Outcome

- **Priority:** Low
- **Issue:** Outlook search not working
- **Technical actions:** Search index rebuilt and mailbox re-synchronised
- **User action:** Test Outlook search again
- **Status:** Closed within the lab workflow

## Support Skills Demonstrated

This scenario demonstrated:

- Microsoft Outlook troubleshooting
- Investigating application functionality issues
- Outlook indexing troubleshooting
- Mailbox synchronisation troubleshooting
- Recording technical actions clearly
- Communicating testing instructions to a user
- Requesting verification after a fix
- Documenting final ticket status

---

## Internal Notes vs Public Responses

One of the main objectives of this project was to practise the difference between technician documentation and user communication.

### Internal Notes

Internal notes were used to record information such as:

- Reported symptoms
- Suspected causes
- Troubleshooting activity
- Technical findings
- Resolution actions
- Information useful to another technician

These notes are intended for support staff rather than end users.

### Public Responses

Public responses were written using clearer user-facing language.

They were used to:

- Explain what action had been taken
- Tell the user what to do next
- Request testing or confirmation
- Provide progress updates
- Confirm when an issue was ready for closure

This distinction helps maintain useful technical records while keeping communication understandable for non-technical users.

---

## Ticket Prioritisation

The lab used three priority levels to practise assessing incidents according to impact and urgency.

### High Priority

The VPN connectivity incident was treated as High Priority because the problem could prevent a remote user from accessing systems required for work.

### Medium Priority

The individual password-reset request was treated as Medium Priority because the affected user required support to regain account access.

### Low Priority

The Outlook Search issue was treated as Low Priority because email remained available and only part of the application's functionality was affected.

The purpose was to practise evaluating incidents rather than treating every support request as equally critical.

---

## Ticket Status Management

Different ticket statuses were used to represent the support lifecycle.

### Open

The issue has been logged and requires investigation or action.

### Waiting

Support has taken an action and requires information, testing or confirmation from the user before progressing further.

### Closed

The support process has been completed and no further action is currently required.

Using clear ticket statuses helps support technicians understand which incidents require attention and which are waiting for another party.

---

## Service Desk Workflow Demonstrated

The overall support workflow practised in this project was:

1. Review the user's reported problem
2. Log the incident in Spiceworks
3. Assess impact and urgency
4. Assign an appropriate priority
5. Perform first-line troubleshooting
6. Record technical findings in internal notes
7. Apply an appropriate resolution or next action
8. Communicate clearly with the user
9. Update the ticket status
10. Request user verification where required
11. Close the ticket when the issue is resolved

---

## Skills Demonstrated

- Spiceworks Cloud Help Desk
- IT service desk workflow
- First-line IT support
- Ticket logging
- Incident categorisation
- Ticket prioritisation
- Impact and urgency assessment
- Internal technician documentation
- User-facing support communication
- Ticket status management
- Incident lifecycle management
- Managing Open, Waiting and Closed tickets
- First-line troubleshooting
- VPN troubleshooting
- Active Directory password resets
- User account support
- Microsoft Outlook troubleshooting
- Outlook indexing troubleshooting
- Mailbox synchronisation
- Recording troubleshooting steps
- Recording resolution actions
- Requesting user verification
- Clear communication with non-technical users
- Structured issue management
- Attention to detail
- Technical documentation

---

## Key Learning Outcomes

Through this project I developed practical experience in:

- Using a cloud-based help desk platform
- Understanding how IT support requests are logged and managed
- Assessing incidents according to impact and urgency
- Prioritising multiple support requests
- Performing first-line troubleshooting
- Recording technical investigation and resolution steps
- Separating technician notes from user-facing communication
- Maintaining a clear history of support activity
- Updating users throughout the support process
- Using ticket statuses to manage outstanding work
- Understanding when a ticket should remain Waiting for user confirmation
- Requesting user verification after troubleshooting
- Closing incidents after resolution
- Understanding how technical troubleshooting and ticket management work together in a first-line IT support environment

---

## Relationship to Other Portfolio Projects

This project focuses on combining technical troubleshooting with the service desk and ticket-management side of IT support.

Other repositories in this portfolio provide additional technical evidence in areas including:

- Windows endpoint troubleshooting
- Active Directory administration
- Microsoft Entra ID user and authentication support
- Microsoft Quick Assist remote troubleshooting
- PowerShell diagnostic information collection

Together, the projects demonstrate a broader first-line IT support workflow:

**User reports an issue → ticket is logged and prioritised → investigation is performed → the issue is resolved or escalated → the user verifies the result → the ticket is updated and closed.**

---

## Project Context

This project was completed in a controlled IT support lab using Spiceworks Cloud Help Desk and supporting Windows lab environments.

The users and incidents were created specifically for the lab to simulate realistic first-line IT support requests.

The technical troubleshooting actions documented in the tickets, including VPN troubleshooting, Active Directory account support and Outlook troubleshooting, were performed as part of the lab exercise.

Spiceworks was used to practise the service desk side of the workflow, including:

- Logging incidents
- Assigning priorities
- Recording internal technician notes
- Documenting troubleshooting and resolution steps
- Communicating with users
- Updating ticket statuses
- Closing tickets or placing them into a Waiting state

Not every underlying technical troubleshooting step was separately captured in a screenshot. The screenshots in this repository primarily document the ticket-management and communication workflow.

All work was completed in a controlled lab environment and did not involve production users or organisational systems.
