
WebsiteHost v5.3 Beta (2026)
==============================

A lightweight, multi-site HTTP server for local testing, with optional HTTPS support.

Created by: Gavin Codework

--------------------------------
Features
--------------------------------
- Host multiple local sites with custom domains.
- Automatic HTML footer injection (safe banner iframe).
- Optional HTTPS support with PFX certificates.
- Logs all requests and errors in a simple GUI.
- Auto-loads sites and certificates from sites.json.
- Version label shown in the GUI: V5.3 Beta (2026).
- Simple navigation and live reload support (planned for future versions).

--------------------------------
Getting Started
--------------------------------
1. Place the WebsiteHost_v5.3_Beta.exe file in a folder of your choice.
2. Run WebsiteHost_v5.3_Beta.exe. (Administrator privileges recommended for low-numbered ports)
3. Add a site:
   - Click "Add Site".
   - Select the folder for your site. Or use the site1 folder.
   - Enter a local domain (e.g., site1.localhost).
4. Optional: Add HTTPS:
   - Click "Pick HTTPS Cert".
   - Select your PFX certificate and enter its password.
5. Start the server:
   - Click "Start Server".
   - Your sites are now available at the domain(s) you entered.

--------------------------------
Accessing Your Sites
--------------------------------
- Default HTTP port: 8080
- Default HTTPS port: 8443
- Example: http://site1.localhost:8080 or https://site1.localhost:8443
- Make sure to add your local domains to your hosts file if needed.

--------------------------------
File Structure
--------------------------------
- WebsiteHost_v5.3_Beta.exe : The main application.
- sites.json : Configuration file storing your sites and optional certificates.
- Your site folders: Containing index.html, about.html, etc.

--------------------------------
Quick Tips
--------------------------------
- Always run as Administrator for ports below 1024.
- Keep your site folders organized inside a main "sites" folder.
- To test locally, add domains to your hosts file:
  C:\Windows\System32\drivers\etc\hosts
- If using HTTPS, make sure the PFX certificate is valid and the password is correct.

--------------------------------
Troubleshooting
--------------------------------
- If a port is busy, choose a different one in the port box.
- If HTTPS fails, check your PFX certificate and password.
- If a page does not load, ensure your local domain is added to the hosts file.
- Logs in the app GUI show what was served and any errors.

--------------------------------
Notes
--------------------------------
- The "safe banner" iframe is injected automatically into HTML pages if not already present.
- Low-numbered ports (<1024) may require Administrator privileges.

--------------------------------
Contact
--------------------------------
Created by Gavin Codework
Website: https://php-testing.fwh.is

--------------------------------
Enjoy hosting your local sites!
--------------------------------
