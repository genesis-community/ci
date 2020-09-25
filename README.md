Genesis Continuous Integration (Template)
=========================================

This is a template for building Concourse CI/CD pipelines for
Genesis Kits.  These pipelines will properly vet and test kits
under a variety of (author-defined) deployment scenarios and
paradigms, and run optional validation (again, at the discretion
of the kit author).

To use, copy the `ci/` directory into the root of the Genesis Kit
git repository, and adjust the `ci/settings.yml` file.

search and replace for `UPDATEME` params
