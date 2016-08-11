Clasp Build
=========

This role builds clasp from source.

Role Variables
--------------

- `clasp_version` - which branch/commit/tag of code to build from,
  default: testing
- `clasp_src_dir` - directory to download clasp source, default: ~/clasp
- `clasp_repo_url` - url of remote clasp repo, default: https://github.com/drmeister/clasp
- `clasp_force_checkout` - whether to force a recheckout, default: true
- `pjobs` - number of threads to use for building, default: 2
- `externals_clasp_dir` - directory which contains the externals-clasp
  repo, default: /home/vagrant/externals-clasp

Dependencies
------------

Clasp's build dependencies must be installed, and at the correct
version. See the Clasp-Externals role.

License
-------

MIT
