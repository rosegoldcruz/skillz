# Unified Skills Collection

92 skills from all five uploaded files, plus one starter template.

## Folder layout

- `skills/`: one folder per skill, with its original SKILL.md and all bundled resources.
- `templates/`: the original starter template, separated from usable skills.
- `sources/`: all original source packages, preserving licenses, notices, hooks, setup files, tests, shared resources, and upstream documentation.
- `INDEX.md`: searchable list with links to every skill.
- `manifest.json`: source mapping and content checksums.

## Usage

Extract this ZIP first. Select the skill folders needed for the target agent and follow that agent's installation method. This is a portable collection; it does not install or activate skills automatically. Original instructions and resources are unchanged. Some skills expect a particular agent, plugin, external tool, or source repository layout; consult the original packages in `sources/` for setup and shared dependencies. Avoid activating the whole collection blindly: several workflows overlap.

## Two prototype variants

Both source collections include a different skill whose internal name is `prototype`. Their folders are `skills/prototype-matt-pocock/` and `skills/prototype-emil-kowalski/`. Both are preserved without editing their metadata. Choose one when an agent requires globally unique skill names; a folder suffix alone does not resolve an internal-name collision.

## Integrity

All skill files were verified byte-for-byte against their inputs, and source archives are retained unchanged. Only identical complete skill folders would be deduplicated; none were found. No skill scripts or installers were executed. Packaging integrity was checked; skill behavior and runtime compatibility were not tested.
