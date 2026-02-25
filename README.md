# grafos-caminhos-minimos
2026-02-25 15:19:49,760 INFO o.a.j.e.u.CompoundVariable: Note: Function class names must contain the string: '.functions.'
2026-02-25 15:19:49,761 INFO o.a.j.e.u.CompoundVariable: Note: Function class names must not contain the string: '.gui.'
2026-02-25 15:19:49,816 INFO o.a.j.r.ClassFinder: Will scan jar /opt/apache-jmeter-5.6.3/lib/ext/json-lib-2.4-jdk15.jar with filter ExtendsClassFilter [parents=[interface org.apache.jmeter.functions.Function], inner=false, contains=null, notContains=null]. Consider exposing JMeter plugins via META-INF/services, and add JMeter-Skip-Class-Scanning=true manifest attribute so JMeter can skip classfile scanning
2026-02-25 15:19:49,817 INFO o.a.j.r.ClassFinder: Will scan jar /opt/apache-jmeter-5.6.3/lib/ext/jmeter-plugins-manager-1.11.jar with filter ExtendsClassFilter [parents=[interface org.apache.jmeter.functions.Function], inner=false, contains=null, notContains=null]. Consider exposing JMeter plugins via META-INF/services, and add JMeter-Skip-Class-Scanning=true manifest attribute so JMeter can skip classfile scanning
2026-02-25 15:19:49,819 INFO o.a.j.r.ClassFinder: Will scan jar /opt/apache-jmeter-5.6.3/lib/ext/org.eclipse.paho.client.mqttv3-1.0.2.jar with filter ExtendsClassFilter [parents=[interface org.apache.jmeter.functions.Function], inner=false, contains=null, notContains=null]. Consider exposing JMeter plugins via META-INF/services, and add JMeter-Skip-Class-Scanning=true manifest attribute so JMeter can skip classfile scanning
2026-02-25 15:19:49,820 INFO o.a.j.r.ClassFinder: Will scan jar /opt/apache-jmeter-5.6.3/lib/ext/cmdrunner-2.3.jar with filter ExtendsClassFilter [parents=[interface org.apache.jmeter.functions.Function], inner=false, contains=null, notContains=null]. Consider exposing JMeter plugins via META-INF/services, and add JMeter-Skip-Class-Scanning=true manifest attribute so JMeter can skip classfile scanning
2026-02-25 15:19:49,821 INFO o.a.j.r.ClassFinder: Will scan jar /opt/apache-jmeter-5.6.3/lib/ext/mqtt-jmeter-0.0.1-SNAPSHOT.jar with filter ExtendsClassFilter [parents=[interface org.apache.jmeter.functions.Function], inner=false, contains=null, notContains=null]. Consider exposing JMeter plugins via META-INF/services, and add JMeter-Skip-Class-Scanning=true manifest attribute so JMeter can skip classfile scanning
2026-02-25 15:19:49,821 INFO o.a.j.r.ClassFinder: Will scan jar /opt/apache-jmeter-5.6.3/lib/ext/mqtt-xmeter-2.0.2-jar-with-dependencies.jar with filter ExtendsClassFilter [parents=[interface org.apache.jmeter.functions.Function], inner=false, contains=null, notContains=null]. Consider exposing JMeter plugins via META-INF/services, and add JMeter-Skip-Class-Scanning=true manifest attribute so JMeter can skip classfile scanning
2026-02-25 16:07:59,721 INFO o.a.j.s.FileServer: Default base='/home/pedro-mujica'
2026-02-25 16:07:59,722 INFO o.a.j.s.FileServer: Set new base='/home/pedro-mujica/projects'
2026-02-25 16:07:59,941 INFO o.a.j.s.SaveService: Testplan (JMX) version: 2.2. Testlog (JTL) version: 2.2
2026-02-25 16:07:59,951 INFO o.a.j.s.SaveService: Using SaveService properties version 5.0
2026-02-25 16:07:59,953 INFO o.a.j.s.SaveService: Using SaveService properties file encoding UTF-8
2026-02-25 16:10:09,730 INFO o.a.j.e.StandardJMeterEngine: Running the test!
2026-02-25 16:10:09,731 INFO o.a.j.s.SampleEvent: List of sample_variables: []
2026-02-25 16:10:09,731 INFO o.a.j.s.SampleEvent: List of sample_variables: []
2026-02-25 16:10:09,737 INFO o.a.j.g.u.JMeterMenuBar: setRunning(true, *local*)
2026-02-25 16:10:09,838 INFO o.a.j.e.StandardJMeterEngine: Starting ThreadGroup: 1 : ThreadsLoraDevices
2026-02-25 16:10:09,839 INFO o.a.j.e.StandardJMeterEngine: Starting 1 threads for group ThreadsLoraDevices.
2026-02-25 16:10:09,839 INFO o.a.j.e.StandardJMeterEngine: Thread will continue on error
2026-02-25 16:10:09,839 INFO o.a.j.t.ThreadGroup: Starting thread group... number=1 threads=1 ramp-up=1 delayedStart=false
2026-02-25 16:10:09,844 INFO o.a.j.t.ThreadGroup: Started thread group number 1
2026-02-25 16:10:09,844 INFO o.a.j.e.StandardJMeterEngine: All thread groups have been started
2026-02-25 16:10:09,845 INFO o.a.j.t.JMeterThread: Thread started: ThreadsLoraDevices 1-1
2026-02-25 16:10:11,938 INFO o.a.j.s.SampleResult: Note: Sample TimeStamps are START times
2026-02-25 16:10:11,938 INFO o.a.j.s.SampleResult: sampleresult.default.encoding is set to UTF-8
2026-02-25 16:10:11,939 INFO o.a.j.s.SampleResult: sampleresult.useNanoTime=true
2026-02-25 16:10:11,939 INFO o.a.j.s.SampleResult: sampleresult.nanoThreadSleep=5000
2026-02-25 16:10:11,949 ERROR o.a.j.t.JMeterThread: Error while processing sampler: 'MQTT Publisher'.
java.lang.IllegalArgumentException: 10.81.24.151:1883
	at org.eclipse.paho.client.mqttv3.MqttConnectOptions.validateURI(MqttConnectOptions.java:473) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:273) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:167) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttClient.<init>(MqttClient.java:224) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.apache.jmeter.protocol.mqtt.paho.clients.BlockingClient.<init>(BlockingClient.java:81) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.initClient(PublisherSampler.java:247) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.sample(PublisherSampler.java:271) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.threads.JMeterThread.doSampling(JMeterThread.java:651) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:570) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
