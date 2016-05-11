Clasp Build
=========

This role builds clasp from source.

Role Variables
--------------

- clasp_branch - which branch of code to build from
- clasp_src_dir - directory to download clasp source
- clasp_repo_url - url of remote clasp repo
- clasp_force_checkout - whether to force a recheckout
- pjobs - number of threads to use for building
- externals_clasp_dir - directory which contains the externals-clasp repo

Dependencies
------------

Clasp's build dependencies must be installed, and at the correct
version. See the Clasp-Externals role.

License
-------

MIT
