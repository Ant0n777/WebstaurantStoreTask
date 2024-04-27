# WebstaurantStoreTask

This project is for sharing results of the WebstaurantStore Code Screen Task.

Results are in the following files:
1. webstaurantstore_outlet.jmx - JMeter test plan
2. results.jtl - JMeter results in csv format (ran with command `${JMETER_HOME}/bin/jmeter -n -t webstaurantstore_outlet.jmx -l results.jtl`)
3. results.xls - aggregated results/charts in Excel format

Conclusions:
- Average response time for opening pages with different outlet products (with all embedded resources) - 2790 ms.
- Median - 2630 ms
- Min response time - 1400 ms
- Max response time - 6040 ms

- Round trip network time between my laptop and webstaurantstore.com was approximately 28 ms, which is relatively small.

- The average outlet product page requires 1.739 kB to download.
- During 15 minutes of testing 61 requests were performed.
- With such a small load it doesn't make sense to analyze throughput results.
