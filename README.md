# network_automation_fortigate
network automation
Idea of this is to check a list of IPs if they are part of a group are in a bigger network which is already listed in the group.
Then the script asks you if you want to list the ones that are not present in the group

Example:

python3 Providers.py   #run it
Enter Operator name
<name>
Paste IP addresses one at a line
 quit/exit/q to end pasting
91.216.168.196/32
q
['91.216.168.196/32']
91.216.168.196/32 is in network 91.216.168.0/24
Nothing was whitelisted
