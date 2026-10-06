# meatsack-marketplace

Source registry: `plugins.json`. Generated packages in `plugins/`, client marketplace catalogs, and `plugins.lock.json` must only be updated with `npm run sync`. Never edit generated outputs by hand.

Product plugin manifests, skills, MCP configuration, and logos belong in the product repositories. Sync copies only the explicit allowlist and never runs product code. Validate with `npm run validate` and `claude plugin validate .`.

Do not commit, push, create a branch, or open a pull request unless explicitly asked. Preserve unrelated changes. Never package secrets or application source.
