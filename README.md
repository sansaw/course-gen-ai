Build Your First MCP Server: Leave Management

This AI tool helps an HR with leave management related tasks. The codebase here is for MCP server that interacts with mock leave database and responds to MCP client queries

Setup steps

Install Claude Desktop

1)  course-gen-ai % brew install mcp  


2)  course-gen-ai % brew install uv  

 

3)  course-gen-ai % uv init my-first-mcp-server 

 

4)  my-first-mcp-server % uv add "mcp[cli]"  

After init my-first-mcp-server  

5) 3 files created  main.py  pyproject.toml README.md

6)  my-first-mcp-server % ls -l  

total 16 

-rw-r--r--@ 1   staff   97 Aug 13 21:52 main.py 

-rw-r--r--@ 1   staff  165 Aug 13 21:52 pyproject.toml 

-rw-r--r--@ 1   staff    0 Aug 13 21:52 README.md 


7) Just created basic skleton main.py - write your code  

8) my-first-mcp-server % uv run mcp install main.py 

[08/13/25 21:59:01] INFO     Added server 'LeaveManager' to Claude config           claude.py:136 

                    INFO     Successfully installed LeaveManager in Claude app         cli.py:485 

9)  my-first-mcp-server %  
 
10) Leave Manager MCP avaiable in Claude  
