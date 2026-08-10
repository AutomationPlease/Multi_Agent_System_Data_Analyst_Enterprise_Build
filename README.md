# Multi_Agent_System_Data_Analyst_Enterprise_Build
Multi Agent System Data Analyst build with enterprise grade security.

**Note: This repo is being continually updated. Project source code is not uploaded at this time.**

## Analysis Tools
Database tools that operate on PostgreSQL data:
- Inventory summary
- Highest on-hand items
- Low stock detection
- Demand versus on-hand comparison
- Overdue order identification
- Demand spike detection

## Security Notes
- Passwords are stored as bcrypt hashes.
- API routes are protected with an API key.
- Rate limiting is applied to selected endpoints.
- Security headers are attached in middleware.
- Role checks gate admin UI access.
- File access is constrained through path validation helpers.

## Operational Status
Implemented:
- Authenticated multi-user access
- Role model for admin and standard users
- Persistent threads
- Database-backed inventory analysis
- Dockerized API deployment

## License
Proprietary. Internal use only unless otherwise specified by the project owner.

## User Interface and Application Screenshots

→ [View Project](https://github.com/AutomationPlease/Multi_Agent_System_Data_Analyst_Enterprise_Build/streamlit_app_showcase)

## Architecture

Here are some diagrams I made to show the system architecture design for the enterprise build:


![System_Architecture](Screenshots/System_Architecture.drawio.png)



##
![Chat_Flowchart](Screenshots/Delegation_Flow_Agents_Diagram.drawio.png)




##
![Agents](Screenshots/Agent_Specialist_current_drawio.png)
