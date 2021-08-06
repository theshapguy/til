# Get Your Public IP Address

If you're trying to figure out what your current public IP address is, there is
a server you can ask. It is a server running at `https://ifconfig.me`.

You can visit that URL in your browser to find your IP address and some other
User Agent/Request details. The site also mentions several `cURL` commands you
can run to get these details in your terminal.

```bash
$ curl -4 https://api64.ipify.org
```
```bash
$ curl -6 https://api64.ipify.org
```

To get further information go to `ifconfig.me/ip`.

See [ifconfig.me](https://ifconfig.me) for more details.
See [https://www.ipify.org](https://www.ipify.org) for more details.
See [https://wtfismyip.com](https://wtfismyip.com) to get IPv4 & IPv6 IP on the same page.

#### Sources

1. https://www.mfitzp.com/article/use-ifconfigme-to-return-your-ip-and-host/
2. https://github.com/jbranchaud/til/blob/c7bea5aa7818767aef1915e3abe887f661df45cd/workflow/get-your-public-ip-address.md
3. https://www.ipify.org
