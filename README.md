# Installation of openshift 3.11 in 3 node cluster.

git clone https://github.com/awsompankaj/openshift-3.11.git

### using 3 node cluster.

master  > master and infra node
node1   > compute node
node2   > compute node

### after downloading run install-tools.sh on all 3 servers.

install ansible 2.6 or later on master or your local workstation.

make login password less on all 3 servers.

### run install-openshift.sh to setup 3 node openshift cluster.
