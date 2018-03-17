# nordvpn_organize
Organizes NordVPN configuration files for Tunnelblick

- Do you use Tunnelblick?
- The 7000+ ovpn files seem daunting to import? 
- Do you need to scroll endlessly on the Tunnelblick dropdown to find what you want?

Luckily nordvpn_organize can help bring some structure to your NordVPN configuration files.
Just clone this project and run
```
echo ~/Downloads/ovpn_tblk/**/*.ovpn | ./nordvpn_organize
```
to structure your files into a pretty folder structure according to
`type/protocol/location/name`.
Or if it doesn't fit, you can customize the format!

Python 3.2+ required.
