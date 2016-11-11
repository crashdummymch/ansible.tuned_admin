#Ansible Role: crashdummymch.tuned_admin
Ansible role for managing tuned profiles and setting active profile  


Creating custom profile:  
1. Place profile directory into files/profiles/[profilename]
2. Set tuned_admin_profile to [profilename]
#License:
GPLv3  
#Dependencies:
crashdummymch.tuned  
#Usage:
role: tuned-admin  
#Variables Used:
tuned_config_dir: "/etc/tuned"  
tuned_admin_tunedadm: 'tuned-adm'  
tuned_admin_profile: 'balanced'  
