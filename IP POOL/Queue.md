/queue simple
add max-limit=1G/1G name=ICMP-CCR-1009-KAZLA target=ICMP-CCR-1009-KAZLA
add dst=202.150.221.0/24 max-limit=1G/1G name="NewMedia Express - Singapore" target=""
add dst=157.119.185.0/24 max-limit=1G/1G name="Summit Communications Limited-DC IP Block" target=""
add dst=10.11.1.104/30 max-limit=1G/1G name=LANCACHE target=""
add dst=157.119.185.0/24 max-limit=1G/1G name=FAST.COM target=""
add dst=PTX02-SPEED-CDNRT-V327 max-limit=1G/1G name=PTX02-SPEED-CDNRT-V327 target=""
add dst=0.FTP max-limit=1G/1G name=0.FTP queue=BDIX-UL/BDIX-DL target=""
add dst=5.BDIX-VLAN-910-F@H-UG max-limit=1G/1G name=BDIX queue=BDIX-UL/BDIX-DL target=""
add dst=5.BDIX-VLAN-905-BASABO-OH max-limit=1G/1G name=BDIX-2 queue=BDIX-UL/BDIX-DL target=""
add dst=4.CDN-VLAN-914-BONGOBAZAR max-limit=1G/1G name=BDIX-3 queue=BDIX-UL/BDIX-DL target=""
add dst=2.GGC-VLAN-907-F@H-UG max-limit=1G/1G name=GGC-FREE-PACKAG1.E queue=GGC-FREE-PACKAGE/GGC-FREE-PACKAGE target=\
    10.16.20.0/22,10.16.24.0/22,10.16.28.0/24,10.14.16.0/21,10.14.24.0/24
add dst=2.GGC-VLAN-902-BASABO-OH max-limit=1G/1G name=2.GGC-FREE-PACKAGE queue=GGC-FREE-PACKAGE/GGC-FREE-PACKAGE target=\
    10.16.20.0/22,10.16.24.0/22,10.16.28.0/24,10.14.16.0/21,10.14.24.0/24
add dst=3.FNA-VLAN-908-F@H-UG max-limit=1G/1G name=1.FNA-FREE-PACKAGE queue=GGC-FREE-PACKAGE/GGC-FREE-PACKAGE target=\
    10.16.20.0/22,10.16.24.0/22,10.16.28.0/24,10.14.16.0/21,10.14.24.0/24
add dst=3.FNA-VLAN-903-BASABO-OH max-limit=1G/1G name=2.FNA-FREE-PACKAGE queue=GGC-FREE-PACKAGE/GGC-FREE-PACKAGE target=\
    10.16.20.0/22,10.16.24.0/22,10.16.28.0/24,10.14.16.0/21,10.14.24.0/24
