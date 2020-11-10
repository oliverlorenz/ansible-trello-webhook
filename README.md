# Trello Webhook

Creates a webhook for trello

## Role Variables

| name        | description         |
|-------------|---------------------|
| key         | Trello Api Key      |
| token       | Trello Token        |
| callbackURL | Callback url to set |
| idModel     | model to observe    |


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: trello-webhook
           vars:
             key: XXX 
