# setup-engines (v0)

setup "engines" of `package.json` for node

## usage

use this on actions (`.github/workflows/*.yml`) before use node commands in actions: `uses: Nanai10a/setup-engines@v1`.

## limitation

read `.engines` from `<repo root>/package.json` only, however this doesn't read `package.json` in other directory.  
in future, read and validate: check `package.json` of all in repo, and solve version of node to matches all requirings.
