---
layout: main
title: Storage::SCP
---

Storage::SCP
============

``` rb
store_with SCP do |server|
  server.username = 'my_username'
  server.password = 'my_password'
  server.ip       = '123.45.678.90'
  server.port     = 22
  server.path     = '~/backups/'
  server.keep     = 5

  # Additional options for the SSH connection.
  # server.ssh_options = {}
end
```

{% include markdown_links %}