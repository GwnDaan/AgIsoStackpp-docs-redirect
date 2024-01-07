# AgIsoStack++ Documentation Redirect

To migrate from an old ReadTheDocs project to the agisostack-plus-plus subdomain:

On the ReadTheDocs dashboard of your old project, do the following:
1. Add an **Exact** Redirect from `/*` to `https://agisostack-plus-plus.readthedocs.io/` with a 301 status code.

2. Deactivate all versions of the old project, except latest (which can't be deactivated)

3. Change the repository URL on https://readthedocs.org/dashboard/oldproject/edit/ to this repository.

4. If needed, change the latest branch to `main`.

## References

- https://stackoverflow.com/a/69928404
