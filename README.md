
# nopass

A library and full server setup for SMP plugins and server configuration.

## Server Structure

This setup uses three servers:

* Proxy → Velocity proxy server
* Lobby → PaperMC server (hub/lobby)
* Main → PaperMC server (main gameplay server)



## Installation

### Full Setup (Recommended for exact replica)

1. Stop all servers
2. Create a backup of your existing server files
3. Delete all contents inside each server directory
4. Copy and paste the provided files into each respective server folder

This will create an exact replica of the intended server network setup.



### Plugin-Only Setup

If you only want to use the plugins:

1. Open the server directory you want to modify:

   * Proxy
   * Lobby
   * Main

2. Navigate to:
   plugins/


3. Copy only the plugin files you want to use into your existing server



## Important Notes

* Some configuration values are intentionally removed or replaced with empty strings (""). These must be manually configured before use.
* Do not modify configuration values unless you are instructed to do so, as this may result in plugin errors, data corruption, or server instability.
* Always create a full backup of your server before applying any changes.
* Some plugins may not function correctly in all environments, especially when using PaperMC without Velocity.



## Third-Party Content

This project includes plugins and components that may come from external sources, including:

* Public plugin platforms such as Modrinth
* Independent developers
* AI-assisted development tools

All rights to these components remain with their original creators.

If you are the owner of any content included in this project and wish for it to be removed or credited differently, [contact us here](mailto:nopass.smp@gmail.com)

We will respond to valid requests and take appropriate action.



## Support

If you encounter issues:

* Check the documentation of the individual plugins
* Consult community resources
* Seek external technical support if necessary



## Disclaimer

This project is provided "as is", without any warranty of any kind. Use at your own risk. Create a Backup beforehand to prevent data loss

# -your NopassSMP team

