prometheus
==========


What is does this role do?
--------------------------

This role installs and configures prometheus to scrape a static target
set.

Meta
----

Files Managed:
  * None

Defaults Provided:
  * None

Variables Required:
  * prometheus: # prometheus config variable
    frules: # List of outbound firewall rules to establish
      - host: # Host to allow
        port: # Port to allow
    cfg: # Valid prometheus configuration structure

Optional Variables:
  * None

Files Required:
  * None

Optional Files:
  * None

Conflicting Roles:
  * None

Depends On:
  * None
