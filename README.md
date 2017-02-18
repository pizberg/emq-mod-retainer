emq_mod_retainer
================

Retainer Module (v2.0.7)

Configuration
-------------

etc/emq_mod_retainer.conf:

```
## disc: disc_copies, ram: ram_copies
## Notice: retainer's storage_type on each node in a cluster must be the same!
module.retainer.storage_type = disc

## Max number of retained messages
module.retainer.max_message_num = 100000

## Max Payload Size of retained message
module.retainer.max_payload_size = 64KB

## Expired after seconds, never expired if 0
module.retainer.expired_after = 0
```

License
-------

Apache License Version 2.0

Author
------

feng at emqtt.io

