# outerspace.js

An InnerSpace proxy, to see if I could write one.

**If you like the software, please buy a subscription!**

**I wrote this because my trial ran out and I hadn't had a chance to use it properly.**

# Running

Start the node-script like any other.

# Prerequisites

Because InnerSpace doesn't use DNS lookup, the `hosts` file cannot be used.
The backend-IP's should instead be mapped to the loopback interface.

    netsh interface ipv4 add address "Loopback" 50.23.91.236
    netsh interface ipv4 add address "Loopback" 37.58.71.184

Requires a full, working install of InnerSpace.
