# nftables
nftables rules and test 

nftables/port_knocking.nft
1. This template uses the classic table and chain naming convention (similar to iptables).
2. All actions occur in prerouting and do not affect incoming or outgoing traffic.
3. Knocking uses valid TCP SYN packets, taking into account traffic on various networks and equipment.
4. Security methods are applied only to the knocking ports you specify in the config (real packet numbers and trap packet numbers).
5. Emoji are used to simplify parameter changes.
6. This is not a default template - specify a link in /etc/nftables.conf
using the include option.

BEFORE USE, CHANGE THE ACTUAL KNOCKING AND TRAP PORTS TO SUITABLE USE.
CHECK THAT THE PERMISSION RULES FOR NAMING TABLES AND CHAINS MATCH.
