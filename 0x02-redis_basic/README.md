**Redis** offers a fast, in-memory data store to power live streaming use cases. Redis can be used to store metadata about users' profiles and viewing histories, authentication information/tokens for millions of users, and manifest files to enable CDNs to stream videos to millions of mobile and desktop users at a time.

ACL CAT
Lists the ACL categories, or the commands inside a category.

Read more
ACL DELUSER
Deletes ACL users, and terminates their connections.

Read more
ACL DRYRUN
Simulates the execution of a command by a user, without executing the command.

Read more
ACL GENPASS
Generates a pseudorandom, secure password that can be used to identify ACL users.

Read more
ACL GETUSER
Lists the ACL rules of a user.

Read more
ACL LIST
Dumps the effective rules in ACL file format.

Read more
ACL LOAD
Reloads the rules from the configured ACL file.

Read more
ACL LOG
Lists recent security events generated due to ACL rules.

Read more
ACL SAVE
Saves the effective ACL rules in the configured ACL file.

Read more
ACL SETUSER
Creates and modifies an ACL user and its rules.

Read more
ACL USERS
Lists all ACL users.

Read more
ACL WHOAMI
Returns the authenticated username of the current connection.

Read more
APPEND
Appends a string to the value of a key. Creates the key if it doesn't exist.

Read more
ASKING
Signals that a cluster client is following an -ASK redirect.

Read more
AUTH
Authenticates the connection.

Read more
BF.ADD
Adds an item to a Bloom Filter

Read more
BF.CARD
Returns the cardinality of a Bloom filter

Read more
BF.EXISTS
Checks whether an item exists in a Bloom Filter

Read more
BF.INFO
Returns information about a Bloom Filter

Read more
BF.INSERT
Adds one or more items to a Bloom Filter. A filter will be created if it does not exist

Read more
BF.LOADCHUNK
Restores a filter previously saved using SCANDUMP

Read more
BF.MADD
Adds one or more items to a Bloom Filter. A filter will be created if it does not exist

Read more
BF.MEXISTS
Checks whether one or more items exist in a Bloom Filter

Read more
BF.RESERVE
Creates a new Bloom Filter

Read more
BF.SCANDUMP
Begins an incremental save of the bloom filter

Read more
BGREWRITEAOF
Asynchronously rewrites the append-only file to disk.

Read more
BGSAVE
Asynchronously saves the database(s) to disk.

Read more
BITCOUNT
Counts the number of set bits (population counting) in a string.

Read more
BITFIELD
Performs arbitrary bitfield integer operations on strings.

Read more
BITFIELD_RO
Performs arbitrary read-only bitfield integer operations on strings.

Read more
BITOP
Performs bitwise operations on multiple strings, and stores the result.

Read more
BITPOS
Finds the first set (1) or clear (0) bit in a string.

Read more
BLMOVE
Pops an element from a list, pushes it to another list and returns it. Blocks until an element is available otherwise. Deletes the list if the last element was moved.

Read more
BLMPOP
Pops the first element from one of multiple lists. Blocks until an element is available otherwise. Deletes the list if the last element was popped.

Read more
BLPOP
Removes and returns the first element in a list. Blocks until an element is available otherwise. Deletes the list if the last element was popped.

Read more
BRPOP
Removes and returns the last element in a list. Blocks until an element is available otherwise. Deletes the list if the last element was popped.

Read more
BRPOPLPUSH
Pops an element from a list, pushes it to another list and returns it. Block until an element is available otherwise. Deletes the list if the last element was popped.

Read more
BZMPOP
Removes and returns a member by score from one or more sorted sets. Blocks until a member is available otherwise. Deletes the sorted set if the last element was popped.

Read more
BZPOPMAX
Removes and returns the member with the highest score from one or more sorted sets. Blocks until a member available otherwise. Deletes the sorted set if the last element was popped.

Read more
BZPOPMIN
Removes and returns the member with the lowest score from one or more sorted sets. Blocks until a member is available otherwise. Deletes the sorted set if the last element was popped.

Read more
CF.ADD
Adds an item to a Cuckoo Filter

Read more
CF.ADDNX
Adds an item to a Cuckoo Filter if the item did not exist previously.

Read more
CF.COUNT
Return the number of times an item might be in a Cuckoo Filter