add dst=2.GGC-VLAN-907-F@H-UG max-limit=8G/8G name=GGC-UG queue=GGC-UL/GGC-DL target=""
add dst=3.FNA-VLAN-908-F@H-UG max-limit=8G/8G name=FNA-UG queue=FNA-UL/FNA-DL target=""
add dst=2.GGC-VLAN-902-BASABO-OH max-limit=8G/8G name=GGC-BASABO queue=GGC-UL/GGC-DL target=""
add dst=3.FNA-VLAN-903-BASABO-OH max-limit=8G/8G name=FNA-BASABO queue=FNA-UL/FNA-DL target=""
add max-limit=2G/2G name=500TK-KAZLA-P2-1 queue=Upload/500TK-20MB target=10.16.40.0/24
add max-limit=2G/2G name=500TK-KAZLA-P2-2 queue=Upload/500TK-20MB target=10.16.41.0/24
add max-limit=2G/2G name=500TK-KAZLA-P2-3 queue=Upload/500TK-20MB target=10.16.42.0/24
add max-limit=2G/2G name=500TK-KAZLA-P2-4 queue=Upload/500TK-20MB target=10.16.43.0/24
add max-limit=2G/2G name=500TK-KAZLA-P2-5 queue=Upload/500TK-20MB target=10.16.44.0/24
add max-limit=2G/2G name=500TK-KAZLA-P2-6 queue=Upload/500TK-20MB target=10.16.45.0/24
add max-limit=2G/2G name=500TK-KAZLA-P2-7 queue=Upload/500TK-20MB target=10.16.46.0/24
add max-limit=2G/2G name=500TK-KAZLA-P2-8 queue=Upload/500TK-20MB target=10.16.47.0/24
add max-limit=2G/2G name=600TK-KAZLA queue=Upload/600TK-25MB target=10.16.8.0/24
add max-limit=1G/1G name=700TK-KAZLA queue=Upload/700TK-30MB target=10.16.9.0/24,103.183.63.64/32
add max-limit=2G/2G name=800TK-KAZLA queue=Upload/800TK-40MB target=10.16.10.0/24
add max-limit=2G/2G name=1000TK-KAZLA queue=Upload/1000TK-50MB target=10.16.11.0/24,103.183.63.66/32,103.183.63.67/32
add max-limit=2G/2G name=1200TK-KAZLA queue=Upload/1200TK-60MB target=10.16.12.0/24
add max-limit=2G/2G name=1500TK-KAZLA queue=Upload/1500TK-70MB target=10.16.13.0/24,103.183.63.65/32
add max-limit=2G/2G name=2000TK-KAZLA queue=Upload/2000TK-80MB target=10.16.14.0/24
add max-limit=2G/2G name=2500TK-KAZLA queue=Upload/2500TK-90MB target=10.16.15.0/24
add max-limit=2G/2G name=3000TK-KAZLA queue=Upload/3000TK-100MB target=10.16.16.0/24
add max-limit=2G/2G name=3500TK-KAZLA queue=Upload/3500TK-110MB target=10.16.17.0/24
add max-limit=2G/2G name=4000TK-KAZLA queue=Upload/4000TK-120MB target=10.16.18.0/24
add max-limit=2G/2G name=5000TK-KAZLA queue=Upload/4000TK-120MB target=10.16.19.0/24,10.16.4.180/32
add max-limit=100M/100M name=300TK-KAZLA queue=Upload/3MB target=10.16.20.0/24
add max-limit=100M/100M name=400TK-KAZLA queue=Upload/4MB target=10.16.21.0/24
add comment=300/- max-limit=100M/100M name=DISCOUNT-PKG-1-KAZLA queue=4MB/4MB target=10.16.22.0/24
add comment=400/- max-limit=100M/100M name=DISCOUNT-PKG-2-KAZLA queue=5MB/5MB target=10.16.23.0/24
add max-limit=50M/50M name=KAZLA-FREE-1MB queue=FREE-1MB/FREE-1MB target=10.16.24.0/24
add max-limit=50M/50M name=KAZLA-FREE-2MB queue=FREE-2MB/FREE-2MB target=10.16.25.0/24
add max-limit=50M/50M name=KAZLA-FREE-5MB queue=FREE-5MB/FREE-5MB target=10.16.26.0/24
add max-limit=50M/50M name=KAZLA-FREE-10MB queue=FREE-10MB/FREE-10MB target=10.16.27.0/24
add max-limit=50M/50M name=KAZLA-FREE-20MB queue=FREE-20MB/FREE-20MB target=10.16.28.0/24
add comment="############ UNCHAKED #################" max-limit=2G/2G name=3.PACKAGE-500/- queue=Upload/500TK-20MB target=10.14.0.0/22
add max-limit=2G/2G name=600TK-ALL-BRANCH queue=Upload/600TK-25MB target=10.14.4.0/24
add max-limit=2G/2G name=700TK-ALL-BRANCH queue=Upload/700TK-30MB target=10.14.5.0/24
add max-limit=2G/2G name=800TK-ALL-BRANCH queue=Upload/800TK-40MB target=10.14.6.0/24
add max-limit=2G/2G name=1000TK-ALL-BRANCH queue=Upload/1000TK-50MB target=10.14.7.0/24
add max-limit=2G/2G name=1200TK-ALL-BRANCH queue=Upload/1200TK-60MB target=10.14.8.0/24
add max-limit=2G/2G name=1500TK-ALL-BRANCH queue=Upload/1500TK-70MB target=10.14.9.0/24
add max-limit=2G/2G name=2000TK-ALL-BRANCH queue=Upload/2000TK-80MB target=10.14.10.0/24
add max-limit=2G/2G name=2500TK-ALL-BRANCH queue=Upload/2500TK-90MB target=10.14.11.0/24
add max-limit=2G/2G name=3000TK-ALL-BRANCH queue=Upload/3000TK-100MB target=10.14.12.0/24
add max-limit=2G/2G name=3500TK-ALL-BRANCH queue=Upload/3500TK-110MB target=10.14.13.0/24
add max-limit=2G/2G name=4000TK-ALL-BRANCH queue=Upload/4000TK-120MB target=10.14.14.0/24
add max-limit=2G/2G name=5000TK_KP-BRANCH queue=Upload/5000TK-150MB target=10.14.15.0/24
add max-limit=100M/100M name=PACKAGE-D3-500/- queue=4MB/4MB target=10.14.16.0/24
add max-limit=100M/100M name=PACKAGE-D4-500/- queue=5MB/5MB target=10.14.17.0/24
add max-limit=100M/100M name=300TK-ALL-BRANCH queue=3MB/3MB target=10.14.18.0/24
add max-limit=100M/100M name=400TK-ALL-BRANCH queue=4MB/4MB target=10.14.19.0/24
add max-limit=50M/50M name=FREE-PLAN-1MB queue=FREE-1MB/FREE-1MB target=10.14.20.0/24
add max-limit=50M/50M name=FREE-PLAN-2MB queue=FREE-2MB/FREE-2MB target=10.14.21.0/24
add max-limit=50M/50M name=FREE-PLAN-5MB queue=FREE-5MB/FREE-5MB target=10.14.22.0/24
add max-limit=50M/50M name=FREE-PLAN-10MB queue=FREE-10MB/FREE-10MB target=10.14.23.0/24
add max-limit=50M/50M name=FREE-PLAN-20MB queue=FREE-20MB/FREE-20MB target=10.14.24.0/24
add max-limit=100M/100M name=testpack20mb queue=Upload/testpack20mb target=172.20.50.0/24