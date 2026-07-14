# Lawstronaut MCP

## Overview

Lawstronaut is a remote MCP server that provides access to millions of legal documents, including laws, regulations, and court decisions.

## Transport

- Streamable HTTP
- Endpoint: https://mcp.lawstronaut.com

## Authentication

Supports:

- OAuth 2.0 Client Credentials (recommended)
- Bearer API Token

OAuth discovery endpoints:

- /.well-known/oauth-authorization-server
- /.well-known/oauth-protected-resource