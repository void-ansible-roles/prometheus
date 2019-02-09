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
      jobs: # List of jobs
        - name: # Job name
          targets: # List of targets
            - host # Host for the scrape
            - port # Port for the scrape

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
