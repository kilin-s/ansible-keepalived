# keepalived

vars:
keepalived_instance_interface: eth0 # interface to assign ip adress
keepalived_vrrp_state: MASTER # MASTER|BACKUP - state of instance
keepalived_virtual_router_id: 33 # uniq id for cluster
keepalived_router_id: nginx # uniq id over keepalive instance
keepalived_track_process: nginx # process to track 
keepalived_instance_priority: 100 # instance priority
keepalived_virtual_ip: 192.168.200.100 # assigned ip


