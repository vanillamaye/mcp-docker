# Create a Docker Container using Cursor

**Project Link:** [AI MCP Docker](http://learn.nextwork.org/projects/ai-mcp-docker)  
**Author:** Marielle Bahuyo

## Project Overview
In this project, I created a running PostgreSQL database container managed entirely through Cursor's AI chat using the Docker MCP.

### Key Tools & Concepts
* **Cursor & Docker**: Used Docker Desktop and the Docker MCP to bridge AI agents with my local dev environment.
* **Python & uv**: Installed Python for compatibility and `uv` for faster package management.[cite: 1]
* **Docker Compose**: Orchestrated both PostgreSQL and Adminer containers.[cite: 1]

## Setup & Implementation
1. **Docker MCP**: Enabled the MCP to allow Cursor to read and edit files securely.[cite: 1]
2. **PostgreSQL Container**: Created a container named `my-db` and verified its "running" status in Docker Desktop.[cite: 1]
3. **Adminer**: Set up a web-based UI to access the database at `localhost:8080`.[cite: 1]

## Lessons Learned
* **Logs**: Learned to check container logs directly through Cursor using the Docker MCP tool instead of the terminal.[cite: 1]
* **Challenges**: The most challenging part was understanding the prompts and port configurations.[cite: 1]