# HTTP Status Probe

A simple HTTP Status Probe written in C.

Compile:

```bash
❯ gcc -std=c11 -Wall -Wextra -O2 -o http-status-probe http-status-probe.c
```

Usage:

```bash
> ./http-status-probe www.example.com
```

Response:

```bash
Status line: HTTP/1.1 308 Permanent Redirect
308 Permanent Redirect
```

