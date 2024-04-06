# Setting up a Minecraft Server using PufferPanel

## Overview

This guide explains how to set up a Minecraft server using the PufferPanel control panel.

## Step-by-Step Instructions

1. **Locate the 'Port' Option**: When creating a Minecraft server in the PufferPanel, ensure you locate the 'Port' option. Initially, set it to '25565'.

3. **if your server is created by Velocity the go to "velocity.toml" an change the:**
# What port should the proxy be bound to? By default, we'll bind to all addresses on port 25577.
**bind = "0.0.0.0:25577**
**change it according to you it not work if you change the port in Puffer Panel setting you must do it in the "velocity.toml" file to work**

4. **Single Server Configuration**: If your server is exclusively in the PufferPanel, there shouldn't be any issues with the default port.

5. **Multiple Server Configuration**: If you're creating multiple Minecraft servers, adjust the port to '25566' for each additional server. Increment the port number accordingly for each new server.

6. **Accessing Your Server IP**: Your server IP will be in the format "YOUR_VPS_IP:PORT". 

7. **Finding the Server Port**: To obtain the server port:
    - The default port is the one you set during the creation of the Minecraft server.
    - You can also modify it from the PufferPanel server settings. Navigate to your server in the PufferPanel, then access the settings. There will be a 'Port' section where you can view and modify the port number. The characters or numbers displayed in the 'Port' section will be your server port.

## Additional Notes

- Ensure you follow the steps correctly to have your server online and accessible.
- Always remember to save and apply your changes after modifying server settings.
