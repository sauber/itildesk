# itildesk
Game Simulating ticket flow between ITIL Functions

In the current configuration you have 5 desks:

* Incident Desk for handling incidents (unexpected interruptions which need to be addressed ASAP
* Problem Desk for managing recurring incidents as well as prro-actively try to prevent incidents from happening
* Engineering desk for creating new solutions to new problems as well as developing solutions for existing probems
* Service Desk for executing service requests from users
* Deploy Desk to do planned changes in the environment

Not all desks are currently used. The initial focus was on Incident/Problem/Engineering.

Actions each desk can do:

* Incident Desk
 * identify: identify what a new ticket is about
 * pass: give this ticket to the Problem Desk
 * invent: a method (solution) to fix a new incident ticket is created (invented)
 * breakfix: an identified ticket can get fixed with a known solution by an engineer
 * request: request to invent a solution. Ticket is assigned to Incident Desk.
 * transfer: Move the selected person to another (random) team.

