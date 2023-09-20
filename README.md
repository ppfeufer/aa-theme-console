# Alliance Auth Theme: Console<a name="alliance-auth-theme-console"></a>

[![Version](https://img.shields.io/pypi/v/aa-theme-console?label=release "Version")](https://pypi.org/project/aa-theme-console/)
[![License](https://img.shields.io/badge/license-GPLv3-green "License")](https://pypi.org/project/aa-theme-console/)
[![Python](https://img.shields.io/pypi/pyversions/aa-theme-console "Python")](https://pypi.org/project/aa-theme-console/)
[![Django](https://img.shields.io/pypi/djversions/aa-theme-console?label=django "Django")](https://pypi.org/project/aa-theme-console/)
![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white)
[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/ppfeufer/aa-theme-console/master.svg)](https://results.pre-commit.ci/latest/github/ppfeufer/aa-theme-console/master)
[![Code Style: black](https://img.shields.io/badge/code%20style-black-000000.svg "Code Style: black")](http://black.readthedocs.io/en/latest/)
[![Automated Checks](https://github.com/ppfeufer/aa-theme-console/actions/workflows/automated-checks.yml/badge.svg "Automated Checks")](https://github.com/ppfeufer/aa-theme-console/actions/workflows/automated-checks.yml)
[![codecov](https://codecov.io/gh/ppfeufer/aa-theme-console/branch/master/graph/badge.svg?token=J9PBF0HM8C "codecov")](https://codecov.io/gh/ppfeufer/aa-theme-console)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg "Contributor Covenant")](https://github.com/ppfeufer/aa-forum/blob/master/CODE_OF_CONDUCT.md)
[![Discord](https://img.shields.io/discord/790364535294132234?label=discord "Discord")](https://discord.gg/zmh52wnfvM)

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/N4N8CL1BY)

______________________________________________________________________

<!-- mdformat-toc start --slug=github --maxlevel=6 --minlevel=1 -->

- [Alliance Auth Theme: Console](#alliance-auth-theme-console)
  - [Installation](#installation)

<!-- mdformat-toc end -->

______________________________________________________________________

The perfect theme for all old school console nerds out there :-)

![AA Theme: Console](https://raw.githubusercontent.com/ppfeufer/aa-theme-console/master/aa_theme_console/images/aa-theme-console.jpg)

## Installation<a name="installation"></a>

```shell
pip install aa-theme-console
```

Now open your `local.py` and add the following right below your `INSTALLED_APPS`:

```python
# Console Thame - https://github.com/ppfeufer/aa-theme-console
INSTALLED_APPS.insert(0, "aa_theme_console")
```

**Important**

If you are using `AA-GDPR`, the template stuff needs to be **after** the `AA_GDPR`
entry, like this:

```python
# GDPR Compliance
INSTALLED_APPS.insert(0, "aagdpr")
AVOID_CDN = True


# Console Thame - https://github.com/ppfeufer/aa-theme-console
INSTALLED_APPS.insert(0, "aa_theme_console")
```
