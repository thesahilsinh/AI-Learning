# Introduction :    

### Goals :  

- overview  
- MCP clients and servers  
- Tools  
- resources    
- prompts   

### requirement :    

- basic python and UV setup   

powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"   

i am using this command to install in my win pc    

https://docs.astral.sh/uv/     

for good understanding of UV use this website    

### MCP :   

you can see the notes after the video but here i will summurize in my own words and what i understood is that MCP help us to connect a tool using API function calls and help us to lower down the burdon of making schemas + functions which help to perform task on it own.

official defination : Model Context Protocol (MCP) is a communication layer that provides Claude with context and tools without requiring you to write a bunch of tedious integration code. Think of it as a way to shift the burden of tool definitions and execution away from your server to specialized MCP servers.

this one i have cited from the course it self just for reference.

### MCP CLients :    

this bridge our server with MCp server.   
it has two protocol that a client can communicate to server.
- Standard IO : locally running mcp server
- Websockets : it runs functions depends on the request.

# Hands-on with MCP servers

### Project setup

- CLI based chatbot

so to set up a CLI chatbot download the zip files that are in my repository called cli_project. this files are the part of this course and i am performing the things and setup described in course.