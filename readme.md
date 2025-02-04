# pihole-ausnews

Australian News Site DNS Blocklist for Pihole (and [AdguardHome](https://github.com/AdguardTeam/AdguardHome)). This list blocks non-Murdoch owned Australian new websites and services like ABC, The Sydney Morning Herald, 7News. If you're looking to block Murdoch sites, check out [suodrazah/murdoch_blocklist](https://github.com/suodrazah/murdoch_blocklist)!

```
https://raw.githubusercontent.com/JackCuthbert/pihole-ausnews/refs/heads/main/pihole-ausnews.txt
```

> Warning: This will block any ABC hosted content, like IView, TripleJ, ABC Listen, etc. If you still use other ABC Services I'd recommend not using the main list and instead using the list that does not include ABC domains.
> **Allow ABC list:** `https://raw.githubusercontent.com/JackCuthbert/pihole-ausnews/refs/heads/main/pihole-ausnews-excl-abc.txt`

## Usage

### Pi-Hole

1. Login into Pi-Hole admin
2. Navigate to "Adlists"
3. Copy this URL: `https://raw.githubusercontent.com/JackCuthbert/pihole-ausnews/refs/heads/main/pihole-ausnews.txt`
4. Paste the URL in the address box and click on Add

### AdguardHome

1. Login to AdguardHome admin
2. Navigate to Filters > DNS Blocklists
3. Click "Add blocklist" at the bottom
4. Select "Add a custom list"
5. Enter a name like `pihole-ausnews`
6. Enter this url: `https://raw.githubusercontent.com/JackCuthbert/pihole-ausnews/refs/heads/main/pihole-ausnews.txt`
7. Click "Save"

## Other lists

I sometimes maintain other lists:

- [pihole-reddit](https://github.com/JackCuthbert/pihole-reddit): Block Reddit domains
- [pihole-splogs](https://github.com/JackCuthbert/pihole-splogs): Block low value GitHub or Stack Overflow spam blogs.
- [pihole-twitter](https://github.com/JackCuthbert/pihole-twitter): Block X (formerly known as Twitter) domains