2026-02-25 16:10:12,965 ERROR o.a.j.t.JMeterThread: Error while processing sampler: 'MQTT Publisher'.
java.lang.IllegalArgumentException: 10.81.24.151:1883
	at org.eclipse.paho.client.mqttv3.MqttConnectOptions.validateURI(MqttConnectOptions.java:473) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:273) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:167) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttClient.<init>(MqttClient.java:224) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.apache.jmeter.protocol.mqtt.paho.clients.BlockingClient.<init>(BlockingClient.java:81) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.initClient(PublisherSampler.java:247) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.sample(PublisherSampler.java:271) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.threads.JMeterThread.doSampling(JMeterThread.java:651) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:570) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
2026-02-25 16:10:13,969 ERROR o.a.j.t.JMeterThread: Error while processing sampler: 'MQTT Publisher'.
java.lang.IllegalArgumentException: 10.81.24.151:1883
	at org.eclipse.paho.client.mqttv3.MqttConnectOptions.validateURI(MqttConnectOptions.java:473) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:273) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:167) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttClient.<init>(MqttClient.java:224) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.apache.jmeter.protocol.mqtt.paho.clients.BlockingClient.<init>(BlockingClient.java:81) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.initClient(PublisherSampler.java:247) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.sample(PublisherSampler.java:271) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.threads.JMeterThread.doSampling(JMeterThread.java:651) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:570) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
