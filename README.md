[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](http://www.gnu.org/licenses/gpl-3.0)
[![ansible-lint](https://github.com/Rosa-Luxemburgstiftung-Berlin/rls.securepim/actions/workflows/lint.yml/badge.svg)](https://github.com/Rosa-Luxemburgstiftung-Berlin/rls.securepim/actions/workflows/lint.yml)

# rls.securepim
ansible playbook to setup [secure pim gateway](https://www.virtual-solution.com/)

## prereq

### deb packages
copy the deb packages to files/securepim/sgw/

### config gw_token
set the var `rls_securepim_gateway_gw_token`
