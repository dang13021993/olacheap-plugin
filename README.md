# OlaCheap

OlaCheap offers domains, business email, hosting, VPS and a free website checker on [olacheap.com](https://olacheap.com).

This package contains configuration only. It connects your assistant to the OlaCheap MCP server at `https://olacheap.com/api/mcp` (Streamable HTTP, requires sign-in).

**Requires sign-in.** The server answers 401 until you sign in with your OlaCheap account (OAuth) or send a personal API key as `Authorization: Bearer ocp_...`. Its tools are listed by the server after sign-in, so they are not listed here.

## Install

| Client | Command |
|---|---|
| Claude Code | `/plugin marketplace add dang13021993/olacheap-plugin` then `/plugin install olacheap@olacheap` |
| Gemini CLI | `gemini extensions install https://github.com/dang13021993/olacheap-plugin` |
| Qwen Code | `qwen extensions install dang13021993/olacheap-plugin` |
| Kimi Code | `/plugins install https://github.com/dang13021993/olacheap-plugin` |
| DeepSeek Harness | `dsh plugin --profile <profile> add github:dang13021993/olacheap-plugin` |
| Any MCP client | Streamable HTTP URL `https://olacheap.com/api/mcp` |

## Contact

support@olacheap.com · https://olacheap.com · License: MIT.
