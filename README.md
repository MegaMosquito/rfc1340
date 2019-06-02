# rfc1340

This code enables access to the port numbers, keywords and descriptions
of the well-known and IANA reserved TCP and UDP ports from RFC1340.

### Usage:

Import the dictionaries of TCP and/or UDP port numbers with these:

```
from rfc1340.known_tcp_ports import known_tcp_ports
from rfc1340.known_udp_ports import known_udp_ports
```

Then you can look up port numbers (they are the keys) to get "keyword" and "description" as listed in rfc1340.

See known_tcp_ports.py and known_udp_ports.py for more info.

Here are samples of both dictionaries:

### TCP Ports

```
  2000: { "keyword": "callbook", "description": "" },
  2001: { "keyword": "dc", "description": "" },
  2002: { "keyword": "globe", "description": "" },
  2004: { "keyword": "mailbox", "description": "" },
  2005: { "keyword": "berknet", "description": "" },
  2006: { "keyword": "invokator", "description": "" },
  ...
```

### UDP Ports

```
  2000: { "keyword": "callbook", "description": "" },
  2001: { "keyword": "wizard", "description": "curry" },
  2002: { "keyword": "globe", "description": "" },
  2004: { "keyword": "emce", "description": "CCWS mm conf" },
  2005: { "keyword": "oracle", "description": "" },
  2006: { "keyword": "raid-cc", "description": "raid" },
  ...
```

Written by Glen Darling, May 2019.