2026-02-25 16:10:14,973 ERROR o.a.j.t.JMeterThread: Error while processing sampler: 'MQTT Publisher'.
java.lang.IllegalArgumentException: 10.81.24.151:1883
	at org.eclipse.paho.client.mqttv3.MqttConnectOptions.validateURI(MqttConnectOptions.java:473) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:273) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:167) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttClient.<init>(MqttClient.java:224) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.apache.jmeter.protocol.mqtt.paho.clients.BlockingClient.<init>(BlockingClient.java:81) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.initClient(PublisherSampler.java:247) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.sample(PublisherSampler.java:271) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.threads.JMeterThread.doSampling(JMeterThread.java:651) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:570) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
2026-02-25 16:10:15,976 ERROR o.a.j.t.JMeterThread: Error while processing sampler: 'MQTT Publisher'.
java.lang.IllegalArgumentException: 10.81.24.151:1883
	at org.eclipse.paho.client.mqttv3.MqttConnectOptions.validateURI(MqttConnectOptions.java:473) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:273) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:167) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttClient.<init>(MqttClient.java:224) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.apache.jmeter.protocol.mqtt.paho.clients.BlockingClient.<init>(BlockingClient.java:81) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.initClient(PublisherSampler.java:247) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.sample(PublisherSampler.java:271) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.threads.JMeterThread.doSampling(JMeterThread.java:651) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:570) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
2026-02-25 16:10:16,979 ERROR o.a.j.t.JMeterThread: Error while processing sampler: 'MQTT Publisher'.
java.lang.IllegalArgumentException: 10.81.24.151:1883
	at org.eclipse.paho.client.mqttv3.MqttConnectOptions.validateURI(MqttConnectOptions.java:473) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:273) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:167) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttClient.<init>(MqttClient.java:224) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.apache.jmeter.protocol.mqtt.paho.clients.BlockingClient.<init>(BlockingClient.java:81) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.initClient(PublisherSampler.java:247) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.sample(PublisherSampler.java:271) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.threads.JMeterThread.doSampling(JMeterThread.java:651) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:570) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
2026-02-25 16:10:17,983 ERROR o.a.j.t.JMeterThread: Error while processing sampler: 'MQTT Publisher'.
java.lang.IllegalArgumentException: 10.81.24.151:1883
	at org.eclipse.paho.client.mqttv3.MqttConnectOptions.validateURI(MqttConnectOptions.java:473) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:273) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:167) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttClient.<init>(MqttClient.java:224) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.apache.jmeter.protocol.mqtt.paho.clients.BlockingClient.<init>(BlockingClient.java:81) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.initClient(PublisherSampler.java:247) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.sample(PublisherSampler.java:271) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.threads.JMeterThread.doSampling(JMeterThread.java:651) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:570) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
2026-02-25 16:10:18,987 ERROR o.a.j.t.JMeterThread: Error while processing sampler: 'MQTT Publisher'.
java.lang.IllegalArgumentException: 10.81.24.151:1883
	at org.eclipse.paho.client.mqttv3.MqttConnectOptions.validateURI(MqttConnectOptions.java:473) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:273) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:167) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttClient.<init>(MqttClient.java:224) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.apache.jmeter.protocol.mqtt.paho.clients.BlockingClient.<init>(BlockingClient.java:81) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.initClient(PublisherSampler.java:247) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.sample(PublisherSampler.java:271) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.threads.JMeterThread.doSampling(JMeterThread.java:651) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:570) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
