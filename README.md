# SQLCL-MCP-Server-using-Openwebui-without-Docker
SQLCL MCP Server integrated with Openwebui, running without Docker. This project provides a lightweight, standalone setup to execute SQLCL commands through a web-based UI, ideal for environments that prefer direct installation over containerized deployments.

*Cammand for exposing tools on one port using MCPO*



uvx mcpo --port 9000 --api-key "Your_API_Key" -- "C:\sqlcl_mcp\sqlcl\bin\sql.exe" -mcp -mcpport:9090 oracle_db_username/Oracle_Db_password@localhost:1521/DNS




