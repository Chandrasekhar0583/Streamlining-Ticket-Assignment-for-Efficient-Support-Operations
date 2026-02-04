# System Architecture

## Overview
The automated ticket assignment system is built on ServiceNow ITSM and uses
core platform components to route tickets efficiently.

## Components Used
- Custom Table (Operations Related)
- Users, Groups, and Roles
- Access Control Lists (ACLs)
- Flow Designer

## Architecture Flow
1. User creates a ticket
2. Flow Designer trigger executes
3. Conditions are evaluated
4. Assignment group is set automatically
5. Notification is sent to the assigned team