2026-02-25 16:10:19,991 ERROR o.a.j.t.JMeterThread: Error while processing sampler: 'MQTT Publisher'.
java.lang.IllegalArgumentException: 10.81.24.151:1883
	at org.eclipse.paho.client.mqttv3.MqttConnectOptions.validateURI(MqttConnectOptions.java:473) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:273) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:167) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttClient.<init>(MqttClient.java:224) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.apache.jmeter.protocol.mqtt.paho.clients.BlockingClient.<init>(BlockingClient.java:81) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.initClient(PublisherSampler.java:247) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.sample(PublisherSampler.java:271) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.threads.JMeterThread.doSampling(JMeterThread.java:651) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:570) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
2026-02-25 16:10:20,995 ERROR o.a.j.t.JMeterThread: Error while processing sampler: 'MQTT Publisher'.
java.lang.IllegalArgumentException: 10.81.24.151:1883
	at org.eclipse.paho.client.mqttv3.MqttConnectOptions.validateURI(MqttConnectOptions.java:473) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:273) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:167) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttClient.<init>(MqttClient.java:224) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.apache.jmeter.protocol.mqtt.paho.clients.BlockingClient.<init>(BlockingClient.java:81) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.initClient(PublisherSampler.java:247) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.sample(PublisherSampler.java:271) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.threads.JMeterThread.doSampling(JMeterThread.java:651) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:570) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
2026-02-25 16:10:21,998 ERROR o.a.j.t.JMeterThread: Error while processing sampler: 'MQTT Publisher'.
java.lang.IllegalArgumentException: 10.81.24.151:1883
	at org.eclipse.paho.client.mqttv3.MqttConnectOptions.validateURI(MqttConnectOptions.java:473) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:273) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:167) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttClient.<init>(MqttClient.java:224) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.apache.jmeter.protocol.mqtt.paho.clients.BlockingClient.<init>(BlockingClient.java:81) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.initClient(PublisherSampler.java:247) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.sample(PublisherSampler.java:271) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.threads.JMeterThread.doSampling(JMeterThread.java:651) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:570) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
2026-02-25 16:10:23,002 ERROR o.a.j.t.JMeterThread: Error while processing sampler: 'MQTT Publisher'.
java.lang.IllegalArgumentException: 10.81.24.151:1883
	at org.eclipse.paho.client.mqttv3.MqttConnectOptions.validateURI(MqttConnectOptions.java:473) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:273) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:167) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttClient.<init>(MqttClient.java:224) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.apache.jmeter.protocol.mqtt.paho.clients.BlockingClient.<init>(BlockingClient.java:81) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.initClient(PublisherSampler.java:247) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.sample(PublisherSampler.java:271) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.threads.JMeterThread.doSampling(JMeterThread.java:651) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:570) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
2026-02-25 16:10:24,005 ERROR o.a.j.t.JMeterThread: Error while processing sampler: 'MQTT Publisher'.
java.lang.IllegalArgumentException: 10.81.24.151:1883
	at org.eclipse.paho.client.mqttv3.MqttConnectOptions.validateURI(MqttConnectOptions.java:473) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:273) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:167) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttClient.<init>(MqttClient.java:224) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.apache.jmeter.protocol.mqtt.paho.clients.BlockingClient.<init>(BlockingClient.java:81) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.initClient(PublisherSampler.java:247) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.sample(PublisherSampler.java:271) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.threads.JMeterThread.doSampling(JMeterThread.java:651) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:570) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
2026-02-25 16:10:25,009 ERROR o.a.j.t.JMeterThread: Error while processing sampler: 'MQTT Publisher'.
java.lang.IllegalArgumentException: 10.81.24.151:1883
	at org.eclipse.paho.client.mqttv3.MqttConnectOptions.validateURI(MqttConnectOptions.java:473) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:273) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:167) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttClient.<init>(MqttClient.java:224) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.apache.jmeter.protocol.mqtt.paho.clients.BlockingClient.<init>(BlockingClient.java:81) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.initClient(PublisherSampler.java:247) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.sample(PublisherSampler.java:271) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.threads.JMeterThread.doSampling(JMeterThread.java:651) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:570) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
