# Performance-Testing

First, you need to download JMeter. After performance testing is done, save the JMX file into the apache-JMeter bin folder. For non-GUI mode run, you need to go to the apache-JMeter bin location using cmd & type 

```sh
JMeter -n -t file_name.jmx -l log.jtl -e -o report 
```

- -n = It specifies JMeter is to run in non-GUI mode, 
- -t = Name of JMX file that contains the Test Plan, 
- -l = Name of JMeter text logs file to log results, 
- -e = Environment,
- -o = Output
 
