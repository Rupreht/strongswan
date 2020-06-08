# strongSwan IKEv2 VPN Server on Docker Compose

[How To Config](https://wiki.strongswan.org/projects/strongswan/wiki/ConfigurationFiles)

## Get Apple Security Profile

Generate a .mobileconfig file for Apple users

```bash
docker-compose exec strongswan generate-mobileconfig > my-ikev2-vpn.mobileconfig
```

- https://support.apple.com/en-gb/guide/iphone/iph6c493b19/ios

License [GNU General Public License, version 2](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html)

> see you on the other side ;-)

