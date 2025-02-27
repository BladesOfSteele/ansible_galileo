This defines a role to install the Galileo agent on AIX and Linux. This was only tested on AIX 7.2 and RHEL on ppc64le.

The inventory file must group systems by OS.  This is important, since the group specifies where to expect to find the python execcutable,
which is a reuirement to gather facts. Horse-cart issue.

