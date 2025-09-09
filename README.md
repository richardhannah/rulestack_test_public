# RuleStack Registry

This is a RuleStack package registry initialized with the rfh CLI.

## Structure

- `packages/` - Contains all published packages
- `index.json` - Registry index with package metadata

## Usage

To publish packages to this registry:

1. Add this registry to your rfh configuration
2. Set it as your active registry
3. Use `rfh pack` to create package archives
4. Use `rfh publish` to publish packages

For more information, visit: https://github.com/richardhannah/rfh
