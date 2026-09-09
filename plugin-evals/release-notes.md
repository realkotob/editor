# OpenAI submission release notes

Initial skills-only submission of Pascal agent skills 0.1.5.

The plugin teaches ChatGPT and Codex to create, inspect, edit, validate, save, and hand off editable Pascal 3D scenes through a separately connected Pascal MCP server. It also includes a focused furniture-fit workflow that reports measured footprint evidence, unsupported checks, and one bounded next action without authorizing project changes or spending.

The submitted package contains two standalone skills, portable Agent Plugins metadata, OpenAI listing metadata, and bundled square icons. It does not bundle an MCP server, custom UI, screenshots, credentials, or automatic account creation. Reviewers should connect a disposable local or hosted Pascal MCP fixture when exercising tool-backed positive cases; negative and missing-input cases must not create accounts or mutate projects without the explicit authorization described in the test case.
