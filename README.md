# credmark-client-py

Credmark client library for python

See the package [README.rst](README.rst)

## Publish Package

### Update Version

- Update the version in `setup.py`, update `HISTORY.rst`, and git commit the changes.

- Tag in git, replacing the version string:

```bash
git tag -a "0.1.0" -m "Version 0.1.0"
git push origin "0.1.0"
```

### Build

```
python3 -m build
```

### Check

```
twine check dist/*
```

### Upload

```
python3 -m twine upload dist/*
```
