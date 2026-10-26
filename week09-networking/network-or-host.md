# Week 9: Network or host? My troubleshooting card

## The four failures I saw
```
Could not resolve host: no-such-site-invalid
Failed to connect to localhost port after 0 ms. Connection refused.
Operation timed out after 5000 milliseconds with 0 bytes recieved.
HTTP/1.0 404 Not Found.
```

## What each one means
Could not resolve to host: Network Problem.
Connection refused: Host problem.
Timed out: Network problem.
404 Not Found: Host Problem.

## How it works
127.0.0.1 only accepts incoming connections originating locally from inside the machine itself, blocking any external traffic attempting to reach it over network interfaces.
