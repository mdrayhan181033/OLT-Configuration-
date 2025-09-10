/ppp profile
set *0 change-tcp-mss=default dns-server=103.123.168.50,8.8.8.8 local-address=10.16.0.1 only-one=yes remote-address=PP-500
add dhcpv6-pd-pool=LAN_IPV6 dns-server=103.123.168.50,8.8.8.8 local-address=10.16.40.1 name=SPEED-REGULAR-500/- only-one=yes remote-address=PP-500 \
    remote-ipv6-prefix-pool=GW_IPV6
add dhcpv6-pd-pool=LAN_IPV6 dns-server=103.123.168.50,8.8.8.8 local-address=10.16.8.1 name=SPEED-REGULAR-600/- only-one=yes remote-address=PP-600 remote-ipv6-prefix-pool=\
    GW_IPV6
add dhcpv6-pd-pool=LAN_IPV6 dns-server=103.123.168.50,8.8.8.8 local-address=10.16.9.1 name=SPEED-REGULAR-700/- only-one=yes remote-address=PP-700 remote-ipv6-prefix-pool=\
    GW_IPV6
add dhcpv6-pd-pool=LAN_IPV6 dns-server=103.123.168.50,8.8.8.8 local-address=10.16.10.1 name=SPEED-REGULAR-800/- only-one=yes remote-address=PP-800 \
    remote-ipv6-prefix-pool=GW_IPV6
add dhcpv6-pd-pool=LAN_IPV6 dns-server=103.123.168.50,8.8.8.8 local-address=10.16.11.1 name=SPEED-REGULAR-1000/- only-one=yes remote-address=PP-1000 \
    remote-ipv6-prefix-pool=GW_IPV6
add dhcpv6-pd-pool=LAN_IPV6 dns-server=103.123.168.50,8.8.8.8 local-address=10.16.12.1 name=SPEED-REGULAR-1200/- only-one=yes remote-address=PP-1200 \
    remote-ipv6-prefix-pool=GW_IPV6
add dhcpv6-pd-pool=LAN_IPV6 dns-server=103.123.168.50,8.8.8.8 local-address=10.16.13.1 name=SPEED-REGULAR-1500/- only-one=yes remote-address=PP-1500 \
    remote-ipv6-prefix-pool=GW_IPV6
add dhcpv6-pd-pool=LAN_IPV6 dns-server=103.123.168.50,8.8.8.8 local-address=10.16.14.1 name=SPEED-REGULAR-2000/- only-one=yes remote-address=PP-2000 \
    remote-ipv6-prefix-pool=GW_IPV6
add dhcpv6-pd-pool=LAN_IPV6 dns-server=103.123.168.50,8.8.8.8 local-address=10.16.15.1 name=SPEED-REGULAR-2500/- only-one=yes remote-address=PP-2500 \
    remote-ipv6-prefix-pool=GW_IPV6
add dhcpv6-pd-pool=LAN_IPV6 dns-server=103.123.168.50,8.8.8.8 local-address=10.16.16.1 name=SPEED-REGULAR-3000/- only-one=yes remote-address=PP-3000 \
    remote-ipv6-prefix-pool=GW_IPV6
add dhcpv6-pd-pool=LAN_IPV6 dns-server=103.123.168.50,8.8.8.8 local-address=10.16.17.1 name=SPEED-REGULAR-3500/- only-one=yes remote-address=PP-3500 \
    remote-ipv6-prefix-pool=GW_IPV6
add dhcpv6-pd-pool=LAN_IPV6 dns-server=103.123.168.50,8.8.8.8 local-address=10.16.18.1 name=SPEED-REGULAR-4000/- only-one=yes remote-address=PP-4000 \
    remote-ipv6-prefix-pool=GW_IPV6
add dhcpv6-pd-pool=LAN_IPV6 dns-server=103.123.168.50,8.8.8.8 local-address=10.16.19.1 name=SPEED-REGULAR-5000/- only-one=yes remote-address=PP-5000 \
    remote-ipv6-prefix-pool=GW_IPV6
add dns-server=103.123.168.50,8.8.8.8 local-address=10.16.24.1 name=SPEED-FREE-1MB only-one=yes remote-address=FREE-PLAN-1
add dns-server=103.123.168.50,8.8.8.8 local-address=10.16.25.1 name=SPEED-FREE-2MB only-one=yes remote-address=FREE-PLAN-2
add dns-server=103.123.168.50,8.8.8.8 local-address=10.16.26.1 name=SPEED-FREE-5MB only-one=yes remote-address=FREE-PLAN-5
add dns-server=103.123.168.50,8.8.8.8 local-address=10.16.27.1 name=SPEED-FREE-10MB only-one=yes remote-address=FREE-PLAN-10
add dns-server=103.123.168.50,8.8.8.8 local-address=10.16.28.1 name=SPEED-FREE-20MB only-one=yes remote-address=FREE-PLAN-20
add dns-server=103.123.168.50,8.8.8.8 local-address=10.16.20.1 name=300BDT/- only-one=yes remote-address=PP-300
add dns-server=103.123.168.50,8.8.8.8 local-address=10.16.21.1 name=400BDT/- only-one=yes remote-address=PP-400
add local-address=172.172.0.1 name=Expired remote-address=Expired
add dns-server=103.123.168.50,8.8.8.8 local-address=10.16.22.1 name=PACKAGE-D3-500/- only-one=yes remote-address=PACKAGE-D3-500/-
add dns-server=103.123.168.50,8.8.8.8 local-address=10.16.23.1 name=PACKAGE-D4-500/- only-one=yes remote-address=PACKAGE-D4-500/-
add dns-server=103.123.168.50,8.8.8.8 local-address=10.16.70.1 name=SPEED-FREE-30MB only-one=yes remote-address=*18