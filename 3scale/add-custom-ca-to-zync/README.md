# Add custom ca to Zync

Adds a custom CA file to Zync truststore. This enables Zync to trust a local CA for SSO integrations.

Based on [instructions in the 3scale documentation](https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.10/html/administering_the_api_gateway/openid-connect#configuring-zync_integration-threescale-sso).

## Running the playbook

`ansible-playbook add-custom-ca-to-zync.yaml -i inventory/example.inventory`

## Configuration

See [example.inventory](inventory/example.inventory) for details.

## Dependencies

- oc client
- user logged in with oc client
