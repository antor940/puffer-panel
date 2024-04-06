# Setting up a Minecraft Server using PufferPanel

## Overview

This guide explains how to set up a Minecraft server using the PufferPanel control panel.

## Step-by-Step Instructions

1. **Locate the 'Port' Option**: When creating a Minecraft server in the PufferPanel, ensure you locate the 'Port' option. Initially, set it to '25565'.
   
2. **Setting up Velocity Proxy**

If your server is created using Velocity, follow these steps to change the port binding:

1. Navigate to the `velocity.toml` file.
2. Find the line: `bind = "0.0.0.0:25577"`.
3. Modify the port according to your preference.
4. Save the changes.

3. **Single Server Configuration**: If your server is exclusively in the PufferPanel, there shouldn't be any issues with the default port.

4. **Multiple Server Configuration**: If you're creating multiple Minecraft servers, adjust the port to '25566' for each additional server. Increment the port number accordingly for each new server.

5. **Accessing Your Server IP**: Your server IP will be in the format "YOUR_VPS_IP:PORT". 

6. **Finding the Server Port**: To obtain the server port:
    - The default port is the one you set during the creation of the Minecraft server.
    - You can also modify it from the PufferPanel server settings. Navigate to your server in the PufferPanel, then access the settings. There will be a 'Port' section where you can view and modify the port number. The characters or numbers displayed in the 'Port' section will be your server port.

## Additional Notes

- Ensure you follow the steps correctly to have your server online and accessible.
- Always remember to save and apply your changes after modifying server settings.
