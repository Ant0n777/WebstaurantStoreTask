# WebstaurantStoreTask

This project is for sharing results of the WebstaurantStore Code Screen Task.
Result are JMeter .jmx file and html report.

You can run test locally too.
1. Clone/copy webstaurantstore_outlet.jmx to your machine into ${JMETER_HOME}/bin folder
2. Run test
   ${JMETER_HOME}/bin/jmeter -n -t webstaurantstore_outlet.jmx -l results.jtl
3. Generate report based on .jtl file
   ${JMETER_HOME}/bin/jmeter -g results.jtl -o webstaurantstore_outlet_report
