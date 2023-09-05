# Alliance Auth Theme: Console<a name="alliance-auth-theme-console"></a>

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
