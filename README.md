# save_money_on_aws

Enforce tagging on instances
    * Owner: owner_name
    * Project: project_name
    * Name: instance_name

**Save money on AWS by terminating orphaned/forgotten instances left ON**

Use case 1: 
    Bespoke AWS instances manually created for a one-off project, 
    usually to test something, 
    then instances were forgotten about and left running.
    We require everyone to tag their instances with owner:person.
    This create an eazy way to audit who is accountable for billing.

Use case 2:
    CI instances spun up to test changes programmatically for every pull request,
    sometimes hit a corner where not everything is deprovisionned correctly.


