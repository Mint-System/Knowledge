# Odoo Troubleshooting

## Odoo-Client-Fehler

**Problem**

After restoring an Odoo instance the following error occurs

```
Fehler:
Zurückverfolgung
_generateActionViews/<@https://metallprojekt.mintsys.ch/web/content/625-ed50555/web.assets_backend.js:447:298
_.forEach@https://metallprojekt.mintsys.ch/web/content/606-2d12e2f/web.assets_common.js:108:566
_generateActionViews@https://metallprojekt.mintsys.ch/web/content/625-ed50555/web.assets_backend.js:447:229
_executeWindowAction/<@https://metallprojekt.mintsys.ch/web/content/625-ed50555/web.assets_backend.js:442:497
```

**Solution**

Reassmble all assets. Alernatively delete assets entries.

##  Python OSError

**Problem**

When generating a report with p3yo this error occurs:

```
OSError: [Errno 8] Exec format error: '/usr/local/bin/libreoffice'
```

**Solution**

Apply shebang line `#!/bin/sh` in shell script.
