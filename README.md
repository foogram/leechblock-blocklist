# leechblock-blocklist
a personal list of distracting websites

Add the following block to the registry key to prevent the extensions from getting disabled `Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Mozilla\Firefox` 

note : The closing bracket should be on the same line as registry gobles up the last bracket if its on a new line.
```json
{
    "leechblockng@proginosko.com": {
        "installation_mode": "force_installed",
        "install_url": "https://addons.mozilla.org/firefox/downloads/latest/leechblockng@proginosko.com/latest.xpi",
        "private_browsing" : true
    }}
```