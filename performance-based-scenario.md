---
title: "Sample Scenario"
---

### Your Environment 

`HashiCorp Vault cluster`

- IP address: `127.0.0.1:8200`
- Token: `s.f7Ea3C3ojOYE0GRLzmhSG`

`scenario-node-appserver`

- Server address: `<IP_Address>`
- Vault Agent configuration file: `/etc/vault/agent7.hcl`
- Sink location: `/etc/vault/token.json`

### Instructions

You have an application that needs to retrieve credentials from Vault, even though the application was **not** architected to interact directly with Vault. You need to securely configure Vault Agent Auto-Auth and token sink. 

The `approle/` path has an `AppRole` auth method with the following properties:
- Role name: `appy7`
- Vault policy: `policy7`
- RoleID: `xxxxxxxx-xxxxxxxx-xxxxxxxx-xxxxxxxxxxx`

Use the information provided to:
1. Configure the application server to use the Vault Agent to retrieve a Vault token. 
    - The Vault Agent should use AppRole for authentication.
    - Keep the token renewed automatically. 
2. Use response-wrapping on the Auth method to protect the resulting token from Vault. 
3. Write the token to the sink location. 

### Important Notes

-	You can validate the configuration by viewing the contents of the sink. If a token does **not** exist, the configuration is **not** correct.
-	`$PATH` includes the Vault binary.