Read more
CF.DEL
Deletes an item from a Cuckoo Filter

Read more
CF.EXISTS
Checks whether one or more items exist in a Cuckoo Filter

Read more
CF.INFO
Returns information about a Cuckoo Filter

Read more
CF.INSERT
Adds one or more items to a Cuckoo Filter. A filter will be created if it does not exist

Read more
CF.INSERTNX
Adds one or more items to a Cuckoo Filter if the items did not exist previously. A filter will be created if it does not exist

Read more
CF.LOADCHUNK
Restores a filter previously saved using SCANDUMP

Read more
CF.MEXISTS
Checks whether one or more items exist in a Cuckoo Filter

Read more
CF.RESERVE
Creates a new Cuckoo Filter

Read more
CF.SCANDUMP
Begins an incremental save of the bloom filter

Read more
CLIENT CACHING
Instructs the server whether to track the keys in the next request.

Read more
CLIENT GETNAME
Returns the name of the connection.

Read more
CLIENT GETREDIR
Returns the client ID to which the connection's tracking notifications are redirected.

Read more
CLIENT ID
Returns the unique client ID of the connection.

Read more
CLIENT INFO
Returns information about the connection.

Read more
CLIENT KILL
Terminates open connections.

Read more
CLIENT LIST
Lists open connections.

Read more
CLIENT NO-EVICT
Sets the client eviction mode of the connection.

Read more
CLIENT NO-TOUCH
Controls whether commands sent by the client affect the LRU/LFU of accessed keys.

Read more
CLIENT PAUSE
Suspends commands processing.

Read more
CLIENT REPLY
Instructs the server whether to reply to commands.

Read more
CLIENT SETINFO
Sets information specific to the client or connection.

Read more
CLIENT SETNAME
Sets the connection name.

Read more
CLIENT TRACKING
Controls server-assisted client-side caching for the connection.

Read more
CLIENT TRACKINGINFO
Returns information about server-assisted client-side caching for the connection.

Read more
CLIENT UNBLOCK
Unblocks a client blocked by a blocking command from a different connection.

Read more
CLIENT UNPAUSE
Resumes processing commands from paused clients.

Read more
CLUSTER ADDSLOTS
Assigns new hash slots to a node.

Read more
CLUSTER ADDSLOTSRANGE
Assigns new hash slot ranges to a node.

Read more
CLUSTER BUMPEPOCH
Advances the cluster config epoch.

Read more
CLUSTER COUNT-FAILURE-REPORTS
Returns the number of active failure reports active for a node.

Read more
CLUSTER COUNTKEYSINSLOT
Returns the number of keys in a hash slot.

Read more
CLUSTER DELSLOTS
Sets hash slots as unbound for a node.

Read more
CLUSTER DELSLOTSRANGE
Sets hash slot ranges as unbound for a node.

Read more
CLUSTER FAILOVER
Forces a replica to perform a manual failover of its master.

Read more
CLUSTER FLUSHSLOTS
Deletes all slots information from a node.

Read more
CLUSTER FORGET
Removes a node from the nodes table.

Read more
CLUSTER GETKEYSINSLOT
Returns the key names in a hash slot.

Read more
CLUSTER INFO
Returns information about the state of a node.

Read more
CLUSTER KEYSLOT
Returns the hash slot for a key.

Read more
CLUSTER LINKS
Returns a list of all TCP links to and from peer nodes.

Read more
CLUSTER MEET
Forces a node to handshake with another node.

Read more
CLUSTER MYID
Returns the ID of a node.

Read more
CLUSTER MYSHARDID
Returns the shard ID of a node.

Read more
CLUSTER NODES
Returns the cluster configuration for a node.

Read more
CLUSTER REPLICAS
Lists the replica nodes of a master node.

Read more
CLUSTER REPLICATE
Configure a node as replica of a master node.

Read more
CLUSTER RESET
Resets a node.

Read more
CLUSTER SAVECONFIG
Forces a node to save the cluster configuration to disk.

Read more
CLUSTER SET-CONFIG-EPOCH
Sets the configuration epoch for a new node.

Read more
CLUSTER SETSLOT
Binds a hash slot to a node.

Read more
CLUSTER SHARDS
Returns the mapping of cluster slots to shards.