2026-02-25 16:10:26,012 ERROR o.a.j.t.JMeterThread: Error while processing sampler: 'MQTT Publisher'.
java.lang.IllegalArgumentException: 10.81.24.151:1883
	at org.eclipse.paho.client.mqttv3.MqttConnectOptions.validateURI(MqttConnectOptions.java:473) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:273) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:167) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttClient.<init>(MqttClient.java:224) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.apache.jmeter.protocol.mqtt.paho.clients.BlockingClient.<init>(BlockingClient.java:81) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.initClient(PublisherSampler.java:247) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.sample(PublisherSampler.java:271) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.threads.JMeterThread.doSampling(JMeterThread.java:651) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:570) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
2026-02-25 16:10:27,016 ERROR o.a.j.t.JMeterThread: Error while processing sampler: 'MQTT Publisher'.
java.lang.IllegalArgumentException: 10.81.24.151:1883
	at org.eclipse.paho.client.mqttv3.MqttConnectOptions.validateURI(MqttConnectOptions.java:473) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:273) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:167) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttClient.<init>(MqttClient.java:224) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.apache.jmeter.protocol.mqtt.paho.clients.BlockingClient.<init>(BlockingClient.java:81) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.initClient(PublisherSampler.java:247) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.sample(PublisherSampler.java:271) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.threads.JMeterThread.doSampling(JMeterThread.java:651) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:570) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
2026-02-25 16:10:28,020 ERROR o.a.j.t.JMeterThread: Error while processing sampler: 'MQTT Publisher'.
java.lang.IllegalArgumentException: 10.81.24.151:1883
	at org.eclipse.paho.client.mqttv3.MqttConnectOptions.validateURI(MqttConnectOptions.java:473) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:273) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:167) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttClient.<init>(MqttClient.java:224) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.apache.jmeter.protocol.mqtt.paho.clients.BlockingClient.<init>(BlockingClient.java:81) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.initClient(PublisherSampler.java:247) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.sample(PublisherSampler.java:271) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.threads.JMeterThread.doSampling(JMeterThread.java:651) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:570) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
2026-02-25 16:10:29,023 ERROR o.a.j.t.JMeterThread: Error while processing sampler: 'MQTT Publisher'.
java.lang.IllegalArgumentException: 10.81.24.151:1883
	at org.eclipse.paho.client.mqttv3.MqttConnectOptions.validateURI(MqttConnectOptions.java:473) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:273) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:167) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttClient.<init>(MqttClient.java:224) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.apache.jmeter.protocol.mqtt.paho.clients.BlockingClient.<init>(BlockingClient.java:81) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.initClient(PublisherSampler.java:247) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.sample(PublisherSampler.java:271) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.threads.JMeterThread.doSampling(JMeterThread.java:651) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:570) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
2026-02-25 16:10:30,026 ERROR o.a.j.t.JMeterThread: Error while processing sampler: 'MQTT Publisher'.
java.lang.IllegalArgumentException: 10.81.24.151:1883
	at org.eclipse.paho.client.mqttv3.MqttConnectOptions.validateURI(MqttConnectOptions.java:473) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:273) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:167) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttClient.<init>(MqttClient.java:224) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.apache.jmeter.protocol.mqtt.paho.clients.BlockingClient.<init>(BlockingClient.java:81) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.initClient(PublisherSampler.java:247) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.sample(PublisherSampler.java:271) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.threads.JMeterThread.doSampling(JMeterThread.java:651) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:570) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
