/ppp profile
set *0 change-tcp-mss=no dns-server=8.8.8.8 only-one=yes use-upnp=no
add dns-server=8.8.8.8 local-address=10.163.0.1 name=NETX-P1-500/- only-one=yes \
    remote-address=NETX-P1-500/-
add dns-server=8.8.8.8 local-address=10.163.1.1 name=NETX-P2-600/- only-one=yes \
    remote-address=NETX-P2-600/-
add dns-server=8.8.8.8 local-address=10.163.2.1 name=NETX-P3-700/- only-one=yes \
    remote-address=NETX-P3-700/-
add dns-server=8.8.8.8 local-address=10.163.3.1 name=NETX-P4-800/- only-one=yes \
    remote-address=NETX-P4-800/-
add dns-server=8.8.8.8 local-address=10.163.4.1 name=NETX-P5-1000/- only-one=\
    yes remote-address=NETX-P5-1000/-
add dns-server=8.8.8.8 local-address=10.162.5.1 name=NETX-P6-1200/- only-one=\
    yes remote-address=NETX-P6-1200/-
add dns-server=8.8.8.8 local-address=10.162.6.1 name=NETX-P7-1500/- only-one=\
    yes remote-address=NETX-P7-1500/-
add dns-server=8.8.8.8,8.8.4.4 local-address=10.162.7.1 name=NETX-P8-2000/- \
    only-one=yes remote-address=NETX-P8-2000/-
add dns-server=8.8.8.8,10.0.1.53 local-address=10.162.8.1 name=NETX-P9-2500/- \
    only-one=yes remote-address=NETX-P9-2500/-
add dns-server=8.8.8.8 local-address=10.162.9.1 name=NETX-P10-3000/- only-one=\
    yes remote-address=NETX-P10-3000/-
add dns-server=8.8.8.8 local-address=10.163.10.1 name=NETX-P11-300/- only-one=\
    yes remote-address=NETX-P11-300/-
