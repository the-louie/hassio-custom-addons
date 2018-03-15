# OpenVPN Client



## Configuration

This takes only one configuration option: the OpenVPN config file for the
connection that you want to use. For example, if you have an OpenVPN config
file named "client.ovpn", simply copy that file to the /config directory on
your hass.io install, then configure your OpenVPN client as follows:

```json
{
  "ovpn_file": "client.ovpn"
}
```
