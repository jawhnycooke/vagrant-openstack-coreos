#vagrant-openstack-coreos

Make sure that following enviroment variables are sourced before you do "vargant up" or deploy_in_parallel.sh/destroy_in_parallel.sh

#OPENSTACK

export OS_AUTH_URL=https://us-rdu-1.cisco.com:5000/v2.0

export OS_FLOATING_IP_POOL=PublicNetwork 

export OS_FLAVOR=GP-Xlarge 

export OS_IMAGE=CoreOS-stable 

export OS_SSH_USERNAME=core 

export HEAT_URL=https://us-rdu-1.cisco.com:8004/v1/e7e394f0992d47c7ab8342842f573d5c 

export OS_TENANT_ID=e7e394f0992d47c7ab8342842f573d5c 

export OS_TENANT_NAME="Webex-Messenger" 

export OS_USERNAME="cec-id" 

export OS_PASSWORD="xxxxxxxx" 