2026-02-25 16:10:31,029 ERROR o.a.j.t.JMeterThread: Error while processing sampler: 'MQTT Publisher'.
java.lang.IllegalArgumentException: 10.81.24.151:1883
	at org.eclipse.paho.client.mqttv3.MqttConnectOptions.validateURI(MqttConnectOptions.java:473) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:273) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:167) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttClient.<init>(MqttClient.java:224) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.apache.jmeter.protocol.mqtt.paho.clients.BlockingClient.<init>(BlockingClient.java:81) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.initClient(PublisherSampler.java:247) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.sample(PublisherSampler.java:271) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.threads.JMeterThread.doSampling(JMeterThread.java:651) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:570) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
2026-02-25 16:10:32,032 ERROR o.a.j.t.JMeterThread: Error while processing sampler: 'MQTT Publisher'.
java.lang.IllegalArgumentException: 10.81.24.151:1883
	at org.eclipse.paho.client.mqttv3.MqttConnectOptions.validateURI(MqttConnectOptions.java:473) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:273) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:167) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttClient.<init>(MqttClient.java:224) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.apache.jmeter.protocol.mqtt.paho.clients.BlockingClient.<init>(BlockingClient.java:81) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.initClient(PublisherSampler.java:247) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.sample(PublisherSampler.java:271) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.threads.JMeterThread.doSampling(JMeterThread.java:651) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:570) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
2026-02-25 16:10:33,035 ERROR o.a.j.t.JMeterThread: Error while processing sampler: 'MQTT Publisher'.
java.lang.IllegalArgumentException: 10.81.24.151:1883
	at org.eclipse.paho.client.mqttv3.MqttConnectOptions.validateURI(MqttConnectOptions.java:473) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:273) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:167) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttClient.<init>(MqttClient.java:224) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.apache.jmeter.protocol.mqtt.paho.clients.BlockingClient.<init>(BlockingClient.java:81) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.initClient(PublisherSampler.java:247) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.sample(PublisherSampler.java:271) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.threads.JMeterThread.doSampling(JMeterThread.java:651) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:570) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
2026-02-25 16:10:34,039 ERROR o.a.j.t.JMeterThread: Error while processing sampler: 'MQTT Publisher'.
java.lang.IllegalArgumentException: 10.81.24.151:1883
	at org.eclipse.paho.client.mqttv3.MqttConnectOptions.validateURI(MqttConnectOptions.java:473) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:273) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:167) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttClient.<init>(MqttClient.java:224) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.apache.jmeter.protocol.mqtt.paho.clients.BlockingClient.<init>(BlockingClient.java:81) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.initClient(PublisherSampler.java:247) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.sample(PublisherSampler.java:271) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.threads.JMeterThread.doSampling(JMeterThread.java:651) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:570) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
2026-02-25 16:10:35,042 ERROR o.a.j.t.JMeterThread: Error while processing sampler: 'MQTT Publisher'.
java.lang.IllegalArgumentException: 10.81.24.151:1883
	at org.eclipse.paho.client.mqttv3.MqttConnectOptions.validateURI(MqttConnectOptions.java:473) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:273) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:167) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttClient.<init>(MqttClient.java:224) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.apache.jmeter.protocol.mqtt.paho.clients.BlockingClient.<init>(BlockingClient.java:81) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.initClient(PublisherSampler.java:247) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.sample(PublisherSampler.java:271) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.threads.JMeterThread.doSampling(JMeterThread.java:651) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:570) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
2026-02-25 16:10:36,045 ERROR o.a.j.t.JMeterThread: Error while processing sampler: 'MQTT Publisher'.
java.lang.IllegalArgumentException: 10.81.24.151:1883
	at org.eclipse.paho.client.mqttv3.MqttConnectOptions.validateURI(MqttConnectOptions.java:473) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:273) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:167) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttClient.<init>(MqttClient.java:224) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.apache.jmeter.protocol.mqtt.paho.clients.BlockingClient.<init>(BlockingClient.java:81) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.initClient(PublisherSampler.java:247) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.sample(PublisherSampler.java:271) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.threads.JMeterThread.doSampling(JMeterThread.java:651) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:570) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
