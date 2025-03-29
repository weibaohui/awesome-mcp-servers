# Awesome MCP Servers [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![English](https://img.shields.io/badge/English-Click-yellow)](README.md)
[![中文文档](https://img.shields.io/badge/中文文档-点击查看-orange)](README-zh.md)
[![日本語](https://img.shields.io/badge/日本語-クリック-青)](README-ja.md)
[![Discord](https://img.shields.io/discord/1312302100125843476?logo=discord&label=discord)](https://glama.ai/mcp/discord)
[![Subreddit subscribers](https://img.shields.io/reddit/subreddit-subscribers/mcp?style=flat&logo=reddit&label=subreddit)](https://www.reddit.com/r/mcp/)

A curated list of awesome Model Context Protocol (MCP) servers.

* [What is MCP?](#what-is-mcp)
* [Clients](#clients)
* [Tutorials](#tutorials)
* [Server Implementations](#server-implementations)
* [Frameworks](#frameworks)
* [Utilities](#utilities)
* [Tips & Tricks](#tips-and-tricks)

## What is MCP?

[MCP](https://modelcontextprotocol.io/) is an open protocol that enables AI models to securely interact with local and remote resources through standardized server implementations. This list focuses on production-ready and experimental MCP servers that extend AI capabilities through file access, database connections, API integrations, and other contextual services.

## Clients

Checkout [awesome-mcp-clients](https://github.com/punkpeye/awesome-mcp-clients/) and [glama.ai/mcp/clients](https://glama.ai/mcp/clients).

> [!TIP]
> [Glama Chat](https://glama.ai/chat) is a multi-modal AI client with MCP support & [AI gateway](https://glama.ai/gateway).

## Tutorials

* [Model Context Protocol (MCP) Quickstart](https://glama.ai/blog/2024-11-25-model-context-protocol-quickstart)
* [Setup Claude Desktop App to Use a SQLite Database](https://youtu.be/wxCCzo9dGj0)

## Community

* [r/mcp Reddit](https://www.reddit.com/r/mcp)
* [Discord Server](https://glama.ai/mcp/discord)

## Legend

* 🎖️ – official implementation
* programming language
  * 🐍 – Python codebase
  * 📇 – TypeScript codebase
  * 🏎️ – Go codebase
  * 🦀 – Rust codebase
  * #️⃣ - C# Codebase
  * ☕ - Java codebase
* scope
  * ☁️ - Cloud Service
  * 🏠 - Local Service
* operating system
  * 🍎 – For macOS
  * 🪟 – For Windows
  * 🐧 - For Linux

> [!NOTE]
> Confused about Local 🏠 vs Cloud ☁️?
> * Use local when MCP server is talking to a locally installed software, e.g. taking control over Chrome browser.
> * Use network when MCP server is talking to remote APIs, e.g. weather API.

## Server Implementations

> [!NOTE]
> We now have a [web-based directory](https://glama.ai/mcp/servers) that is synced with the repository.

* 📂 - [Browser Automation](#browser-automation)
* 🎨 - [Art & Culture](#art-and-culture)
* ☁️ - [Cloud Platforms](#cloud-platforms)
* 🖥️ - [Command Line](#command-line)
* 💬 - [Communication](#communication)
* 👤 - [Customer Data Platforms](#customer-data-platforms)
* 🗄️ - [Databases](#databases)
* 🛠️ - [Developer Tools](#developer-tools)
* 📂 - [File Systems](#file-systems)
* 💰 - [Finance & Fintech](#finance--fintech)
* 🎮 - [Gaming](#gaming)
* 🧠 - [Knowledge & Memory](#knowledge--memory)
* 🗺️ - [Location Services](#location-services)
* 🎯 - [Marketing](#marketing)
* 📊 - [Monitoring](#monitoring)
* 🔎 - [Search](#search)
* 🔒 - [Security](#security)
* 🏃 - [Sports](#sports)
* 🚆 - [Travel & Transportation](#travel-and-transportation)
* 🔄 - [Version Control](#version-control)
* 🛠️ - [Other Tools and Integrations](#other-tools-and-integrations)

### 📂 <a name="browser-automation"></a>Browser Automation

Web content access and automation capabilities. Enables searching, scraping, and processing web content in AI-friendly formats.
- [@blackwhite084/playwright-plus-python-mcp](https://github.com/blackwhite084/playwright-plus-python-mcp) 🌐 - An MCP python server using Playwright for browser automation,more suitable for llm
- [@executeautomation/playwright-mcp-server](https://github.com/executeautomation/mcp-playwright) 🌐⚡️ - An MCP server using Playwright for browser automation and webscrapping
- [@automatalabs/mcp-server-playwright](https://github.com/Automata-Labs-team/MCP-Server-Playwright) 🌐 🖱️ - An MCP server for browser automation using Playwright
- [@modelcontextprotocol/server-puppeteer](https://github.com/modelcontextprotocol/servers/tree/main/src/puppeteer) 📇 🏠 - Browser automation for web scraping and interaction
- [@kimtaeyoon83/mcp-server-youtube-transcript](https://github.com/kimtaeyoon83/mcp-server-youtube-transcript) 📇 ☁️ - Fetch YouTube subtitles and transcripts for AI analysis
- [@recursechat/mcp-server-apple-shortcuts](https://github.com/recursechat/mcp-server-apple-shortcuts) 📇 🏠 🍎 - An MCP Server Integration with Apple Shortcuts
- [@kimtth/mcp-aoai-web-browsing](https://github.com/kimtth/mcp-aoai-web-browsing) 🐍 🏠 - A `minimal` server/client MCP implementation using Azure OpenAI and Playwright.
- [@pskill9/web-search](https://github.com/pskill9/web-search) 📇 🏠 - An MCP server that enables free web searching using Google search results, with no API keys required.
- [@co-browser/browser-use-mcp-server](https://github.com/co-browser/browser-use-mcp-server) 🌐🔮 - browser-use packaged as an MCP server with SSE transport. includes a dockerfile to run chromium in docker + a vnc server.
- [@34892002/bilibili-mcp-js](https://github.com/34892002/bilibili-mcp-js) 📇 🏠 - A MCP server that supports searching for Bilibili content. Provides LangChain integration examples and test scripts.
- [@getrupt/ashra-mcp](https://github.com/getrupt/ashra-mcp) 🐍 🏠 - Extract structured data from any website. Just prompt and get JSON.


### 🎨 <a name="art-and-culture"></a>Art & Culture

Access and explore art collections, cultural heritage, and museum databases. Enables AI models to search and analyze artistic and cultural content.

- [burningion/video-editing-mcp](https://github.com/burningion/video-editing-mcp) 📹🎬 - Add, Analyze, Search, and Generate Video Edits from your Video Jungle Collection
- [r-huijts/rijksmuseum-mcp](https://github.com/r-huijts/rijksmuseum-mcp) 📇 ☁️ - Rijksmuseum API integration for artwork search, details, and collections
- [yuna0x0/anilist-mcp](https://github.com/yuna0x0/anilist-mcp) 📇 ☁️ - A MCP server integrating AniList API for anime and manga information 

### ☁️ <a name="cloud-platforms"></a>Cloud Platforms

Cloud platform service integration. Enables management and interaction with cloud infrastructure and services.

- [Cloudflare MCP Server](https://github.com/cloudflare/mcp-server-cloudflare) 🎖️ 📇 ☁️ - Integration with Cloudflare services including Workers, KV, R2, and D1
- [alexei-led/aws-mcp-server](https://github.com/alexei-led/aws-mcp-server) 🐍 ☁️ - A lightweight but powerful server that enables AI assistants to execute AWS CLI commands, use Unix pipes, and apply prompt templates for common AWS tasks in a safe Docker environment with multi-architecture support
- [Kubernetes MCP Server](https://github.com/strowk/mcp-k8s-go) - 🏎️ ☁️/🏠 Kubernetes cluster operations through MCP
- [@flux159/mcp-server-kubernetes](https://github.com/Flux159/mcp-server-kubernetes) - 📇 ☁️/🏠 Typescript implementation of Kubernetes cluster operations for pods, deployments, services.
- [@manusa/Kubernetes MCP Server](https://github.com/manusa/kubernetes-mcp-server) - 🏎️ 🏠 A powerful Kubernetes MCP server with additional support for OpenShift. Besides providing CRUD operations for **any** Kubernetes resource, this server provides specialized tools to interact with your cluster.
- [wenhuwang/mcp-k8s-eye](https://github.com/wenhuwang/mcp-k8s-eye) 🏎️ ☁️/🏠 MCP Server for kubernetes management, and analyze your cluster, application health
- [johnneerdael/netskope-mcp](https://github.com/johnneerdael/netskope-mcp) 🔒 ☁️ - An MCP to give access to all Netskope Private Access components within a Netskope Private Access environments including detailed setup information and LLM examples on usage.
- [nwiizo/tfmcp](https://github.com/nwiizo/tfmcp) - 🦀 🏠 - A Terraform MCP server allowing AI assistants to manage and operate Terraform environments, enabling reading configurations, analyzing plans, applying configurations, and managing Terraform state.
- [weibaohui/k8m](https://github.com/weibaohui/k8m) - 🏎️ ☁️/🏠 Provides MCP multi-cluster Kubernetes management and operations, featuring a management ui, logging, and nearly 50 built-in tools covering common DevOps and development scenarios. Supports both standard and CRD resources.  
- [weibaohui/kom](https://github.com/weibaohui/kom) - 🏎️ ☁️/🏠 Provides MCP multi-cluster Kubernetes management and operations. It can be integrated as an SDK into your own project and includes nearly 50 built-in tools covering common DevOps and development scenarios. Supports both standard and CRD resources.

### 🖥️ <a name="command-line"></a>Command Line

Run commands, capture output and otherwise interact with shells and command line tools.

- [ferrislucas/iterm-mcp](https://github.com/ferrislucas/iterm-mcp) 🖥️ 🛠️ 💬 - A Model Context Protocol server that provides access to iTerm. You can run commands and ask questions about what you see in the iTerm terminal.
- [g0t4/mcp-server-commands](https://github.com/g0t4/mcp-server-commands) 📇 🏠 - Run any command with `run_command` and `run_script` tools.
- [MladenSU/cli-mcp-server](https://github.com/MladenSU/cli-mcp-server) 🐍 🏠 - Command line interface with secure execution and customizable security policies
- [tumf/mcp-shell-server](https://github.com/tumf/mcp-shell-server) A secure shell command execution server implementing the Model Context Protocol (MCP)

### 💬 <a name="communication"></a>Communication

Integration with communication platforms for message management and channel operations. Enables AI models to interact with team communication tools.

- [zcaceres/gtasks-mcp](https://github.com/zcaceres/gtasks-mcp) - 📇 ☁️ - An MCP server to Manage Google Tasks
- [hannesrudolph/imessage-query-fastmcp-mcp-server](https://github.com/hannesrudolph/imessage-query-fastmcp-mcp-server) 🐍 🏠 🍎 - An MCP server that provides safe access to your iMessage database through Model Context Protocol (MCP), enabling LLMs to query and analyze iMessage conversations with proper phone number validation and attachment handling
- [@modelcontextprotocol/server-slack](https://github.com/modelcontextprotocol/servers/tree/main/src/slack) 📇 ☁️ - Slack workspace integration for channel management and messaging
- [@modelcontextprotocol/server-bluesky](https://github.com/keturiosakys/bluesky-context-server) 📇 ☁️ - Bluesky instance integration for querying and interaction
- [MarkusPfundstein/mcp-gsuite](https://github.com/MarkusPfundstein/mcp-gsuite) - 🐍 ☁️ - Integration with gmail and Google Calendar.
- [adhikasp/mcp-twikit](https://github.com/adhikasp/mcp-twikit) 🐍 ☁️ - Interact with Twitter search and timeline
- [gotoolkits/wecombot](https://github.com/gotoolkits/mcp-wecombot-server.git) - 🚀 ☁️  - An MCP server application that sends various types of messages to the WeCom group robot.
- [AbdelStark/nostr-mcp](https://github.com/AbdelStark/nostr-mcp) - 🌐 ☁️ - A Nostr MCP server that allows to interact with Nostr, enabling posting notes, and more.
- [elie222/inbox-zero](https://github.com/elie222/inbox-zero/tree/main/apps/mcp-server) - 🐍 ☁️ - An MCP server for Inbox Zero. Adds functionality on top of Gmail like finding out which emails you need to reply to or need to follow up on.
- [carterlasalle/mac_messages_mcp](https://github.com/carterlasalle/mac_messages_mcp) 🏠 🍎 🚀 - An MCP server that securely interfaces with your iMessage database via the Model Context Protocol (MCP), allowing LLMs to query and analyze iMessage conversations. It includes robust phone number validation, attachment processing, contact management, group chat handling, and full support for sending and receiving messages.
- [sawa-zen/vrchat-mcp](https://github.com/sawa-zen/vrchat-mcp) - 📇 🏠 This is an MCP server for interacting with the VRChat API. You can retrieve information about friends, worlds, avatars, and more in VRChat.
- [arpitbatra123/mcp-googletasks](https://github.com/arpitbatra123/mcp-googletasks) - 📇 ☁️ - An MCP server to interface with the Google Tasks API

### 👤 <a name="customer-data-platforms"></a>Customer Data Platforms

Provides access to customer profiles inside of customer data platforms

- [sergehuber/inoyu-mcp-unomi-server](https://github.com/sergehuber/inoyu-mcp-unomi-server) 📇 ☁️ - An MCP server to access and updates profiles on an Apache Unomi CDP server.
- [OpenDataMCP/OpenDataMCP](https://github.com/OpenDataMCP/OpenDataMCP) 🐍 ☁️ - Connect any Open Data to any LLM with Model Context Protocol.
- [tinybirdco/mcp-tinybird](https://github.com/tinybirdco/mcp-tinybird) 🐍 ☁️ - An MCP server to interact with a Tinybird Workspace from any MCP client.
- [@iaptic/mcp-server-iaptic](https://github.com/iaptic/mcp-server-iaptic) 🎖️ 📇 ☁️ - Connect with [iaptic](https://www.iaptic.com) to ask about your Customer Purchases, Transaction data and App Revenue statistics.

### 🗄️ <a name="databases"></a>Databases

Secure database access with schema inspection capabilities. Enables querying and analyzing data with configurable security controls including read-only access.

- [aliyun/alibabacloud-tablestore-mcp-server](https://github.com/aliyun/alibabacloud-tablestore-mcp-server) ☕ 🐍 ☁️ - MCP service for Tablestore, features include adding documents, semantic search for documents based on vectors and scalars, RAG-friendly, and serverless.
- [cr7258/elasticsearch-mcp-server](https://github.com/cr7258/elasticsearch-mcp-server) 🐍 🏠 - MCP Server implementation that provides Elasticsearch interaction
- [domdomegg/airtable-mcp-server](https://github.com/domdomegg/airtable-mcp-server) 📇 🏠 - Airtable database integration with schema inspection, read and write capabilities
- [rashidazarang/airtable-mcp](https://github.com/rashidazarang/airtable-mcp) 🐍 ☁️ - Connect AI tools directly to Airtable. Query, create, update, and delete records using natural language. Features include base management, table operations, schema manipulation, record filtering, and data migration through a standardized MCP interface.
- [LucasHild/mcp-server-bigquery](https://github.com/LucasHild/mcp-server-bigquery) 🐍 ☁️ - BigQuery database integration with schema inspection and query capabilities
- [c4pt0r/mcp-server-tidb](https://github.com/c4pt0r/mcp-server-tidb) 🐍 ☁️ - TiDB database integration with schema inspection and query capabilities
- [tradercjz/dolphindb-mcp-server](https://github.com/tradercjz/dolphindb-mcp-server) 🐍 ☁️ - TDolphinDB database integration with schema inspection and query capabilities
- [ergut/mcp-bigquery-server](https://github.com/ergut/mcp-bigquery-server) 📇 ☁️ - Server implementation for Google BigQuery integration that enables direct BigQuery database access and querying capabilities
- [ClickHouse/mcp-clickhouse](https://github.com/ClickHouse/mcp-clickhouse) 🐍 ☁️ - ClickHouse database integration with schema inspection and query capabilities
- [get-convex/convex-backend](https://stack.convex.dev/convex-mcp-server) 📇 ☁️ - Convex database integration to introspect tables, functions, and run oneoff queries ([Source](https://github.com/get-convex/convex-backend/blob/main/npm-packages/convex/src/cli/mcp.ts))
- [@gannonh/firebase-mcp](https://github.com/gannonh/firebase-mcp) 🔥 ⛅️ - Firebase services including Auth, Firestore and Storage.
- [jovezhong/mcp-timeplus](https://github.com/jovezhong/mcp-timeplus) 🐍 ☁️ - MCP server for Apache Kafka and Timeplus. Able to list Kafka topics, poll Kafka messages, save Kafka data locally and query streaming data with SQL via Timeplus
- [@fireproof-storage/mcp-database-server](https://github.com/fireproof-storage/mcp-database-server) 📇 ☁️ - Fireproof ledger database with multi-user sync
- [designcomputer/mysql_mcp_server](https://github.com/designcomputer/mysql_mcp_server) 🐍 🏠 - MySQL database integration with configurable access controls, schema inspection, and comprehensive security guidelines
- [f4ww4z/mcp-mysql-server](https://github.com/f4ww4z/mcp-mysql-server) 🐍 🏠 - Node.js-based MySQL database integration that provides secure MySQL database operations
- [FreePeak/db-mcp-server](https://github.com/FreePeak/db-mcp-server) 🏎️ 🏠 – A high-performance multi-database MCP server built with Golang, supporting MySQL & PostgreSQL (NoSQL coming soon). Includes built-in tools for query execution, transaction management, schema exploration, query building, and performance analysis, with seamless Cursor integration for enhanced database workflows.
- [@modelcontextprotocol/server-postgres](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres) 📇 🏠 - PostgreSQL database integration with schema inspection and query capabilities
- [@modelcontextprotocol/server-sqlite](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite) 🐍 🏠 - SQLite database operations with built-in analysis features
- [@joshuarileydev/supabase-mcp-server](https://github.com/joshuarileydev/supabase) - Supabase MCP Server for managing and creating projects and organisations in Supabase
- [@alexanderzuev/supabase-mcp-server](https://github.com/alexander-zuev/supabase-mcp-server) - Supabase MCP Server with support for SQL query execution and database exploration tools
- [ktanaka101/mcp-server-duckdb](https://github.com/ktanaka101/mcp-server-duckdb) 🐍 🏠 - DuckDB database integration with schema inspection and query capabilities
- [Dataring-engineering/mcp-server-trino](https://github.com/Dataring-engineering/mcp-server-trino) 🐍 ☁️ - Trino MCP Server to query and access data from Trino Clusters.
- [memgraph/mcp-memgraph](https://github.com/memgraph/mcp-memgraph) 🐍 🏠 - Memgraph MCP Server - includes a tool to run a query against Memgraph and a schema resource.
- [furey/mongodb-lens](https://github.com/furey/mongodb-lens) 📇 🏠 - MongoDB Lens: Full Featured MCP Server for MongoDB Databases
- [QuantGeekDev/mongo-mcp](https://github.com/QuantGeekDev/mongo-mcp) 📇 🏠 - MongoDB integration that enables LLMs to interact directly with databases.
- [kiliczsh/mcp-mongo-server](https://github.com/kiliczsh/mcp-mongo-server) 📇 🏠 - A Model Context Protocol Server for MongoDB
- [tinybirdco/mcp-tinybird](https://github.com/tinybirdco/mcp-tinybird) 🐍 ☁️ - Tinybird integration with query and API capabilities
- [KashiwaByte/vikingdb-mcp-server](https://github.com/KashiwaByte/vikingdb-mcp-server) 🐍 ☁️ - VikingDB integration with collection and index introduction, vector store and search capabilities.
- [neo4j-contrib/mcp-neo4j](https://github.com/neo4j-contrib/mcp-neo4j) 🐍 🏠 - Model Context Protocol with Neo4j
- [niledatabase/nile-mcp-server](https://github.com/niledatabase/nile-mcp-server) MCP server for Nile's Postgres platform - Manage and query Postgres databases, tenants, users, auth using LLMs
- [isaacwasserman/mcp-snowflake-server](https://github.com/isaacwasserman/mcp-snowflake-server) 🐍 ☁️ - Snowflake integration implementing read and (optional) write operations as well as insight tracking
- [hannesrudolph/sqlite-explorer-fastmcp-mcp-server](https://github.com/hannesrudolph/sqlite-explorer-fastmcp-mcp-server) 🐍 🏠 - An MCP server that provides safe, read-only access to SQLite databases through Model Context Protocol (MCP). This server is built with the FastMCP framework, which enables LLMs to explore and query SQLite databases with built-in safety features and query validation.
- [sirmews/mcp-pinecone](https://github.com/sirmews/mcp-pinecone) 🐍 ☁️ - Pinecone integration with vector search capabilities
- [runekaagaard/mcp-alchemy](https://github.com/runekaagaard/mcp-alchemy) 🐍 🏠 - Universal SQLAlchemy-based database integration supporting PostgreSQL, MySQL, MariaDB, SQLite, Oracle, MS SQL Server and many more databases. Features schema and relationship inspection, and large dataset analysis capabilities.
- [mcp-server-jdbc](https://github.com/quarkiverse/quarkus-mcp-servers/tree/main/jdbc) ☕ 🏠 - Connect to any JDBC-compatible database and query, insert, update, delete, and more.
- [pab1it0/adx-mcp-server](https://github.com/pab1it0/adx-mcp-server) 🐍 ☁️ - Query and analyze Azure Data Explorer databases
- [pab1it0/prometheus-mcp-server](https://github.com/pab1it0/prometheus-mcp-server) 🐍 ☁️ -  Query and analyze Prometheus, open-source monitoring system.
- [neondatabase/mcp-server-neon](https://github.com/neondatabase/mcp-server-neon) 📇 ☁️ — An MCP Server for creating and managing Postgres databases using Neon Serverless Postgres
- [XGenerationLab/xiyan_mcp_server](https://github.com/XGenerationLab/xiyan_mcp_server) 📇 ☁️ — An MCP server that supports fetching data from a database using natural language queries, powered by XiyanSQL as the text-to-SQL LLM.
- [bytebase/dbhub](https://github.com/bytebase/dbhub) 📇 🏠 – Universal database MCP server supporting mainstream databases.
- [GreptimeTeam/greptimedb-mcp-server](https://github.com/GreptimeTeam/greptimedb-mcp-server) 🐍 🏠 - MCP Server for querying GreptimeDB.
- [idoru/influxdb-mcp-server](https://github.com/idoru/influxdb-mcp-server) 📇 ☁️ 🏠 - Run queries against InfluxDB OSS API v2.
- [xing5/mcp-google-sheets](https://github.com/xing5/mcp-google-sheets) 🐍 ☁️ - A Model Context Protocol server for interacting with Google Sheets. This server provides tools to create, read, update, and manage spreadsheets through the Google Sheets API.
- [qdrant/mcp-server-qdrant](https://github.com/qdrant/mcp-server-qdrant) 🐍 🏠 - A Qdrant MCP server

### 💻 <a name="developer-tools"></a>Developer Tools

Tools and integrations that enhance the development workflow and environment management.

- [21st-dev/Magic-MCP](https://github.com/21st-dev/magic-mcp) - Create crafted UI components inspired by the best 21st.dev design engineers.
- [Coment-ML/Opik-MCP](https://github.com/comet-ml/opik-mcp) 🎖️ 📇 ☁️ 🏠 - Talk to your LLM observability, traces and monitoring captured by Opik using natural language.
- [GLips/Figma-Context-MCP](https://github.com/GLips/Figma-Context-MCP) 📇 🏠 - Provide coding agents direct access to Figma data to help them one-shot design implementation.
- [QuantGeekDev/docker-mcp](https://github.com/QuantGeekDev/docker-mcp) 🏎️ 🏠 - Docker container management and operations through MCP
- [zcaceres/fetch-mcp](https://github.com/zcaceres/fetch-mcp) 📇 🏠 - An MCP server to flexibly fetch JSON, text, and HTML data
- [r-huijts/xcode-mcp-server](https://github.com/r-huijts/xcode-mcp-server) 📇 🏠 🍎 - Xcode integration for project management, file operations, and build automation
- [snaggle-ai/openapi-mcp-server](https://github.com/snaggle-ai/openapi-mcp-server) 🏎️ 🏠 - Connect any HTTP/REST API server using an Open API spec (v3)
- [jetbrains/mcpProxy](https://github.com/JetBrains/mcpProxy) 🎖️ 📇 🏠 - Connect to JetBrains IDE
- [tumf/mcp-text-editor](https://github.com/tumf/mcp-text-editor) 🐍 🏠 - A line-oriented text file editor. Optimized for LLM tools with efficient partial file access to minimize token usage.
- [@joshuarileydev/simulator-mcp-server](https://github.com/JoshuaRileyDev/simulator-mcp-server) 📇 🏠 - An MCP server to control iOS Simulators
- [@joshuarileydev/app-store-connect-mcp-server](https://github.com/JoshuaRileyDev/app-store-connect-mcp-server) 📇 🏠 - An MCP server to communicate with the App Store Connect API for iOS Developers
- [@sammcj/mcp-package-version](https://github.com/sammcj/mcp-package-version) 📇 🏠 - An MCP Server to help LLMs suggest the latest stable package versions when writing code.
- [@delano/postman-mcp-server](https://github.com/delano/postman-mcp-server) 📇 ☁️ - Interact with [Postman API](https://www.postman.com/postman/postman-public-workspace/)
- [@vivekvells/mcp-pandoc](https://github.com/vivekVells/mcp-pandoc) 🗄️ 🚀 - MCP server for seamless document format conversion using Pandoc, supporting Markdown, HTML, PDF, DOCX (.docx), csv and more.
- [@pskill9/website-downloader](https://github.com/pskill9/website-downloader) 🗄️ 🚀 - This MCP server provides a tool to download entire websites using wget. It preserves the website structure and converts links to work locally.
- [@lamemind/mcp-server-multiverse](https://github.com/lamemind/mcp-server-multiverse) 📇 🏠 🛠️ - A middleware server that enables multiple isolated instances of the same MCP servers to coexist independently with unique namespaces and configurations.
- [@j4c0bs/mcp-server-sql-analyzer](https://github.com/j4c0bs/mcp-server-sql-analyzer) 🐍 - MCP server that provides SQL analysis, linting, and dialect conversion using [SQLGlot](https://github.com/tobymao/sqlglot)
- [@haris-musa/excel-mcp-server](https://github.com/haris-musa/excel-mcp-server) 🐍 🏠 - An Excel manipulation server providing workbook creation, data operations, formatting, and advanced features (charts, pivot tables, formulae).
- [xcodebuild](https://github.com/ShenghaiWang/xcodebuild) 🍎 Build iOS Xcode workspace/project and feed back errors to llm.
- [@jasonjmcghee/claude-debugs-for-you](https://github.com/jasonjmcghee/claude-debugs-for-you) 📇 🏠 - An MCP Server and VS Code Extension which enables (language agnostic) automatic debugging via breakpoints and expression evaluation.
- [@Jktfe/serveMyAPI](https://github.com/Jktfe/serveMyAPI) 📇 🏠 🍎 - A personal MCP (Model Context Protocol) server for securely storing and accessing API keys across projects using the macOS Keychain.
- [@xzq.xu/jvm-mcp-server](https://github.com/xzq-xu/jvm-mcp-server) 📇 🏠  - An implementation project of a JVM-based MCP (Model Context Protocol) server. 
- [@yangkyeongmo@/mcp-server-apache-airflow](https://github.com/yangkyeongmo/mcp-server-apache-airflow) 🐍 🏠 - MCP server that connects to [Apache Airflow](https://airflow.apache.org/) using official client.
- [hyperb1iss/droidmind](https://github.com/hyperb1iss/droidmind) 🐍 🏠 - Control Android devices with AI through MCP, enabling device control, debugging, system analysis, and UI automation with a comprehensive security framework.
- [Rootly-AI-Labs/Rootly-MCP-server](https://github.com/Rootly-AI-Labs/Rootly-MCP-server) 🎖️🐍☁️🍎 - MCP server for the incident management platform [Rootly](https://rootly.com/).
- [YuChenSSR/mindmap-mcp-server](https://github.com/YuChenSSR/mindmap-mcp-server) 🐍 🏠 - A Model Context Protocol (MCP) server for generating a beautiful interactive mindmap.
- [SDGLBL/mcp-claude-code](https://github.com/SDGLBL/mcp-claude-code) 🐍 🏠 - An implementation of Claude Code capabilities using MCP, enabling AI code understanding, modification, and project analysis with comprehensive tool support.
- [gofireflyio/firefly-mcp](https://github.com/gofireflyio/firefly-mcp) 🎖️ 📇 ☁️ - Integrates, discovers, manages, and codifies cloud resources with [Firefly](https://firefly.ai).
- [yWorks/mcp-typescribe](https://github.com/yWorks/mcp-typescribe) 📇 🏠 - MCP server that provides Typescript API information efficiently to the agent to enable it to work with untrained APIs

### 🧮 Data Science Tools

Integrations and tools designed to simplify data exploration, analysis and enhance data science workflows.
- [ChronulusAI/chronulus-mcp](https://github.com/ChronulusAI/chronulus-mcp) 🐍 ☁️ - Predict anything with Chronulus AI forecasting and prediction agents.
- [zcaceres/markdownify-mcp](https://github.com/zcaceres/markdownify-mcp) 📇 🏠 - An MCP server to convert almost any file or web content into Markdown
- [@reading-plus-ai/mcp-server-data-exploration](https://github.com/reading-plus-ai/mcp-server-data-exploration) 🐍 ☁️ - Enables autonomous data exploration on .csv-based datasets, providing intelligent insights with minimal effort.

### 📂 <a name="file-systems"></a>File Systems

Provides direct access to local file systems with configurable permissions. Enables AI models to read, write, and manage files within specified directories.

- [@modelcontextprotocol/server-filesystem](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem) 📇 🏠 - Direct local file system access.
- [@modelcontextprotocol/server-google-drive](https://github.com/modelcontextprotocol/servers/tree/main/src/gdrive) 📇 ☁️ - Google Drive integration for listing, reading, and searching files
- [hmk/box-mcp-server](https://github.com/hmk/box-mcp-server) 📇 ☁️ - Box integration for listing, reading and searching files
- [mark3labs/mcp-filesystem-server](https://github.com/mark3labs/mcp-filesystem-server) 🏎️ 🏠 - Golang implementation for local file system access.
- [mamertofabian/mcp-everything-search](https://github.com/mamertofabian/mcp-everything-search) 🐍 🏠 🪟 - Fast Windows file search using Everything SDK
- [cyberchitta/llm-context.py](https://github.com/cyberchitta/llm-context.py) 🐍 🏠 - Share code context with LLMs via MCP or clipboard
- [filesystem@quarkiverse/quarkus-mcp-servers](https://github.com/quarkiverse/quarkus-mcp-servers/tree/main/filesystem) ☕ 🏠 - A filesystem allowing for browsing and editing files implemented in Java using Quarkus. Available as jar or native image.
- [Xuanwo/mcp-server-opendal](https://github.com/Xuanwo/mcp-server-opendal) 🐍 🏠 ☁️ - Access any storage with Apache OpenDAL™

### 💰 <a name="finance--fintech"></a>Finance & Fintech

Financial data access and cryptocurrency market information. Enables querying real-time market data, crypto prices, and financial analytics.

- [heurist-network/heurist-mesh-mcp-server](https://github.com/heurist-network/heurist-mesh-mcp-server) 🎖️ ⛅️ 🏠 🐍 - Access specialized web3 AI agents for blockchain analysis, smart contract security auditing, token metrics evaluation, and on-chain interactions through the Heurist Mesh network. Provides comprehensive tools for DeFi analysis, NFT valuation, and transaction monitoring across multiple blockchains
- [@base/base-mcp](https://github.com/base/base-mcp) 🎖️ 📇 ☁️ - Base Network integration for onchain tools, allowing interaction with Base Network and Coinbase API for wallet management, fund transfers, smart contracts, and DeFi operations
- [QuantGeekDev/coincap-mcp](https://github.com/QuantGeekDev/coincap-mcp) 📇 ☁️ - Real-time cryptocurrency market data integration using CoinCap's public API, providing access to crypto prices and market information without API keys
- [anjor/coinmarket-mcp-server](https://github.com/anjor/coinmarket-mcp-server) 🐍 ☁️ - Coinmarket API integration to fetch cryptocurrency listings and quotes
- [berlinbra/alpha-vantage-mcp](https://github.com/berlinbra/alpha-vantage-mcp) 🐍 ☁️ - Alpha Vantage API integration to fetch both stock and crypto information
- [ferdousbhai/tasty-agent](https://github.com/ferdousbhai/tasty-agent) 🐍 ☁️ - Tastyworks API integration to handle trading activities on Tastytrade
- [ferdousbhai/investor-agent](https://github.com/ferdousbhai/investor-agent) 🐍 ☁️ - Yahoo Finance integration to fetch stock market data including options recommendations
- [mcpdotdirect/evm-mcp-server](https://github.com/mcpdotdirect/evm-mcp-server) 📇 ☁️ - Comprehensive blockchain services for 30+ EVM networks, supporting native tokens, ERC20, NFTs, smart contracts, transactions, and ENS resolution.
- [bankless/onchain-mcp](https://github.com/Bankless/onchain-mcp/) 📇 ☁️ - Bankless Onchain API to interact with smart contracts, query transaction and token information
- [kukapay/cryptopanic-mcp-server](https://github.com/kukapay/cryptopanic-mcp-server) 🐍 ☁️ - Providing latest cryptocurrency news to AI agents, powered by CryptoPanic.
- [kukapay/whale-tracker-mcp](https://github.com/kukapay/whale-tracker-mcp) 🐍 ☁️ -  A mcp server for tracking cryptocurrency whale transactions.
- [kukapay/crypto-feargreed-mcp](https://github.com/kukapay/crypto-feargreed-mcp) 🐍 ☁️ -  Providing real-time and historical Crypto Fear & Greed Index data.
- [kukapay/dune-analytics-mcp](https://github.com/kukapay/dune-analytics-mcp) 🐍 ☁️ -  A mcp server that bridges Dune Analytics data to AI agents.
- [kukapay/pancakeswap-poolspy-mcp](https://github.com/kukapay/pancakeswap-poolspy-mcp) 🐍 ☁️ -  An MCP server that tracks newly created pools on Pancake Swap.
- [kukapay/uniswap-poolspy-mcp](https://github.com/kukapay/uniswap-poolspy-mcp) 🐍 ☁️ -  An MCP server that tracks newly created liquidity pools on Uniswap across multiple blockchains.
- [kukapay/uniswap-trader-mcp](https://github.com/kukapay/uniswap-trader-mcp) 🐍 ☁️ -  An MCP server for AI agents to automate token swaps on Uniswap DEX across multiple blockchains.
- [kukapay/token-minter-mcp](https://github.com/kukapay/token-minter-mcp) 🐍 ☁️ -  An MCP server providing tools for AI agents to mint ERC-20 tokens across multiple blockchains.
- [kukapay/thegraph-mcp](https://github.com/kukapay/thegraph-mcp) 🐍 ☁️ -  An MCP server that powers AI agents with indexed blockchain data from The Graph.
- [pwh-pwh/coin-mcp-server](https://github.com/pwh-pwh/coin-mcp-server) 🐍 ☁️ -  Bitget API to fetch cryptocurrency price.
 
### 🎮 <a name="gaming"></a>Gaming

Integration with gaming related data, game engines, and services

- [Coding-Solo/godot-mcp](https://github.com/Coding-Solo/godot-mcp) 📇 🏠 - A MCP server for interacting with the Godot game engine, providing tools for editing, running, debugging, and managing scenes in Godot projects.
- [rishijatia/fantasy-pl-mcp](https://github.com/rishijatia/fantasy-pl-mcp/) 🐍 ☁️ - An MCP server for real-time Fantasy Premier League data and analysis tools.
- [CoderGamester/mcp-unity](https://github.com/CoderGamester/mcp-unity) 📇 #️⃣ 🏠 - MCP Server for Unity3d Game Engine integration for game development

### 🧠 <a name="knowledge--memory"></a>Knowledge & Memory

Persistent memory storage using knowledge graph structures. Enables AI models to maintain and query structured information across sessions.
- [@modelcontextprotocol/server-memory](https://github.com/modelcontextprotocol/servers/tree/main/src/memory) 📇 🏠 - Knowledge graph-based persistent memory system for maintaining context
- [/CheMiguel23/MemoryMesh](https://github.com/CheMiguel23/MemoryMesh) 📇 🏠 - Enhanced graph-based memory with a focus on AI role-play and story generation
- [/topoteretes/cognee](https://github.com/topoteretes/cognee/tree/dev/cognee-mcp) 📇 🏠 - Memory manager for AI apps and Agents using various graph and vector stores and allowing ingestion from 30+ data sources
- [@hannesrudolph/mcp-ragdocs](https://github.com/hannesrudolph/mcp-ragdocs) 🐍 🏠 - An MCP server implementation that provides tools for retrieving and processing documentation through vector search, enabling AI assistants to augment their responses with relevant documentation context
- [@kaliaboi/mcp-zotero](https://github.com/kaliaboi/mcp-zotero) 📇 ☁️ - A connector for LLMs to work with collections and sources on your Zotero Cloud
- [mcp-summarizer](https://github.com/0xshellming/mcp-summarizer) 📕 ☁️ - AI Summarization MCP Server, Support for multiple content types: Plain text, Web pages, PDF documents, EPUB books, HTML content
- [graphlit-mcp-server](https://github.com/graphlit/graphlit-mcp-server) 📇 ☁️ - Ingest anything from Slack, Discord, websites, Google Drive, Linear or GitHub into a Graphlit project - and then search and retrieve relevant knowledge within an MCP client like Cursor, Windsurf or Cline.
- [@mem0ai/mem0-mcp](https://github.com/mem0ai/mem0-mcp) 🐍 🏠 - A Model Context Protocol server for Mem0 that helps manage coding preferences and patterns, providing tools for storing, retrieving and semantically handling code implementations, best practices and technical documentation in IDEs like Cursor and Windsurf

### 🗺️ <a name="location-services"></a>Location Services

Geographic and location-based services integration. Enables access to mapping data, directions, and place information.

- [@modelcontextprotocol/server-google-maps](https://github.com/modelcontextprotocol/servers/tree/main/src/google-maps) 📇 ☁️ - Google Maps integration for location services, routing, and place details
- [SecretiveShell/MCP-timeserver](https://github.com/SecretiveShell/MCP-timeserver) 🐍 🏠 - Access the time in any timezone and get the current local time
- [webcoderz/MCP-Geo](https://github.com/webcoderz/MCP-Geo) 🐍 🏠 - Geocoding MCP server for nominatim, ArcGIS, Bing
- [@briandconnelly/mcp-server-ipinfo](https://github.com/briandconnelly/mcp-server-ipinfo) 🐍 ☁️  - IP address geolocation and network information using IPInfo API
- [QGIS MCP](https://github.com/jjsantos01/qgis_mcp) - connects QGIS Desktop to Claude AI through the MCP. This integration enables prompt-assisted project creation, layer loading, code execution, and more.
-  [kukapay/nearby-search-mcp](https://github.com/kukapay/nearby-search-mcp) 🐍 ☁️ - An MCP server for nearby place searches with IP-based location detection.

### 🎯 <a name="marketing"></a>Marketing

Tools for creating and editing marketing content, working with web meta data, product positioning, and editing guides.

- [Open Strategy Partners Marketing Tools](https://github.com/open-strategy-partners/osp_marketing_tools) 🐍 🏠 - A suite of marketing tools from Open Strategy Partners including writing style, editing codes, and product marketing value map creation.

### 📊 <a name="monitoring"></a>Monitoring

Access and analyze application monitoring data. Enables AI models to review error reports and performance metrics.

- [@modelcontextprotocol/server-sentry](https://github.com/modelcontextprotocol/servers/tree/main/src/sentry) 🐍 ☁️ - Sentry.io integration for error tracking and performance monitoring
- [@modelcontextprotocol/server-raygun](https://github.com/MindscapeHQ/mcp-server-raygun) 📇 ☁️ - Raygun API V3 integration for crash reporting and real user monitoring
- [metoro-io/metoro-mcp-server](https://github.com/metoro-io/metoro-mcp-server) 🎖️ 🏎️ ☁️ - Query and interact with kubernetes environments monitored by Metoro
- [grafana/mcp-grafana](https://github.com/grafana/mcp-grafana) 🎖️ 🐍 🏠 ☁️ - Search dashboards, investigate incidents and query datasources in your Grafana instance
- [pydantic/logfire-mcp](https://github.com/pydantic/logfire-mcp) 🎖️ 🐍 ☁️ - Provides access to OpenTelemetry traces and metrics through Logfire
- [seekrays/mcp-monitor](https://github.com/seekrays/mcp-monitor) 🏎️ 🏠 - A system monitoring tool that exposes system metrics via the Model Context Protocol (MCP). This tool allows LLMs to retrieve real-time system information through an MCP-compatible interface.（support CPU、Memory、Disk、Network、Host、Process）
- [hyperb1iss/lucidity-mcp](https://github.com/hyperb1iss/lucidity-mcp) 🐍 🏠 - Enhance AI-generated code quality through intelligent, prompt-based analysis across 10 critical dimensions from complexity to security vulnerabilities

### 🔎 <a name="search"></a>Search

- [@modelcontextprotocol/server-brave-search](https://github.com/modelcontextprotocol/servers/tree/main/src/brave-search) 📇 ☁️ - Web search capabilities using Brave's Search API
- [@angheljf/nyt](https://github.com/angheljf/nyt) 📇 ☁️ - Search articles using the NYTimes API
- [@modelcontextprotocol/server-fetch](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch) 🐍 🏠 ☁️ - Efficient web content fetching and processing for AI consumption
- [ac3xx/mcp-servers-kagi](https://github.com/ac3xx/mcp-servers-kagi) 📇 ☁️ - Kagi search API integration
- [exa-labs/exa-mcp-server](https://github.com/exa-labs/exa-mcp-server) 🎖️ 📇 ☁️ – A Model Context Protocol (MCP) server lets AI assistants like Claude use the Exa AI Search API for web searches. This setup allows AI models to get real-time web information in a safe and controlled way.
- [fatwang2/search1api-mcp](https://github.com/fatwang2/search1api-mcp) 📇 ☁️ - Search via search1api (requires paid API key)
- [Tomatio13/mcp-server-tavily](https://github.com/Tomatio13/mcp-server-tavily) ☁️ 🐍 – Tavily AI search API
- [kshern/mcp-tavily](https://github.com/kshern/mcp-tavily.git) ☁️ 📇 – Tavily AI search API
- [blazickjp/arxiv-mcp-server](https://github.com/blazickjp/arxiv-mcp-server) ☁️ 🐍 - Search ArXiv research papers
- [mzxrai/mcp-webresearch](https://github.com/mzxrai/mcp-webresearch) 🔍📚 - Search Google and do deep web research on any topic
- [andybrandt/mcp-simple-arxiv](https://github.com/andybrandt/mcp-simple-arxiv) - 🐍 ☁️  MCP for LLM to search and read papers from arXiv
- [andybrandt/mcp-simple-pubmed](https://github.com/andybrandt/mcp-simple-pubmed) - 🐍 ☁️  MCP to search and read medical / life sciences papers from PubMed.
- [apify/mcp-server-rag-web-browser](https://github.com/apify/mcp-server-rag-web-browser) 📇 ☁️ - An MCP server for Apify's open-source RAG Web Browser Actor to perform web searches, scrape URLs, and return content in Markdown.
- [SecretiveShell/MCP-searxng](https://github.com/SecretiveShell/MCP-searxng) 🐍 🏠 - An MCP Server to connect to searXNG instances
- [Bigsy/Clojars-MCP-Server](https://github.com/Bigsy/Clojars-MCP-Server) 📇 ☁️ - Clojars MCP Server for upto date dependency information of Clojure libraries
- [Ihor-Sokoliuk/MCP-SearXNG](https://github.com/ihor-sokoliuk/mcp-searxng) 📇 🏠/☁️ - A Model Context Protocol Server for [SearXNG](https://docs.searxng.org)
- [erithwik/mcp-hn](https://github.com/erithwik/mcp-hn) 🐍 ☁️ - An MCP server to search Hacker News, get top stories, and more.
- [chanmeng/google-news-mcp-server](https://github.com/ChanMeng666/server-google-news) 📇 ☁️ - Google News integration with automatic topic categorization, multi-language support, and comprehensive search capabilities including headlines, stories, and related topics through [SerpAPI](https://serpapi.com/).
- [devflowinc/trieve](https://github.com/devflowinc/trieve/tree/main/clients/mcp-server) 🎖️ 📇 ☁️ 🏠 - Crawl, embed, chunk, search, and retrieve information from datasets through [Trieve](https://trieve.ai)
- [nickclyde/duckduckgo-mcp-server](https://github.com/nickclyde/duckduckgo-mcp-server) 🐍 ☁️ - Web search using DuckDuckGo
- [zhsama/duckduckgo-mcp-server](https://github.com/zhsama/duckduckgo-mpc-server/) 📇 🏠 ☁️ - This is a TypeScript-based MCP server that provides DuckDuckGo search functionality.
- [vectorize-io/vectorize-mcp-server](https://github.com/vectorize-io/vectorize-mcp-server/) ☁️ 📇 - [Vectorize](https://vectorize.io) MCP server for advanced retrieval, Private Deep Research, Anything-to-Markdown file extraction and text chunking.
- [jae-jae/fetcher-mcp](https://github.com/jae-jae/fetcher-mcp) 📇 🏠 - MCP server for fetching web page content using Playwright headless browser, supporting Javascript rendering and intelligent content extraction, and outputting Markdown or HTML format.

### 🔒 <a name="security"></a>Security

- [dnstwist MCP Server](https://github.com/BurtTheCoder/mcp-dnstwist) 📇🪟☁️ - MCP server for dnstwist, a powerful DNS fuzzing tool that helps detect typosquatting, phishing, and corporate espionage.
- [Maigret MCP Server](https://github.com/BurtTheCoder/mcp-maigret) 📇🪟☁️ - MCP server for maigret, a powerful OSINT tool that collects user account information from various public sources. This server provides tools for searching usernames across social networks and analyzing URLs.
- [Shodan MCP Server](https://github.com/BurtTheCoder/mcp-shodan) 📇🪟☁️ - MCP server for querying the Shodan API and Shodan CVEDB. This server provides tools for IP lookups, device searches, DNS lookups, vulnerability queries, CPE lookups, and more.
- [VirusTotal MCP Server](https://github.com/BurtTheCoder/mcp-virustotal) 📇🪟☁️ - MCP server for querying the VirusTotal API. This server provides tools for scanning URLs, analyzing file hashes, and retrieving IP address reports.
- [ORKL MCP Server](https://github.com/fr0gger/MCP_Security) 📇🛡️☁️ - MCP server for querying the ORKL API. This server provides tools for fetching threat reports, analyzing threat actors, and retrieving intelligence sources.
- [Security Audit MCP Server](https://github.com/qianniuspace/mcp-security-audit) 📇🛡️☁️ A powerful MCP (Model Context Protocol) Server that audits npm package dependencies for security vulnerabilities. Built with remote npm registry integration for real-time security checks.

### 🏃 <a name="sports"></a>Sports

Tools for accessing sports-related data, results, and statistics.

- [r-huijts/firstcycling-mcp](https://github.com/r-huijts/firstcycling-mcp) 📇 ☁️ - Access cycling race data, results, and statistics through natural language. Features include retrieving start lists, race results, and rider information from firstcycling.com.

### 🚆 <a name="travel-and-transportation"></a>Travel & Transportation

Access to travel and transportation information. Enables querying schedules, routes, and real-time travel data.

- [Airbnb MCP Server](https://github.com/openbnb-org/mcp-server-airbnb) 📇 ☁️ - Provides tools to search Airbnb and get listing details.
- [NS Travel Information MCP Server](https://github.com/r-huijts/ns-mcp-server) 📇 ☁️ - Access Dutch Railways (NS) travel information, schedules, and real-time updates
- [KyrieTangSheng/mcp-server-nationalparks](https://github.com/KyrieTangSheng/mcp-server-nationalparks) 📇 ☁️ - National Park Service API integration providing latest information of park details, alerts, visitor centers, campgrounds, and events for U.S. National Parks
- [pab1it0/tripadvisor-mcp](https://github.com/pab1it0/tripadvisor-mcp) 📇 🐍 - A MCP server that enables LLMs to interact with Tripadvisor API, supporting location data, reviews, and photos through standardized MCP interfaces

### 🔄 <a name="version-control"></a>Version Control

Interact with Git repositories and version control platforms. Enables repository management, code analysis, pull request handling, issue tracking, and other version control operations through standardized APIs.

- [@modelcontextprotocol/server-github](https://github.com/modelcontextprotocol/servers/tree/main/src/github) 📇 ☁️ - GitHub API integration for repository management, PRs, issues, and more
- [@modelcontextprotocol/server-gitlab](https://github.com/modelcontextprotocol/servers/tree/main/src/gitlab) 📇 ☁️ 🏠 - GitLab platform integration for project management and CI/CD operations
- [@oschina/mcp-gitee](https://github.com/oschina/gitee) 🏎️ ☁️ 🏠 - Gitee API integration, repository, issue, and pull request management, and more.
- [@modelcontextprotocol/server-git](https://github.com/modelcontextprotocol/servers/tree/main/src/git) 🐍 🏠 - Direct Git repository operations including reading, searching, and analyzing local repositories
- [adhikasp/mcp-git-ingest](https://github.com/adhikasp/mcp-git-ingest) 🐍 🏠 - Read and analyze GitHub repositories with your LLM

### 🛠️ <a name="other-tools-and-integrations"></a>Other Tools and Integrations

- [apify/actors-mcp-server](https://github.com/apify/actors-mcp-server) 📇 ☁️ - Use 3,000+ pre-built cloud tools, known as Actors, to extract data from websites, e-commerce, social media, search engines, maps, and more
- [ivo-toby/contentful-mcp](https://github.com/ivo-toby/contentful-mcp) 📇 🏠 - Update, create, delete content, content-models and assets in your Contentful Space
- [mzxrai/mcp-openai](https://github.com/mzxrai/mcp-openai) 📇 ☁️ - Chat with OpenAI's smartest models
- [mrjoshuak/godoc-mcp](https://github.com/mrjoshuak/godoc-mcp) 🏎️ 🏠 - Token-efficient Go documentation server that provides AI assistants with smart access to package docs and types without reading entire source files
- [pierrebrunelle/mcp-server-openai](https://github.com/pierrebrunelle/mcp-server-openai) 🐍 ☁️ - Query OpenAI models directly from Claude using MCP protocol
- [@modelcontextprotocol/server-everything](https://github.com/modelcontextprotocol/servers/tree/main/src/everything) 📇 🏠 - MCP server that exercises all the features of the MCP protocol
- [baba786/phabricator-mcp-server](https://github.com/baba786/phabricator-mcp-server) 🐍 ☁️ - Interacting with Phabricator API
- [MarkusPfundstein/mcp-obsidian](https://github.com/MarkusPfundstein/mcp-obsidian) 🐍 ☁️ 🏠 - Interacting with Obsidian via REST API
- [calclavia/mcp-obsidian](https://github.com/calclavia/mcp-obsidian) 📇 🏠 - This is a connector to allow Claude Desktop (or any MCP client) to read and search any directory containing Markdown notes (such as an Obsidian vault).
- [anaisbetts/mcp-youtube](https://github.com/anaisbetts/mcp-youtube) 📇 ☁️ - Fetch YouTube subtitles
- [Seym0n/tiktok-mcp](https://github.com/Seym0n/tiktok-mcp) 📇 ☁️ - Interact with TikTok videos
- [danhilse/notion_mcp](https://github.com/danhilse/notion_mcp) 🐍 ☁️ - Integrates with Notion's API to manage personal todo lists
- [rusiaaman/wcgw](https://github.com/rusiaaman/wcgw/blob/main/src/wcgw/client/mcp_server/Readme.md) 🐍 🏠 - Autonomous shell execution, computer control and coding agent. (Mac)
- [reeeeemo/ancestry-mcp](https://github.com/reeeeemo/ancestry-mcp) 🐍 🏠 - Allows the AI to read .ged files and genetic data
- [sirmews/apple-notes-mcp](https://github.com/sirmews/apple-notes-mcp) 🐍 🏠 - Allows the AI to read from your local Apple Notes database (macOS only)
- [anjor/coinmarket-mcp-server](https://github.com/anjor/coinmarket-mcp-server) 🐍 🏠 - Coinmarket API integration to fetch cryptocurrency listings and quotes
- [suekou/mcp-notion-server](https://github.com/suekou/mcp-notion-server) 📇 🏠 - Interacting with Notion API
- [amidabuddha/unichat-mcp-server](https://github.com/amidabuddha/unichat-mcp-server) 🐍/📇 ☁️ - Send requests to OpenAI, MistralAI, Anthropic, xAI, Google AI or DeepSeek using MCP protocol via tool or predefined prompts. Vendor API key required
- [evalstate/mcp-miro](https://github.com/evalstate/mcp-miro) 📇 ☁️ - Access MIRO whiteboards, bulk create and read items. Requires OAUTH key for REST API.
- [@tacticlaunch/mcp-linear](https://github.com/tacticlaunch/mcp-linear) 📇 ☁️ 🍎 🪟 🐧 - Integrates with Linear project management system
- [KS-GEN-AI/jira-mcp-server](https://github.com/KS-GEN-AI/jira-mcp-server) 📇 ☁️ 🍎 🪟 - Read jira data via JQL and api and execute requests to create and edit tickets.
- [KS-GEN-AI/confluence-mcp-server](https://github.com/KS-GEN-AI/confluence-mcp-server) 📇 ☁️ 🍎 🪟 - Get Confluence data via CQL and read pages.
- [sooperset/mcp-atlassian](https://github.com/sooperset/mcp-atlassian) 🐍 ☁️ - MCP server for Atlassian products (Confluence and Jira). Supports Confluence Cloud, Jira Cloud, and Jira Server/Data Center. Provides comprehensive tools for searching, reading, creating, and managing content across Atlassian workspaces.
- [pyroprompts/any-chat-completions-mcp](https://github.com/pyroprompts/any-chat-completions-mcp) - Chat with any other OpenAI SDK Compatible Chat Completions API, like Perplexity, Groq, xAI and more
- [anaisbetts/mcp-installer](https://github.com/anaisbetts/mcp-installer) 🐍 🏠 -  An MCP server that installs other MCP servers for you.
- [tanigami/mcp-server-perplexity](https://github.com/tanigami/mcp-server-perplexity) 🐍 ☁️ - Interacting with Perplexity API.
- [future-audiences/wikimedia-enterprise-model-context-protocol](https://gitlab.wikimedia.org/repos/future-audiences/wikimedia-enterprise-model-context-protocol) 🐍 ☁️  - Wikipedia Article lookup API
- [andybrandt/mcp-simple-timeserver](https://github.com/andybrandt/mcp-simple-timeserver) 🐍 🏠☁️ - An MCP server that allows checking local time on the client machine or current UTC time from an NTP server
- [andybrandt/mcp-simple-openai-assistant](https://github.com/andybrandt/mcp-simple-openai-assistant) - 🐍 ☁️  MCP to talk to OpenAI assistants (Claude can use any GPT model as his assitant)
- [@llmindset/mcp-hfspace](https://github.com/evalstate/mcp-hfspace) 📇 ☁️ - Use HuggingFace Spaces directly from Claude. Use Open Source Image Generation, Chat, Vision tasks and more. Supports Image, Audio and text uploads/downloads.
- [zueai/mcp-manager](https://github.com/zueai/mcp-manager) 📇 ☁️ - Simple Web UI to install and manage MCP servers for Claude Desktop App.
- [wong2/mcp-cli](https://github.com/wong2/mcp-cli) 📇 🏠 - CLI tool for testing MCP servers
- [chrishayuk/mcp-cli](https://github.com/chrishayuk/mcp-cli) 🐍 🏠 - Yet another CLI tool for testing MCP servers
- [isaacwasserman/mcp-vegalite-server](https://github.com/isaacwasserman/mcp-vegalite-server) 🐍 🏠 - Generate visualizations from fetched data using the VegaLite format and renderer.
- [tevonsb/homeassistant-mcp](https://github.com/tevonsb/homeassistant-mcp) 📇 🏠 - Access Home Assistant data and control devices (lights, switches, thermostats, etc).
- [allenporter/mcp-server-home-assistant](https://github.com/allenporter/mcp-server-home-assistant) 🐍 🏠 - Expose all Home Assistant voice intents through a Model Context Protocol Server allowing home control.
- [@magarcia/mcp-server-giphy](https://github.com/magarcia/mcp-server-giphy) 📇 ☁️ - Search and retrieve GIFs from Giphy's vast library through the Giphy API.
- [nguyenvanduocit/all-in-one-model-context-protocol](https://github.com/nguyenvanduocit/all-in-one-model-context-protocol) 🏎️ 🏠 - Some useful tools for developer, almost everything an engineer need: confluence, Jira, Youtube, run script, knowledge base RAG, fetch URL, Manage youtube channel, emails, calendar, gitlab
- [@joshuarileydev/mac-apps-launcher-mcp-server](https://github.com/JoshuaRileyDev/mac-apps-launcher) 📇 🏠 - An MCP server to list and launch applications on MacOS
- [ZeparHyfar/mcp-datetime](https://github.com/ZeparHyfar/mcp-datetime) - MCP server providing date and time functions in various formats
- [SecretiveShell/MCP-wolfram-alpha](https://github.com/SecretiveShell/MCP-wolfram-alpha) 🐍 ☁️ - An MCP server for querying wolfram alpha API.
- [Amazon Bedrock Nova Canvas](https://github.com/zxkane/mcp-server-amazon-bedrock) 📇 ☁️ - Use Amazon Nova Canvas model for image generation.
- [apinetwork/piapi-mcp-server](https://github.com/apinetwork/piapi-mcp-server) 📇 ☁️ PiAPI MCP server makes user able to generate media content with Midjourney/Flux/Kling/Hunyuan/Udio/Trellis directly from Claude or any other MCP-compatible apps.
- [gotoolkits/DifyWorkflow](https://github.com/gotoolkits/mcp-difyworkflow-server) - 🏎️ ☁️ Tools to the query and execute of Dify workflows
- [@pskill9/hn-server](https://github.com/pskill9/hn-server) - 📇 ☁️ Parses the HTML content from news.ycombinator.com (Hacker News) and provides structured data for different types of stories (top, new, ask, show, jobs).
- [@mediar-ai/screenpipe](https://github.com/mediar-ai/screenpipe) - 🎖️ 🦀 🏠 🍎 Local-first system capturing screen/audio with timestamped indexing, SQL/embedding storage, semantic search, LLM-powered history analysis, and event-triggered actions - enables building context-aware AI agents through a NextJS plugin ecosystem.
- [akseyh/bear-mcp-server](https://github.com/akseyh/bear-mcp-server) - Allows the AI to read from your Bear Notes (macOS only)
- [mcp-server-jfx](https://github.com/quarkiverse/quarkus-mcp-servers/tree/main/jfx) ☕ 🏠 - Draw on JavaFX canvas.
- [hmk/attio-mcp-server](https://github.com/hmk/attio-mcp-server) - 📇 ☁️ Allows AI clients to manage records and notes in Attio CRM
- [roychri/mcp-server-asana](https://github.com/roychri/mcp-server-asana) - 📇 ☁️ This Model Context Protocol server implementation of Asana allows you to talk to Asana API from MCP Client such as Anthropic's Claude Desktop Application, and many more.
- [ws-mcp](https://github.com/nick1udwig/ws-mcp) - Wrap MCP servers with a WebSocket (for use with [kitbitz](https://github.com/nick1udwig/kibitz))
- [AbdelStark/bitcoin-mcp](https://github.com/AbdelStark/bitcoin-mcp) - ₿ A Model Context Protocol (MCP) server that enables AI models to interact with Bitcoin, allowing them to generate keys, validate addresses, decode transactions, query the blockchain, and more.
- [tomekkorbak/strava-mcp-server](https://github.com/tomekkorbak/strava-mcp-server) 🐍 ☁️ - An MCP server for Strava, an app for tracking physical exercise
- [tomekkorbak/oura-mcp-server](https://github.com/tomekkorbak/oura-mcp-server) 🐍 ☁️ - An MCP server for Oura, an app for tracking sleep
- [rember/rember-mcp](https://github.com/rember/rember-mcp) 📇 🏠 - Create spaced repetition flashcards in [Rember](https://rember.com) to remember anything you learn in your chats.
- [hiromitsusasaki/raindrop-io-mcp-server](https://github.com/hiromitsusasaki/raindrop-io-mcp-server) 📇 ☁️ - An integration that allows LLMs to interact with Raindrop.io bookmarks using the Model Context Protocol (MCP).
- [@makehq/mcp-server](https://github.com/integromat/make-mcp-server) 🎖️ 📇 🏠 - Turn your [Make](https://www.make.com/) scenarios into callable tools for AI assistants.
- [NON906/omniparser-autogui-mcp](https://github.com/NON906/omniparser-autogui-mcp) - 🐍 Automatic operation of on-screen GUI.
- [kj455/mcp-kibela](https://github.com/kj455/mcp-kibela) - 📇 ☁️ Allows AI models to interact with [Kibela](https://kibe.la/)
- [blurrah/mcp-graphql](https://github.com/blurrah/mcp-graphql) 📇 ☁️ - Allows the AI to query GraphQL servers
- [@awkoy/replicate-flux-mcp](https://github.com/awkoy/replicate-flux-mcp) 📇 ☁️ - Provides the ability to generate images via Replicate's API.
- [kenliao94/mcp-server-rabbitmq](https://github.com/kenliao94/mcp-server-rabbitmq) 🐍 🏠 - Enable interaction (admin operation, message enqueue/dequeue) with RabbitMQ
- [marcelmarais/Spotify](https://github.com/marcelmarais/spotify-mcp-server) - 📇 🏠 Control Spotify playback and manage playlists.
- [NakaokaRei/swift-mcp-gui](https://github.com/NakaokaRei/swift-mcp-gui.git) 🏠 🍎 - MCP server that can execute commands such as keyboard input and mouse movement
- [awwaiid/mcp-server-taskwarrior](https://github.com/awwaiid/mcp-server-taskwarrior) 🏠 📇 - An MCP server for basic local taskwarrior usage (add, update, remove tasks)

## Frameworks

- [FastMCP](https://github.com/jlowin/fastmcp) 🐍 - A high-level framework for building MCP servers in Python
- [FastMCP](https://github.com/punkpeye/fastmcp) 📇 - A high-level framework for building MCP servers in TypeScript
- [Foxy Contexts](https://github.com/strowk/foxy-contexts) 🏎️ - Golang library to write MCP Servers declaratively with functional testing included
- [Genkit MCP](https://github.com/firebase/genkit/tree/main/js/plugins/mcp) 📇 – Provides integration between [Genkit](https://github.com/firebase/genkit/tree/main) and the Model Context Protocol (MCP).
- [LiteMCP](https://github.com/wong2/litemcp) 📇 - A high-level framework for building MCP servers in JavaScript/TypeScript
- [mark3labs/mcp-go](https://github.com/mark3labs/mcp-go) 🏎️ - Golang SDK for building MCP Servers and Clients.
- [mcp-framework](https://github.com/QuantGeekDev/mcp-framework) 📇 - Fast and elegant TypeScript framework for building MCP servers
- [mcp-proxy](https://github.com/punkpeye/mcp-proxy) - 📇 A TypeScript SSE proxy for MCP servers that use `stdio` transport.
- [mcp-rs-template](https://github.com/linux-china/mcp-rs-template) 🦀 - MCP CLI server template for Rust
- [metoro-io/mcp-golang](https://github.com/metoro-io/mcp-golang) 🏎️ - Golang framework for building MCP Servers, focussed on type safety
- [rectalogic/langchain-mcp](https://github.com/rectalogic/langchain-mcp) 🐍 - Provides MCP tool calling support in LangChain, allowing for the integration of MCP tools into LangChain workflows.
- [salty-flower/ModelContextProtocol.NET](https://github.com/salty-flower/ModelContextProtocol.NET) #️⃣ 🏠 - A C# SDK for building MCP servers on .NET 9 with NativeAOT compatibility ⚡ 🔌
- [spring-projects-experimental/spring-ai-mcp](https://github.com/spring-projects-experimental/spring-ai-mcp) ☕ 🌱 - Java SDK and Spring Framework integration for building MCP client and MCP servers with various, plugable, transport options.
- [@marimo-team/codemirror-mcp](https://github.com/marimo-team/codemirror-mcp) - CodeMirror extension that implements the Model Context Protocol (MCP) for resource mentions and prompt commands.
- [quarkiverse/quarkus-mcp-server](https://github.com/quarkiverse/quarkus-mcp-server) ☕ - Java SDK for building MCP servers using Quarkus.
- [lastmile-ai/mcp-agent](https://github.com/lastmile-ai/mcp-agent) 🤖 🔌 - Build effective agents with MCP servers using simple, composable patterns.
- [mullerhai/sakura-mcp](https://github.com/mullerhai/sakura-mcp) 🦀 ☕ - Scala MCP Framework for Build effective agents with MCP servers and MCP clients shade from modelcontextprotocol.io.
  
## Utilities

- [boilingdata/mcp-server-and-gw](https://github.com/boilingdata/mcp-server-and-gw) 📇 - An MCP stdio to HTTP SSE transport gateway with example server and MCP client.
- [isaacwasserman/mcp-langchain-ts-client](https://github.com/isaacwasserman/mcp-langchain-ts-client) 📇 – Use MCP provided tools in LangChain.js
- [lightconetech/mcp-gateway](https://github.com/lightconetech/mcp-gateway) 📇 - A gateway demo for MCP SSE Server.
- [mark3labs/mcphost](https://github.com/mark3labs/mcphost) 🏎️ -  A CLI host application that enables Large Language Models (LLMs) to interact with external tools through the Model Context Protocol (MCP).
- [MCP-Connect](https://github.com/EvalsOne/MCP-Connect) 📇 - A tiny tool that enables cloud-based AI services to access local Stdio based MCP servers by HTTP/HTTPS requests.
- [SecretiveShell/MCP-Bridge](https://github.com/SecretiveShell/MCP-Bridge) 🐍 – an openAI middleware proxy to use mcp in any existing openAI compatible client
- [sparfenyuk/mcp-proxy](https://github.com/sparfenyuk/mcp-proxy) 🐍 – An MCP stdio to SSE transport gateawy.
- [upsonic/gpt-computer-assistant](https://github.com/Upsonic/gpt-computer-assistant) 🐍 – framework to build vertical AI agent
- [kukapay/whereami-mcp](https://github.com/kukapay/whereami-mcp) 🐍 ☁️ -  A lightweight mcp server that tells you exactly where you are based on your current IP.
- [kukapay/whattimeisit-mcp](https://github.com/kukapay/whattimeisit-mcp) 🐍 ☁️ - A lightweight mcp server that tells you exactly what time is it.
- [kukapay/whoami-mcp](https://github.com/kukapay/whoami-mcp) 🐍 🏠 - A lightweight MCP server that tells you exactly who you are.
- [flux159/mcp-chat](https://github.com/flux159/mcp-chat) 📇🖥️ - A CLI based client to chat and connect with any MCP server. Useful during development & testing of MCP servers.
- [TBXark/mcp-proxy](https://github.com/TBXark/mcp-proxy) 🏎️ - An MCP proxy server that aggregates and serves multiple MCP resource servers through a single http server.


## Tips and Tricks

### Official prompt to inform LLMs how to use MCP

Want to ask Claude about Model Context Protocol?

Create a Project, then add this file to it:

https://modelcontextprotocol.io/llms-full.txt

Now Claude can answer questions about writing MCP servers and how they work

- https://www.reddit.com/r/ClaudeAI/comments/1h3g01r/want_to_ask_claude_about_model_context_protocol/

## Star History

<a href="https://star-history.com/#punkpeye/awesome-mcp-servers&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=punkpeye/awesome-mcp-servers&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=punkpeye/awesome-mcp-servers&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=punkpeye/awesome-mcp-servers&type=Date" />
 </picture>
</a>
