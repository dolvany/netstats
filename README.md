# netstats
Send Linux network counters to graphite. Counters which have never incremented are excluded. The parsed files are /proc/net/dev, /proc/net/snmp and /proc/net/netstat. All statistics are transformed into graphite format and then filtered with a series of regular expressions.
