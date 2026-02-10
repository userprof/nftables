# nftables
nftables rules and test 

nftables/port_knocking.nft
1. This template uses standard table and chain naming (similar to iptables).
2. All actions occur in the prerouting section and do not affect incoming or outgoing traffic.
3. Knocking uses valid TCP SYN packets, taking into account traffic flow across various networks and equipment.
4. Protection methods are applied only to the knocking ports you specify in the config (real packet numbers and trap packet numbers).
5. To simplify parameter changes, emoji are used.

BEFORE USE, CHANGE THE ACTUAL KNOCKING AND TRAP PORTS TO SUITABLE USE !!!
CHECK THAT THE ALLOWING RULES MATCH THE TABLE AND CHAINS' NAMES !!!
