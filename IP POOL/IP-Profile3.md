/ppp profile
set *0 dns-server=8.8.8.8 local-address=10.100.32.1 remote-address=Bypass
add local-address=192.168.10.1 name=VPN remote-address=VPN
add dns-server=8.8.8.8 local-address=10.100.0.1 name=7Mbps only-one=yes remote-address=7Mbps
add dns-server=8.8.8.8 local-address=10.100.4.1 name=10Mbps only-one=yes remote-address=10Mbps
add dns-server=8.8.8.8 local-address=10.100.8.1 name=15Mbps only-one=yes remote-address=15Mbps
add dns-server=8.8.8.8 local-address=10.100.12.1 name=20Mbps only-one=yes remote-address=20Mbps
add local-address=172.172.0.1 name=Expired only-one=yes remote-address=Expired_Pool
add dns-server=8.8.8.8 local-address=10.100.16.1 name=10MB only-one=yes remote-address=10MB
add dns-server=8.8.8.8 local-address=10.100.20.1 name=12Mbps-AR only-one=yes remote-address=12Mbps-AR
add dns-server=8.8.8.8,8.8.4.4 local-address=10.172.0.1 name=Tushar5Mbps only-one=yes remote-address=Tushar5Mbps
add dns-server=8.8.8.8,8.8.4.4 local-address=10.100.28.1 name=5Mbps remote-address=5Mbps
add dns-server=8.8.8.8 local-address=10.100.24.1 name=30Mbps only-one=yes remote-address=30Mbps
add local-address=10.100.36.1 name=5MB-STL-JHENAIDHA only-one=yes remote-address=5MB-STL-JHENAIDHA
add dns-server=8.8.8.8 local-address=10.100.28.1 name=10-Mbps only-one=yes remote-address=10-Mbps
add dns-server=8.8.8.8,8.8.4.4 local-address=10.100.40.1 name=TM-10MB only-one=yes remote-address=TM-10MB
add dns-server=8.8.8.8,8.8.4.4 local-address=10.100.44.1 name=TM-12MB only-one=yes remote-address=TM-12MB
add dns-server=8.8.8.8 local-address=10.100.48.1 name=40Mbps only-one=yes remote-address=40Mbps
add dns-server=8.8.8.8 local-address=10.100.52.1 name=50Mbps only-one=yes remote-address=50Mbps
add dns-server=8.8.8.8 local-address=10.100.56.1 name=20Mbps-AR only-one=yes remote-address=20Mbps-AR
add dns-server=8.8.8.8 local-address=10.100.58.1 name=30Mbps-AR only-one=yes remote-address=30Mbps-AR
add dns-server=8.8.8.8 local-address=10.100.60.1 name=40Mbps-AR only-one=yes remote-address=40Mbps-AR
add dns-server=8.8.8.8 local-address=10.100.62.1 name=50Mbps-AR only-one=yes remote-address=50Mbps-AR
add name=3
add dns-server=8.8.8.8 local-address=10.100.58.1 name=KGN-30Mbps only-one=yes remote-address=KGN-30Mbps
add dns-server=8.8.8.8 local-address=10.100.60.1 name=KGN-40Mbps only-one=yes remote-address=KGN-40Mbps
add dns-server=8.8.8.8 local-address=10.100.62.1 name=KGN-50Mbps only-one=yes remote-address=KGN-50Mbps
