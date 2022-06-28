# usom-blacklist

Malicious addresses are constantly added to the USOM's list of malicious addresses. Even if there is an address that is no longer accessible, it will not be deleted from the list! It is a suitable list for address-based blocking.

If DNS-based blocking is done with inaccessible addresses, this long list is read for comparison with each incoming DNS query. Therefore, it unnecessarily consumes the processing power and memory of the DNS server. It also causes increased DNS response times and decreased performance.

This repository is to automatically generate new block lists by checking the accessible addresses of the USOM list on a weekly basis.
