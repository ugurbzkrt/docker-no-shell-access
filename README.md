
"OCI runtime exec failed: exec failed: unable to start container process: exec: "/bin/sh": stat /bin/sh: no such file or directory"

(Distroless/Scratch) - /bin/bash - /bin/sh

BuNetwork Namespace access:

docker run --rm -it --network container:<id> alpine sh

with: telnet/curl
