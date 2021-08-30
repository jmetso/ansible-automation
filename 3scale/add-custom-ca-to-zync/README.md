# Add custom ca to zync

Adds a custom CA file to zync CA. This enables Zync to trust a local CA for SSO integrations.

## Running the playbook

    ansible-playbook add-custom-ca-to-zync.yaml -i inventory/example.inventory

## Configuration

See [example.inventory](inventory/example.inventory) for details.

## Dependencies

- oc client
- user logged in with oc client
