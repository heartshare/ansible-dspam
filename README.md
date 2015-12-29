[![Travis CI](http://img.shields.io/travis/le9i0nx/ansible-dspam.svg?style=flat)](http://travis-ci.org/le9i0nx/ansible-dspam) [![test-suite](http://img.shields.io/badge/test--suite-ansible--dspam-blue.svg?style=flat)](https://github.com/le9i0nx/test-suite/tree/master/ansible-dspam/) [![Ansible Galaxy](http://img.shields.io/badge/galaxy-le9i0nx.dspam-660198.svg?style=flat)](https://galaxy.ansible.com/list#/roles/5258)

DSPAM is a scalable and open-source content-based spam filter designed for multi-user enterprise systems. On a properly configured system, many users experience results between 99.5% - 99.95%, or one error for every 200 to 2000 messages. DSPAM supports many different MTAs and can also be deployed as a stand-alone SMTP appliance. For developers, the DSPAM core engine (libdspam) can be easily incorporated directly into applications for drop-in filtering.

### Installation

This role requires at least Ansible `v1.9.0`. To install it, run:

    ansible-galaxy install le9i0nx.dspam

### Documentation

### Role dependencies

- `debops.secret`
- `debops.rsyslog`

### Authors and license

`dspam` role was written by:
- Aleksej Gavrilov | [e-mail](mailto:le9i0nx@gmail.com) | [GitHub](https://github.com/le9i0nx)

License: [GPLv3](https://github.com/le9i0nx/ansible-dspam/blob/master/LICENSE)