2026-02-25 16:10:37,048 ERROR o.a.j.t.JMeterThread: Error while processing sampler: 'MQTT Publisher'.
java.lang.IllegalArgumentException: 10.81.24.151:1883
	at org.eclipse.paho.client.mqttv3.MqttConnectOptions.validateURI(MqttConnectOptions.java:473) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:273) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:167) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttClient.<init>(MqttClient.java:224) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.apache.jmeter.protocol.mqtt.paho.clients.BlockingClient.<init>(BlockingClient.java:81) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.initClient(PublisherSampler.java:247) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.sample(PublisherSampler.java:271) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.threads.JMeterThread.doSampling(JMeterThread.java:651) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:570) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
2026-02-25 16:10:38,052 ERROR o.a.j.t.JMeterThread: Error while processing sampler: 'MQTT Publisher'.
java.lang.IllegalArgumentException: 10.81.24.151:1883
	at org.eclipse.paho.client.mqttv3.MqttConnectOptions.validateURI(MqttConnectOptions.java:473) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:273) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:167) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttClient.<init>(MqttClient.java:224) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.apache.jmeter.protocol.mqtt.paho.clients.BlockingClient.<init>(BlockingClient.java:81) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.initClient(PublisherSampler.java:247) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.sample(PublisherSampler.java:271) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.threads.JMeterThread.doSampling(JMeterThread.java:651) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:570) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
2026-02-25 16:10:39,055 ERROR o.a.j.t.JMeterThread: Error while processing sampler: 'MQTT Publisher'.
java.lang.IllegalArgumentException: 10.81.24.151:1883
	at org.eclipse.paho.client.mqttv3.MqttConnectOptions.validateURI(MqttConnectOptions.java:473) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:273) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:167) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttClient.<init>(MqttClient.java:224) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.apache.jmeter.protocol.mqtt.paho.clients.BlockingClient.<init>(BlockingClient.java:81) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.initClient(PublisherSampler.java:247) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.sample(PublisherSampler.java:271) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.threads.JMeterThread.doSampling(JMeterThread.java:651) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:570) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
2026-02-25 16:10:40,058 ERROR o.a.j.t.JMeterThread: Error while processing sampler: 'MQTT Publisher'.
java.lang.IllegalArgumentException: 10.81.24.151:1883
	at org.eclipse.paho.client.mqttv3.MqttConnectOptions.validateURI(MqttConnectOptions.java:473) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:273) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttAsyncClient.<init>(MqttAsyncClient.java:167) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.eclipse.paho.client.mqttv3.MqttClient.<init>(MqttClient.java:224) ~[org.eclipse.paho.client.mqttv3-1.0.2.jar:?]
	at org.apache.jmeter.protocol.mqtt.paho.clients.BlockingClient.<init>(BlockingClient.java:81) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.initClient(PublisherSampler.java:247) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.protocol.mqtt.sampler.PublisherSampler.sample(PublisherSampler.java:271) ~[mqtt-jmeter-0.0.1-SNAPSHOT.jar:?]
	at org.apache.jmeter.threads.JMeterThread.doSampling(JMeterThread.java:651) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:570) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
2026-02-25 16:10:40,223 INFO o.a.j.g.a.Start: Stopping test
2026-02-25 16:10:40,229 INFO o.a.j.t.JMeterThread: Stopping: ThreadsLoraDevices 1-1
2026-02-25 16:10:40,230 WARN o.a.j.t.JMeterThread: The delay timer was interrupted - probably did not wait as long as intended.
2026-02-25 16:10:40,231 INFO o.a.j.t.JMeterThread: Thread finished: ThreadsLoraDevices 1-1
2026-02-25 16:10:40,231 INFO o.a.j.e.StandardJMeterEngine: Notifying test listeners of end of test
2026-02-25 16:10:40,235 INFO o.a.j.g.u.JMeterMenuBar: setRunning(false, *local*)



