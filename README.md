# Requirements

You need `ansible` version 2.x installed locally

    sudo pip install ansible

# Machines

## Edmund

(The VM in Tenjin, not the dead box)

- Build with 16.04 image with MOFED for infiniband
* Attach edmund volume
- Run `ansible-playbook -i hosts edmund.yml```
