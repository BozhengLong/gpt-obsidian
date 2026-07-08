# One-time setup

1. In Obsidian, install and enable the community plugin **Local REST API**.
2. In the plugin settings, enable **"Enable Non-encrypted (HTTP) Server"**
   (binds to `http://127.0.0.1:27123`). This avoids dealing with the
   plugin's self-signed HTTPS certificate since traffic never leaves
   this machine.
3. Copy the generated **API key** from the plugin settings.
4. Click the extension icon → the popup won't have a settings link yet
   in early tasks; once Task 9 (options page) is done, open the
   extension's options page and paste the API key there.
