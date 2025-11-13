# packages

This directory is reserved for Home Assistant package-style configuration files (one file per integration/area).

Place YAML files here and include them from configuration.yaml using the `packages:` directive or via `!include_dir_merge_named packages`.

Example: create a file `packages/lights.yaml` to define grouped light automations.
