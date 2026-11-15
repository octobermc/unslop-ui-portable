# unslop-ui-portable

Cursor plugin with one skill, `unslop-ui`: a portable adaptation of Damir Sokolovsky's [unslop](https://github.com/heydamir/unslop) UI skill. It is the only plugin listed by this repository marketplace at `.cursor-plugin/marketplace.json`.

This is not the separate writing skill named `unslop`. The name is `unslop-ui` to avoid that collision.

Source review commit of heydamir/unslop: `620163eedb3529d9cd23a3994ed8d287d06f760d`. Licensed under [CC BY 4.0](LICENSE). Credit Damir Sokolovsky ([@heydamir](https://x.com/heydamir)) and link back to the original repository.

The skill keeps the original screenshot and story-video scripts (`skills/unslop-ui/scripts/`). Snapshotting a live page or rendering a story video needs Playwright and Chromium in the project, and story videos also need ffmpeg. This repository has no hooks, rules, agents, commands, MCP configuration, or installer scripts. It does not include the Claude Code marketplace installer.

Install it from the marketplace entry whose `source` is `cursor-plugins/unslop-ui-portable`.

Paid image generation, if an image tool is already available, still requires showing the prompt and waiting for agreement before running.
