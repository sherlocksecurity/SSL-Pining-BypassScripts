**Usage**

1. Configure your mobile proxy with BurpSuite proxy

2. Get the app_path from the output
> frida-ps -Ua

3. Run the command to bypass the root and SSL pinning restrictions
> frida -U -f (app_path) -l master_bypass.js

