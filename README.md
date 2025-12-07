# MCP Explorer
A simple, browser-based tool for exploring Model Context Protocol (MCP) servers.  
Paste an MCP manifest or discovery URL, and the tool will display:

- Available MCP tools
- Descriptions and metadata
- Resources, models, and actions (if provided)
- The raw JSON manifest

This tool runs **entirely in your browser**.  
No backend, no tracking, no data stored.

## 🌐 Live Demo
https://aruneshmishra.github.io/mcp-explorer/

## 🚀 Features
- Zero backend — works fully client-side
- MCP tool inspection
- JSON viewer
- Auto-detection of tools/resources/models/actions
- Developer-friendly output

## 📦 How it Works
The page fetches your MCP endpoint URL (must support HTTPS + CORS)  
and renders everything client-side using JavaScript.

## ⚠ Requirements
Your MCP server must:
- Serve JSON
- Allow `GET` requests
- Include `Access-Control-Allow-Origin: *` (or your domain)

## 📄 License
MIT License
