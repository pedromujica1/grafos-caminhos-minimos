2026-02-25 16:16:41,900 INFO o.a.j.s.FileServer: Default base='/home/pedro-mujica'
2026-02-25 16:16:41,903 INFO o.a.j.g.a.Load: Loading file: /home/pedro-mujica/projects/ThreadsLoraDevices.jmx
2026-02-25 16:16:41,903 INFO o.a.j.s.FileServer: Set new base='/home/pedro-mujica/projects'
2026-02-25 16:16:42,123 INFO o.a.j.s.SaveService: Testplan (JMX) version: 2.2. Testlog (JTL) version: 2.2
2026-02-25 16:16:42,132 INFO o.a.j.s.SaveService: Using SaveService properties version 5.0
2026-02-25 16:16:42,134 INFO o.a.j.s.SaveService: Using SaveService properties file encoding UTF-8
2026-02-25 16:16:42,136 INFO o.a.j.s.SaveService: Loading file: /home/pedro-mujica/projects/ThreadsLoraDevices.jmx
2026-02-25 16:16:42,658 INFO o.a.j.s.FileServer: Set new base='/home/pedro-mujica/projects'
2026-02-25 16:17:15,373 INFO o.a.j.e.StandardJMeterEngine: Running the test!
2026-02-25 16:17:15,374 INFO o.a.j.s.SampleEvent: List of sample_variables: []
2026-02-25 16:17:15,374 INFO o.a.j.s.SampleEvent: List of sample_variables: []
2026-02-25 16:17:15,376 INFO o.a.j.e.u.CompoundVariable: Note: Function class names must contain the string: '.functions.'
2026-02-25 16:17:15,376 INFO o.a.j.e.u.CompoundVariable: Note: Function class names must not contain the string: '.gui.'
2026-02-25 16:17:15,407 INFO o.a.j.r.ClassFinder: Will scan jar /opt/apache-jmeter-5.6.3/lib/ext/json-lib-2.4-jdk15.jar with filter ExtendsClassFilter [parents=[interface org.apache.jmeter.functions.Function], inner=false, contains=null, notContains=null]. Consider exposing JMeter plugins via META-INF/services, and add JMeter-Skip-Class-Scanning=true manifest attribute so JMeter can skip classfile scanning
2026-02-25 16:17:15,407 INFO o.a.j.r.ClassFinder: Will scan jar /opt/apache-jmeter-5.6.3/lib/ext/jmeter-plugins-manager-1.11.jar with filter ExtendsClassFilter [parents=[interface org.apache.jmeter.functions.Function], inner=false, contains=null, notContains=null]. Consider exposing JMeter plugins via META-INF/services, and add JMeter-Skip-Class-Scanning=true manifest attribute so JMeter can skip classfile scanning
2026-02-25 16:17:15,410 INFO o.a.j.r.ClassFinder: Will scan jar /opt/apache-jmeter-5.6.3/lib/ext/org.eclipse.paho.client.mqttv3-1.0.2.jar with filter ExtendsClassFilter [parents=[interface org.apache.jmeter.functions.Function], inner=false, contains=null, notContains=null]. Consider exposing JMeter plugins via META-INF/services, and add JMeter-Skip-Class-Scanning=true manifest attribute so JMeter can skip classfile scanning
2026-02-25 16:17:15,411 INFO o.a.j.r.ClassFinder: Will scan jar /opt/apache-jmeter-5.6.3/lib/ext/cmdrunner-2.3.jar with filter ExtendsClassFilter [parents=[interface org.apache.jmeter.functions.Function], inner=false, contains=null, notContains=null]. Consider exposing JMeter plugins via META-INF/services, and add JMeter-Skip-Class-Scanning=true manifest attribute so JMeter can skip classfile scanning
2026-02-25 16:17:15,412 INFO o.a.j.r.ClassFinder: Will scan jar /opt/apache-jmeter-5.6.3/lib/ext/mqtt-jmeter-0.0.1-SNAPSHOT.jar with filter ExtendsClassFilter [parents=[interface org.apache.jmeter.functions.Function], inner=false, contains=null, notContains=null]. Consider exposing JMeter plugins via META-INF/services, and add JMeter-Skip-Class-Scanning=true manifest attribute so JMeter can skip classfile scanning
2026-02-25 16:17:15,412 INFO o.a.j.r.ClassFinder: Will scan jar /opt/apache-jmeter-5.6.3/lib/ext/mqtt-xmeter-2.0.2-jar-with-dependencies.jar with filter ExtendsClassFilter [parents=[interface org.apache.jmeter.functions.Function], inner=false, contains=null, notContains=null]. Consider exposing JMeter plugins via META-INF/services, and add JMeter-Skip-Class-Scanning=true manifest attribute so JMeter can skip classfile scanning
2026-02-25 16:17:15,434 INFO o.a.j.g.u.JMeterMenuBar: setRunning(true, *local*)
2026-02-25 16:17:15,523 INFO o.a.j.e.StandardJMeterEngine: Starting ThreadGroup: 1 : ThreadsLoraDevices
2026-02-25 16:17:15,524 INFO o.a.j.e.StandardJMeterEngine: Starting 1 threads for group ThreadsLoraDevices.
2026-02-25 16:17:15,524 INFO o.a.j.e.StandardJMeterEngine: Thread will continue on error
2026-02-25 16:17:15,525 INFO o.a.j.t.ThreadGroup: Starting thread group... number=1 threads=1 ramp-up=1 delayedStart=false
2026-02-25 16:17:15,529 INFO o.a.j.t.ThreadGroup: Started thread group number 1
2026-02-25 16:17:15,530 INFO o.a.j.e.StandardJMeterEngine: All thread groups have been started
2026-02-25 16:17:15,530 INFO o.a.j.t.JMeterThread: Thread started: ThreadsLoraDevices 1-1
2026-02-25 16:17:17,698 INFO o.a.j.s.SampleResult: Note: Sample TimeStamps are START times
2026-02-25 16:17:17,699 INFO o.a.j.s.SampleResult: sampleresult.default.encoding is set to UTF-8
2026-02-25 16:17:17,699 INFO o.a.j.s.SampleResult: sampleresult.useNanoTime=true
2026-02-25 16:17:17,699 INFO o.a.j.s.SampleResult: sampleresult.nanoThreadSleep=5000
2026-02-25 16:17:17,719 INFO o.a.j.p.m.p.c.BlockingClient: Connecting to tcp://10.81.24.151:1883 with client ID '1772047037701.pedro-muj' and cleanSession is false as a blocking client
2026-02-25 16:17:17,737 INFO o.a.j.p.m.p.c.BlockingClient: Connected
2026-02-25 16:17:17,766 ERROR o.a.j.e.JSR223PostProcessor: Problem in JSR223 script, JSR223 PostProcessor
javax.script.ScriptException: org.codehaus.groovy.control.MultipleCompilationErrorsException: startup failed:
Script2.groovy: 3: Unexpected input: '(' @ line 3, column 9.
   vars.put("counter", c.toString
           ^

1 error

	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.compile(GroovyScriptEngineImpl.java:183) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	at org.apache.jmeter.util.JSR223TestElement.lambda$processFileOrScript$1(JSR223TestElement.java:225) ~[ApacheJMeter_core.jar:5.6.3]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.lambda$doComputeIfAbsent$14(BoundedLocalCache.java:2406) ~[caffeine-2.9.3.jar:?]
	at java.base/java.util.concurrent.ConcurrentHashMap.compute(ConcurrentHashMap.java:1916) ~[?:?]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.doComputeIfAbsent(BoundedLocalCache.java:2404) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.computeIfAbsent(BoundedLocalCache.java:2387) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.LocalCache.computeIfAbsent(LocalCache.java:108) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.LocalManualCache.get(LocalManualCache.java:62) ~[caffeine-2.9.3.jar:?]
	at org.apache.jmeter.util.JSR223TestElement.getCompiledScript(JSR223TestElement.java:252) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.util.JSR223TestElement.processFileOrScript(JSR223TestElement.java:223) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.extractor.JSR223PostProcessor.process(JSR223PostProcessor.java:45) ~[ApacheJMeter_components.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.runPostProcessors(JMeterThread.java:973) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:585) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
	Suppressed: java.lang.IllegalStateException: Unable to compile script StringScriptCacheKey{contents='f78324d73594e82a842199c520580f48'}
		at org.apache.jmeter.util.JSR223TestElement.getCompiledScript(JSR223TestElement.java:264) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.util.JSR223TestElement.processFileOrScript(JSR223TestElement.java:223) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.extractor.JSR223PostProcessor.process(JSR223PostProcessor.java:45) ~[ApacheJMeter_components.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.runPostProcessors(JMeterThread.java:973) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:585) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
		at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
Caused by: org.codehaus.groovy.control.MultipleCompilationErrorsException: startup failed:
Script2.groovy: 3: Unexpected input: '(' @ line 3, column 9.
   vars.put("counter", c.toString
           ^

1 error

	at org.codehaus.groovy.control.ErrorCollector.failIfErrors(ErrorCollector.java:292) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.ErrorCollector.addFatalError(ErrorCollector.java:148) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.collectSyntaxError(AstBuilder.java:4301) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.access$000(AstBuilder.java:176) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder$1.syntaxError(AstBuilder.java:4312) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.ProxyErrorListener.syntaxError(ProxyErrorListener.java:44) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.Parser.notifyErrorListeners(Parser.java:543) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.DefaultErrorStrategy.notifyErrorListeners(DefaultErrorStrategy.java:154) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.reportInputMismatch(DescriptiveErrorStrategy.java:103) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.recover(DescriptiveErrorStrategy.java:55) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.recoverInline(DescriptiveErrorStrategy.java:68) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.Parser.match(Parser.java:213) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.GroovyParser.compilationUnit(GroovyParser.java:362) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildCST(AstBuilder.java:250) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildCST(AstBuilder.java:228) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildAST(AstBuilder.java:269) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.Antlr4ParserPlugin.buildAST(Antlr4ParserPlugin.java:58) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.SourceUnit.buildAST(SourceUnit.java:256) ~[groovy-3.0.20.jar:3.0.20]
	at java.base/java.util.Iterator.forEachRemaining(Iterator.java:133) ~[?:?]
	at java.base/java.util.Spliterators$IteratorSpliterator.forEachRemaining(Spliterators.java:1939) ~[?:?]
	at java.base/java.util.stream.ReferencePipeline$Head.forEach(ReferencePipeline.java:762) ~[?:?]
	at org.codehaus.groovy.control.CompilationUnit.buildASTs(CompilationUnit.java:667) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.CompilationUnit.compile(CompilationUnit.java:633) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.doParseClass(GroovyClassLoader.java:389) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.lambda$parseClass$3(GroovyClassLoader.java:332) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.runtime.memoize.StampedCommonCache.compute(StampedCommonCache.java:163) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.runtime.memoize.StampedCommonCache.getAndPut(StampedCommonCache.java:154) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:330) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:314) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:257) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.getScriptClass(GroovyScriptEngineImpl.java:336) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.compile(GroovyScriptEngineImpl.java:181) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	... 15 more
2026-02-25 16:17:18,792 ERROR o.a.j.e.JSR223PostProcessor: Problem in JSR223 script, JSR223 PostProcessor
javax.script.ScriptException: org.codehaus.groovy.control.MultipleCompilationErrorsException: startup failed:
Script3.groovy: 3: Unexpected input: '(' @ line 3, column 9.
   vars.put("counter", c.toString
           ^

1 error

	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.compile(GroovyScriptEngineImpl.java:183) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	at org.apache.jmeter.util.JSR223TestElement.lambda$processFileOrScript$1(JSR223TestElement.java:225) ~[ApacheJMeter_core.jar:5.6.3]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.lambda$doComputeIfAbsent$14(BoundedLocalCache.java:2406) ~[caffeine-2.9.3.jar:?]
	at java.base/java.util.concurrent.ConcurrentHashMap.compute(ConcurrentHashMap.java:1916) ~[?:?]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.doComputeIfAbsent(BoundedLocalCache.java:2404) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.computeIfAbsent(BoundedLocalCache.java:2387) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.LocalCache.computeIfAbsent(LocalCache.java:108) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.LocalManualCache.get(LocalManualCache.java:62) ~[caffeine-2.9.3.jar:?]
	at org.apache.jmeter.util.JSR223TestElement.getCompiledScript(JSR223TestElement.java:252) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.util.JSR223TestElement.processFileOrScript(JSR223TestElement.java:223) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.extractor.JSR223PostProcessor.process(JSR223PostProcessor.java:45) ~[ApacheJMeter_components.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.runPostProcessors(JMeterThread.java:973) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:585) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
	Suppressed: java.lang.IllegalStateException: Unable to compile script StringScriptCacheKey{contents='f78324d73594e82a842199c520580f48'}
		at org.apache.jmeter.util.JSR223TestElement.getCompiledScript(JSR223TestElement.java:264) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.util.JSR223TestElement.processFileOrScript(JSR223TestElement.java:223) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.extractor.JSR223PostProcessor.process(JSR223PostProcessor.java:45) ~[ApacheJMeter_components.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.runPostProcessors(JMeterThread.java:973) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:585) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
		at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
Caused by: org.codehaus.groovy.control.MultipleCompilationErrorsException: startup failed:
Script3.groovy: 3: Unexpected input: '(' @ line 3, column 9.
   vars.put("counter", c.toString
           ^

1 error

	at org.codehaus.groovy.control.ErrorCollector.failIfErrors(ErrorCollector.java:292) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.ErrorCollector.addFatalError(ErrorCollector.java:148) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.collectSyntaxError(AstBuilder.java:4301) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.access$000(AstBuilder.java:176) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder$1.syntaxError(AstBuilder.java:4312) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.ProxyErrorListener.syntaxError(ProxyErrorListener.java:44) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.Parser.notifyErrorListeners(Parser.java:543) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.DefaultErrorStrategy.notifyErrorListeners(DefaultErrorStrategy.java:154) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.reportInputMismatch(DescriptiveErrorStrategy.java:103) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.recover(DescriptiveErrorStrategy.java:55) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.recoverInline(DescriptiveErrorStrategy.java:68) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.Parser.match(Parser.java:213) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.GroovyParser.compilationUnit(GroovyParser.java:362) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildCST(AstBuilder.java:250) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildCST(AstBuilder.java:228) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildAST(AstBuilder.java:269) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.Antlr4ParserPlugin.buildAST(Antlr4ParserPlugin.java:58) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.SourceUnit.buildAST(SourceUnit.java:256) ~[groovy-3.0.20.jar:3.0.20]
	at java.base/java.util.Iterator.forEachRemaining(Iterator.java:133) ~[?:?]
	at java.base/java.util.Spliterators$IteratorSpliterator.forEachRemaining(Spliterators.java:1939) ~[?:?]
	at java.base/java.util.stream.ReferencePipeline$Head.forEach(ReferencePipeline.java:762) ~[?:?]
	at org.codehaus.groovy.control.CompilationUnit.buildASTs(CompilationUnit.java:667) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.CompilationUnit.compile(CompilationUnit.java:633) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.doParseClass(GroovyClassLoader.java:389) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.lambda$parseClass$3(GroovyClassLoader.java:332) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.runtime.memoize.StampedCommonCache.compute(StampedCommonCache.java:163) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.runtime.memoize.StampedCommonCache.getAndPut(StampedCommonCache.java:154) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:330) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:314) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:257) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.getScriptClass(GroovyScriptEngineImpl.java:336) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.compile(GroovyScriptEngineImpl.java:181) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	... 15 more
2026-02-25 16:17:19,806 ERROR o.a.j.e.JSR223PostProcessor: Problem in JSR223 script, JSR223 PostProcessor
javax.script.ScriptException: org.codehaus.groovy.control.MultipleCompilationErrorsException: startup failed:
Script4.groovy: 3: Unexpected input: '(' @ line 3, column 9.
   vars.put("counter", c.toString
           ^

1 error

	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.compile(GroovyScriptEngineImpl.java:183) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	at org.apache.jmeter.util.JSR223TestElement.lambda$processFileOrScript$1(JSR223TestElement.java:225) ~[ApacheJMeter_core.jar:5.6.3]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.lambda$doComputeIfAbsent$14(BoundedLocalCache.java:2406) ~[caffeine-2.9.3.jar:?]
	at java.base/java.util.concurrent.ConcurrentHashMap.compute(ConcurrentHashMap.java:1916) ~[?:?]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.doComputeIfAbsent(BoundedLocalCache.java:2404) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.computeIfAbsent(BoundedLocalCache.java:2387) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.LocalCache.computeIfAbsent(LocalCache.java:108) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.LocalManualCache.get(LocalManualCache.java:62) ~[caffeine-2.9.3.jar:?]
	at org.apache.jmeter.util.JSR223TestElement.getCompiledScript(JSR223TestElement.java:252) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.util.JSR223TestElement.processFileOrScript(JSR223TestElement.java:223) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.extractor.JSR223PostProcessor.process(JSR223PostProcessor.java:45) ~[ApacheJMeter_components.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.runPostProcessors(JMeterThread.java:973) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:585) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
	Suppressed: java.lang.IllegalStateException: Unable to compile script StringScriptCacheKey{contents='f78324d73594e82a842199c520580f48'}
		at org.apache.jmeter.util.JSR223TestElement.getCompiledScript(JSR223TestElement.java:264) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.util.JSR223TestElement.processFileOrScript(JSR223TestElement.java:223) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.extractor.JSR223PostProcessor.process(JSR223PostProcessor.java:45) ~[ApacheJMeter_components.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.runPostProcessors(JMeterThread.java:973) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:585) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
		at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
Caused by: org.codehaus.groovy.control.MultipleCompilationErrorsException: startup failed:
Script4.groovy: 3: Unexpected input: '(' @ line 3, column 9.
   vars.put("counter", c.toString
           ^

1 error

	at org.codehaus.groovy.control.ErrorCollector.failIfErrors(ErrorCollector.java:292) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.ErrorCollector.addFatalError(ErrorCollector.java:148) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.collectSyntaxError(AstBuilder.java:4301) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.access$000(AstBuilder.java:176) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder$1.syntaxError(AstBuilder.java:4312) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.ProxyErrorListener.syntaxError(ProxyErrorListener.java:44) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.Parser.notifyErrorListeners(Parser.java:543) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.DefaultErrorStrategy.notifyErrorListeners(DefaultErrorStrategy.java:154) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.reportInputMismatch(DescriptiveErrorStrategy.java:103) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.recover(DescriptiveErrorStrategy.java:55) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.recoverInline(DescriptiveErrorStrategy.java:68) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.Parser.match(Parser.java:213) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.GroovyParser.compilationUnit(GroovyParser.java:362) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildCST(AstBuilder.java:250) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildCST(AstBuilder.java:228) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildAST(AstBuilder.java:269) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.Antlr4ParserPlugin.buildAST(Antlr4ParserPlugin.java:58) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.SourceUnit.buildAST(SourceUnit.java:256) ~[groovy-3.0.20.jar:3.0.20]
	at java.base/java.util.Iterator.forEachRemaining(Iterator.java:133) ~[?:?]
	at java.base/java.util.Spliterators$IteratorSpliterator.forEachRemaining(Spliterators.java:1939) ~[?:?]
	at java.base/java.util.stream.ReferencePipeline$Head.forEach(ReferencePipeline.java:762) ~[?:?]
	at org.codehaus.groovy.control.CompilationUnit.buildASTs(CompilationUnit.java:667) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.CompilationUnit.compile(CompilationUnit.java:633) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.doParseClass(GroovyClassLoader.java:389) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.lambda$parseClass$3(GroovyClassLoader.java:332) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.runtime.memoize.StampedCommonCache.compute(StampedCommonCache.java:163) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.runtime.memoize.StampedCommonCache.getAndPut(StampedCommonCache.java:154) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:330) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:314) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:257) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.getScriptClass(GroovyScriptEngineImpl.java:336) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.compile(GroovyScriptEngineImpl.java:181) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	... 15 more
2026-02-25 16:17:20,818 ERROR o.a.j.e.JSR223PostProcessor: Problem in JSR223 script, JSR223 PostProcessor
javax.script.ScriptException: org.codehaus.groovy.control.MultipleCompilationErrorsException: startup failed:
Script5.groovy: 3: Unexpected input: '(' @ line 3, column 9.
   vars.put("counter", c.toString
           ^

1 error

	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.compile(GroovyScriptEngineImpl.java:183) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	at org.apache.jmeter.util.JSR223TestElement.lambda$processFileOrScript$1(JSR223TestElement.java:225) ~[ApacheJMeter_core.jar:5.6.3]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.lambda$doComputeIfAbsent$14(BoundedLocalCache.java:2406) ~[caffeine-2.9.3.jar:?]
	at java.base/java.util.concurrent.ConcurrentHashMap.compute(ConcurrentHashMap.java:1916) ~[?:?]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.doComputeIfAbsent(BoundedLocalCache.java:2404) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.computeIfAbsent(BoundedLocalCache.java:2387) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.LocalCache.computeIfAbsent(LocalCache.java:108) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.LocalManualCache.get(LocalManualCache.java:62) ~[caffeine-2.9.3.jar:?]
	at org.apache.jmeter.util.JSR223TestElement.getCompiledScript(JSR223TestElement.java:252) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.util.JSR223TestElement.processFileOrScript(JSR223TestElement.java:223) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.extractor.JSR223PostProcessor.process(JSR223PostProcessor.java:45) ~[ApacheJMeter_components.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.runPostProcessors(JMeterThread.java:973) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:585) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
	Suppressed: java.lang.IllegalStateException: Unable to compile script StringScriptCacheKey{contents='f78324d73594e82a842199c520580f48'}
		at org.apache.jmeter.util.JSR223TestElement.getCompiledScript(JSR223TestElement.java:264) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.util.JSR223TestElement.processFileOrScript(JSR223TestElement.java:223) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.extractor.JSR223PostProcessor.process(JSR223PostProcessor.java:45) ~[ApacheJMeter_components.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.runPostProcessors(JMeterThread.java:973) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:585) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
		at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
Caused by: org.codehaus.groovy.control.MultipleCompilationErrorsException: startup failed:
Script5.groovy: 3: Unexpected input: '(' @ line 3, column 9.
   vars.put("counter", c.toString
           ^

1 error

	at org.codehaus.groovy.control.ErrorCollector.failIfErrors(ErrorCollector.java:292) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.ErrorCollector.addFatalError(ErrorCollector.java:148) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.collectSyntaxError(AstBuilder.java:4301) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.access$000(AstBuilder.java:176) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder$1.syntaxError(AstBuilder.java:4312) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.ProxyErrorListener.syntaxError(ProxyErrorListener.java:44) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.Parser.notifyErrorListeners(Parser.java:543) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.DefaultErrorStrategy.notifyErrorListeners(DefaultErrorStrategy.java:154) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.reportInputMismatch(DescriptiveErrorStrategy.java:103) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.recover(DescriptiveErrorStrategy.java:55) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.recoverInline(DescriptiveErrorStrategy.java:68) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.Parser.match(Parser.java:213) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.GroovyParser.compilationUnit(GroovyParser.java:362) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildCST(AstBuilder.java:250) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildCST(AstBuilder.java:228) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildAST(AstBuilder.java:269) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.Antlr4ParserPlugin.buildAST(Antlr4ParserPlugin.java:58) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.SourceUnit.buildAST(SourceUnit.java:256) ~[groovy-3.0.20.jar:3.0.20]
	at java.base/java.util.Iterator.forEachRemaining(Iterator.java:133) ~[?:?]
	at java.base/java.util.Spliterators$IteratorSpliterator.forEachRemaining(Spliterators.java:1939) ~[?:?]
	at java.base/java.util.stream.ReferencePipeline$Head.forEach(ReferencePipeline.java:762) ~[?:?]
	at org.codehaus.groovy.control.CompilationUnit.buildASTs(CompilationUnit.java:667) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.CompilationUnit.compile(CompilationUnit.java:633) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.doParseClass(GroovyClassLoader.java:389) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.lambda$parseClass$3(GroovyClassLoader.java:332) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.runtime.memoize.StampedCommonCache.compute(StampedCommonCache.java:163) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.runtime.memoize.StampedCommonCache.getAndPut(StampedCommonCache.java:154) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:330) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:314) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:257) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.getScriptClass(GroovyScriptEngineImpl.java:336) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.compile(GroovyScriptEngineImpl.java:181) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	... 15 more
2026-02-25 16:17:21,832 ERROR o.a.j.e.JSR223PostProcessor: Problem in JSR223 script, JSR223 PostProcessor
javax.script.ScriptException: org.codehaus.groovy.control.MultipleCompilationErrorsException: startup failed:
Script6.groovy: 3: Unexpected input: '(' @ line 3, column 9.
   vars.put("counter", c.toString
           ^

1 error

	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.compile(GroovyScriptEngineImpl.java:183) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	at org.apache.jmeter.util.JSR223TestElement.lambda$processFileOrScript$1(JSR223TestElement.java:225) ~[ApacheJMeter_core.jar:5.6.3]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.lambda$doComputeIfAbsent$14(BoundedLocalCache.java:2406) ~[caffeine-2.9.3.jar:?]
	at java.base/java.util.concurrent.ConcurrentHashMap.compute(ConcurrentHashMap.java:1916) ~[?:?]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.doComputeIfAbsent(BoundedLocalCache.java:2404) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.computeIfAbsent(BoundedLocalCache.java:2387) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.LocalCache.computeIfAbsent(LocalCache.java:108) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.LocalManualCache.get(LocalManualCache.java:62) ~[caffeine-2.9.3.jar:?]
	at org.apache.jmeter.util.JSR223TestElement.getCompiledScript(JSR223TestElement.java:252) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.util.JSR223TestElement.processFileOrScript(JSR223TestElement.java:223) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.extractor.JSR223PostProcessor.process(JSR223PostProcessor.java:45) ~[ApacheJMeter_components.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.runPostProcessors(JMeterThread.java:973) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:585) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
	Suppressed: java.lang.IllegalStateException: Unable to compile script StringScriptCacheKey{contents='f78324d73594e82a842199c520580f48'}
		at org.apache.jmeter.util.JSR223TestElement.getCompiledScript(JSR223TestElement.java:264) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.util.JSR223TestElement.processFileOrScript(JSR223TestElement.java:223) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.extractor.JSR223PostProcessor.process(JSR223PostProcessor.java:45) ~[ApacheJMeter_components.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.runPostProcessors(JMeterThread.java:973) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:585) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
		at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
Caused by: org.codehaus.groovy.control.MultipleCompilationErrorsException: startup failed:
Script6.groovy: 3: Unexpected input: '(' @ line 3, column 9.
   vars.put("counter", c.toString
           ^

1 error

	at org.codehaus.groovy.control.ErrorCollector.failIfErrors(ErrorCollector.java:292) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.ErrorCollector.addFatalError(ErrorCollector.java:148) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.collectSyntaxError(AstBuilder.java:4301) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.access$000(AstBuilder.java:176) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder$1.syntaxError(AstBuilder.java:4312) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.ProxyErrorListener.syntaxError(ProxyErrorListener.java:44) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.Parser.notifyErrorListeners(Parser.java:543) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.DefaultErrorStrategy.notifyErrorListeners(DefaultErrorStrategy.java:154) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.reportInputMismatch(DescriptiveErrorStrategy.java:103) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.recover(DescriptiveErrorStrategy.java:55) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.recoverInline(DescriptiveErrorStrategy.java:68) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.Parser.match(Parser.java:213) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.GroovyParser.compilationUnit(GroovyParser.java:362) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildCST(AstBuilder.java:250) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildCST(AstBuilder.java:228) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildAST(AstBuilder.java:269) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.Antlr4ParserPlugin.buildAST(Antlr4ParserPlugin.java:58) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.SourceUnit.buildAST(SourceUnit.java:256) ~[groovy-3.0.20.jar:3.0.20]
	at java.base/java.util.Iterator.forEachRemaining(Iterator.java:133) ~[?:?]
	at java.base/java.util.Spliterators$IteratorSpliterator.forEachRemaining(Spliterators.java:1939) ~[?:?]
	at java.base/java.util.stream.ReferencePipeline$Head.forEach(ReferencePipeline.java:762) ~[?:?]
	at org.codehaus.groovy.control.CompilationUnit.buildASTs(CompilationUnit.java:667) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.CompilationUnit.compile(CompilationUnit.java:633) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.doParseClass(GroovyClassLoader.java:389) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.lambda$parseClass$3(GroovyClassLoader.java:332) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.runtime.memoize.StampedCommonCache.compute(StampedCommonCache.java:163) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.runtime.memoize.StampedCommonCache.getAndPut(StampedCommonCache.java:154) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:330) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:314) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:257) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.getScriptClass(GroovyScriptEngineImpl.java:336) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.compile(GroovyScriptEngineImpl.java:181) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	... 15 more
2026-02-25 16:17:22,845 ERROR o.a.j.e.JSR223PostProcessor: Problem in JSR223 script, JSR223 PostProcessor
javax.script.ScriptException: org.codehaus.groovy.control.MultipleCompilationErrorsException: startup failed:
Script7.groovy: 3: Unexpected input: '(' @ line 3, column 9.
   vars.put("counter", c.toString
           ^

1 error

	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.compile(GroovyScriptEngineImpl.java:183) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	at org.apache.jmeter.util.JSR223TestElement.lambda$processFileOrScript$1(JSR223TestElement.java:225) ~[ApacheJMeter_core.jar:5.6.3]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.lambda$doComputeIfAbsent$14(BoundedLocalCache.java:2406) ~[caffeine-2.9.3.jar:?]
	at java.base/java.util.concurrent.ConcurrentHashMap.compute(ConcurrentHashMap.java:1916) ~[?:?]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.doComputeIfAbsent(BoundedLocalCache.java:2404) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.computeIfAbsent(BoundedLocalCache.java:2387) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.LocalCache.computeIfAbsent(LocalCache.java:108) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.LocalManualCache.get(LocalManualCache.java:62) ~[caffeine-2.9.3.jar:?]
	at org.apache.jmeter.util.JSR223TestElement.getCompiledScript(JSR223TestElement.java:252) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.util.JSR223TestElement.processFileOrScript(JSR223TestElement.java:223) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.extractor.JSR223PostProcessor.process(JSR223PostProcessor.java:45) ~[ApacheJMeter_components.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.runPostProcessors(JMeterThread.java:973) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:585) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
	Suppressed: java.lang.IllegalStateException: Unable to compile script StringScriptCacheKey{contents='f78324d73594e82a842199c520580f48'}
		at org.apache.jmeter.util.JSR223TestElement.getCompiledScript(JSR223TestElement.java:264) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.util.JSR223TestElement.processFileOrScript(JSR223TestElement.java:223) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.extractor.JSR223PostProcessor.process(JSR223PostProcessor.java:45) ~[ApacheJMeter_components.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.runPostProcessors(JMeterThread.java:973) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:585) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
		at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
Caused by: org.codehaus.groovy.control.MultipleCompilationErrorsException: startup failed:
Script7.groovy: 3: Unexpected input: '(' @ line 3, column 9.
   vars.put("counter", c.toString
           ^

1 error

	at org.codehaus.groovy.control.ErrorCollector.failIfErrors(ErrorCollector.java:292) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.ErrorCollector.addFatalError(ErrorCollector.java:148) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.collectSyntaxError(AstBuilder.java:4301) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.access$000(AstBuilder.java:176) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder$1.syntaxError(AstBuilder.java:4312) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.ProxyErrorListener.syntaxError(ProxyErrorListener.java:44) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.Parser.notifyErrorListeners(Parser.java:543) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.DefaultErrorStrategy.notifyErrorListeners(DefaultErrorStrategy.java:154) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.reportInputMismatch(DescriptiveErrorStrategy.java:103) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.recover(DescriptiveErrorStrategy.java:55) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.recoverInline(DescriptiveErrorStrategy.java:68) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.Parser.match(Parser.java:213) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.GroovyParser.compilationUnit(GroovyParser.java:362) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildCST(AstBuilder.java:250) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildCST(AstBuilder.java:228) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildAST(AstBuilder.java:269) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.Antlr4ParserPlugin.buildAST(Antlr4ParserPlugin.java:58) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.SourceUnit.buildAST(SourceUnit.java:256) ~[groovy-3.0.20.jar:3.0.20]
	at java.base/java.util.Iterator.forEachRemaining(Iterator.java:133) ~[?:?]
	at java.base/java.util.Spliterators$IteratorSpliterator.forEachRemaining(Spliterators.java:1939) ~[?:?]
	at java.base/java.util.stream.ReferencePipeline$Head.forEach(ReferencePipeline.java:762) ~[?:?]
	at org.codehaus.groovy.control.CompilationUnit.buildASTs(CompilationUnit.java:667) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.CompilationUnit.compile(CompilationUnit.java:633) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.doParseClass(GroovyClassLoader.java:389) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.lambda$parseClass$3(GroovyClassLoader.java:332) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.runtime.memoize.StampedCommonCache.compute(StampedCommonCache.java:163) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.runtime.memoize.StampedCommonCache.getAndPut(StampedCommonCache.java:154) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:330) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:314) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:257) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.getScriptClass(GroovyScriptEngineImpl.java:336) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.compile(GroovyScriptEngineImpl.java:181) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	... 15 more
2026-02-25 16:17:23,857 ERROR o.a.j.e.JSR223PostProcessor: Problem in JSR223 script, JSR223 PostProcessor
javax.script.ScriptException: org.codehaus.groovy.control.MultipleCompilationErrorsException: startup failed:
Script8.groovy: 3: Unexpected input: '(' @ line 3, column 9.
   vars.put("counter", c.toString
           ^

1 error

	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.compile(GroovyScriptEngineImpl.java:183) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	at org.apache.jmeter.util.JSR223TestElement.lambda$processFileOrScript$1(JSR223TestElement.java:225) ~[ApacheJMeter_core.jar:5.6.3]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.lambda$doComputeIfAbsent$14(BoundedLocalCache.java:2406) ~[caffeine-2.9.3.jar:?]
	at java.base/java.util.concurrent.ConcurrentHashMap.compute(ConcurrentHashMap.java:1916) ~[?:?]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.doComputeIfAbsent(BoundedLocalCache.java:2404) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.computeIfAbsent(BoundedLocalCache.java:2387) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.LocalCache.computeIfAbsent(LocalCache.java:108) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.LocalManualCache.get(LocalManualCache.java:62) ~[caffeine-2.9.3.jar:?]
	at org.apache.jmeter.util.JSR223TestElement.getCompiledScript(JSR223TestElement.java:252) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.util.JSR223TestElement.processFileOrScript(JSR223TestElement.java:223) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.extractor.JSR223PostProcessor.process(JSR223PostProcessor.java:45) ~[ApacheJMeter_components.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.runPostProcessors(JMeterThread.java:973) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:585) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
	Suppressed: java.lang.IllegalStateException: Unable to compile script StringScriptCacheKey{contents='f78324d73594e82a842199c520580f48'}
		at org.apache.jmeter.util.JSR223TestElement.getCompiledScript(JSR223TestElement.java:264) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.util.JSR223TestElement.processFileOrScript(JSR223TestElement.java:223) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.extractor.JSR223PostProcessor.process(JSR223PostProcessor.java:45) ~[ApacheJMeter_components.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.runPostProcessors(JMeterThread.java:973) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:585) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
		at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
Caused by: org.codehaus.groovy.control.MultipleCompilationErrorsException: startup failed:
Script8.groovy: 3: Unexpected input: '(' @ line 3, column 9.
   vars.put("counter", c.toString
           ^

1 error

	at org.codehaus.groovy.control.ErrorCollector.failIfErrors(ErrorCollector.java:292) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.ErrorCollector.addFatalError(ErrorCollector.java:148) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.collectSyntaxError(AstBuilder.java:4301) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.access$000(AstBuilder.java:176) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder$1.syntaxError(AstBuilder.java:4312) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.ProxyErrorListener.syntaxError(ProxyErrorListener.java:44) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.Parser.notifyErrorListeners(Parser.java:543) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.DefaultErrorStrategy.notifyErrorListeners(DefaultErrorStrategy.java:154) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.reportInputMismatch(DescriptiveErrorStrategy.java:103) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.recover(DescriptiveErrorStrategy.java:55) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.recoverInline(DescriptiveErrorStrategy.java:68) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.Parser.match(Parser.java:213) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.GroovyParser.compilationUnit(GroovyParser.java:362) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildCST(AstBuilder.java:250) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildCST(AstBuilder.java:228) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildAST(AstBuilder.java:269) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.Antlr4ParserPlugin.buildAST(Antlr4ParserPlugin.java:58) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.SourceUnit.buildAST(SourceUnit.java:256) ~[groovy-3.0.20.jar:3.0.20]
	at java.base/java.util.Iterator.forEachRemaining(Iterator.java:133) ~[?:?]
	at java.base/java.util.Spliterators$IteratorSpliterator.forEachRemaining(Spliterators.java:1939) ~[?:?]
	at java.base/java.util.stream.ReferencePipeline$Head.forEach(ReferencePipeline.java:762) ~[?:?]
	at org.codehaus.groovy.control.CompilationUnit.buildASTs(CompilationUnit.java:667) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.CompilationUnit.compile(CompilationUnit.java:633) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.doParseClass(GroovyClassLoader.java:389) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.lambda$parseClass$3(GroovyClassLoader.java:332) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.runtime.memoize.StampedCommonCache.compute(StampedCommonCache.java:163) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.runtime.memoize.StampedCommonCache.getAndPut(StampedCommonCache.java:154) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:330) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:314) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:257) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.getScriptClass(GroovyScriptEngineImpl.java:336) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.compile(GroovyScriptEngineImpl.java:181) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	... 15 more
2026-02-25 16:17:24,869 ERROR o.a.j.e.JSR223PostProcessor: Problem in JSR223 script, JSR223 PostProcessor
javax.script.ScriptException: org.codehaus.groovy.control.MultipleCompilationErrorsException: startup failed:
Script9.groovy: 3: Unexpected input: '(' @ line 3, column 9.
   vars.put("counter", c.toString
           ^

1 error

	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.compile(GroovyScriptEngineImpl.java:183) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	at org.apache.jmeter.util.JSR223TestElement.lambda$processFileOrScript$1(JSR223TestElement.java:225) ~[ApacheJMeter_core.jar:5.6.3]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.lambda$doComputeIfAbsent$14(BoundedLocalCache.java:2406) ~[caffeine-2.9.3.jar:?]
	at java.base/java.util.concurrent.ConcurrentHashMap.compute(ConcurrentHashMap.java:1916) ~[?:?]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.doComputeIfAbsent(BoundedLocalCache.java:2404) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.computeIfAbsent(BoundedLocalCache.java:2387) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.LocalCache.computeIfAbsent(LocalCache.java:108) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.LocalManualCache.get(LocalManualCache.java:62) ~[caffeine-2.9.3.jar:?]
	at org.apache.jmeter.util.JSR223TestElement.getCompiledScript(JSR223TestElement.java:252) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.util.JSR223TestElement.processFileOrScript(JSR223TestElement.java:223) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.extractor.JSR223PostProcessor.process(JSR223PostProcessor.java:45) ~[ApacheJMeter_components.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.runPostProcessors(JMeterThread.java:973) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:585) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
	Suppressed: java.lang.IllegalStateException: Unable to compile script StringScriptCacheKey{contents='f78324d73594e82a842199c520580f48'}
		at org.apache.jmeter.util.JSR223TestElement.getCompiledScript(JSR223TestElement.java:264) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.util.JSR223TestElement.processFileOrScript(JSR223TestElement.java:223) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.extractor.JSR223PostProcessor.process(JSR223PostProcessor.java:45) ~[ApacheJMeter_components.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.runPostProcessors(JMeterThread.java:973) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:585) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
		at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
Caused by: org.codehaus.groovy.control.MultipleCompilationErrorsException: startup failed:
Script9.groovy: 3: Unexpected input: '(' @ line 3, column 9.
   vars.put("counter", c.toString
           ^

1 error

	at org.codehaus.groovy.control.ErrorCollector.failIfErrors(ErrorCollector.java:292) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.ErrorCollector.addFatalError(ErrorCollector.java:148) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.collectSyntaxError(AstBuilder.java:4301) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.access$000(AstBuilder.java:176) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder$1.syntaxError(AstBuilder.java:4312) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.ProxyErrorListener.syntaxError(ProxyErrorListener.java:44) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.Parser.notifyErrorListeners(Parser.java:543) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.DefaultErrorStrategy.notifyErrorListeners(DefaultErrorStrategy.java:154) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.reportInputMismatch(DescriptiveErrorStrategy.java:103) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.recover(DescriptiveErrorStrategy.java:55) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.recoverInline(DescriptiveErrorStrategy.java:68) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.Parser.match(Parser.java:213) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.GroovyParser.compilationUnit(GroovyParser.java:362) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildCST(AstBuilder.java:250) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildCST(AstBuilder.java:228) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildAST(AstBuilder.java:269) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.Antlr4ParserPlugin.buildAST(Antlr4ParserPlugin.java:58) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.SourceUnit.buildAST(SourceUnit.java:256) ~[groovy-3.0.20.jar:3.0.20]
	at java.base/java.util.Iterator.forEachRemaining(Iterator.java:133) ~[?:?]
	at java.base/java.util.Spliterators$IteratorSpliterator.forEachRemaining(Spliterators.java:1939) ~[?:?]
	at java.base/java.util.stream.ReferencePipeline$Head.forEach(ReferencePipeline.java:762) ~[?:?]
	at org.codehaus.groovy.control.CompilationUnit.buildASTs(CompilationUnit.java:667) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.CompilationUnit.compile(CompilationUnit.java:633) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.doParseClass(GroovyClassLoader.java:389) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.lambda$parseClass$3(GroovyClassLoader.java:332) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.runtime.memoize.StampedCommonCache.compute(StampedCommonCache.java:163) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.runtime.memoize.StampedCommonCache.getAndPut(StampedCommonCache.java:154) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:330) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:314) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:257) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.getScriptClass(GroovyScriptEngineImpl.java:336) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.compile(GroovyScriptEngineImpl.java:181) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	... 15 more
2026-02-25 16:17:25,880 ERROR o.a.j.e.JSR223PostProcessor: Problem in JSR223 script, JSR223 PostProcessor
javax.script.ScriptException: org.codehaus.groovy.control.MultipleCompilationErrorsException: startup failed:
Script10.groovy: 3: Unexpected input: '(' @ line 3, column 9.
   vars.put("counter", c.toString
           ^

1 error

	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.compile(GroovyScriptEngineImpl.java:183) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	at org.apache.jmeter.util.JSR223TestElement.lambda$processFileOrScript$1(JSR223TestElement.java:225) ~[ApacheJMeter_core.jar:5.6.3]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.lambda$doComputeIfAbsent$14(BoundedLocalCache.java:2406) ~[caffeine-2.9.3.jar:?]
	at java.base/java.util.concurrent.ConcurrentHashMap.compute(ConcurrentHashMap.java:1916) ~[?:?]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.doComputeIfAbsent(BoundedLocalCache.java:2404) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.computeIfAbsent(BoundedLocalCache.java:2387) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.LocalCache.computeIfAbsent(LocalCache.java:108) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.LocalManualCache.get(LocalManualCache.java:62) ~[caffeine-2.9.3.jar:?]
	at org.apache.jmeter.util.JSR223TestElement.getCompiledScript(JSR223TestElement.java:252) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.util.JSR223TestElement.processFileOrScript(JSR223TestElement.java:223) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.extractor.JSR223PostProcessor.process(JSR223PostProcessor.java:45) ~[ApacheJMeter_components.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.runPostProcessors(JMeterThread.java:973) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:585) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
	Suppressed: java.lang.IllegalStateException: Unable to compile script StringScriptCacheKey{contents='f78324d73594e82a842199c520580f48'}
		at org.apache.jmeter.util.JSR223TestElement.getCompiledScript(JSR223TestElement.java:264) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.util.JSR223TestElement.processFileOrScript(JSR223TestElement.java:223) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.extractor.JSR223PostProcessor.process(JSR223PostProcessor.java:45) ~[ApacheJMeter_components.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.runPostProcessors(JMeterThread.java:973) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:585) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
		at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
Caused by: org.codehaus.groovy.control.MultipleCompilationErrorsException: startup failed:
Script10.groovy: 3: Unexpected input: '(' @ line 3, column 9.
   vars.put("counter", c.toString
           ^

1 error

	at org.codehaus.groovy.control.ErrorCollector.failIfErrors(ErrorCollector.java:292) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.ErrorCollector.addFatalError(ErrorCollector.java:148) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.collectSyntaxError(AstBuilder.java:4301) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.access$000(AstBuilder.java:176) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder$1.syntaxError(AstBuilder.java:4312) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.ProxyErrorListener.syntaxError(ProxyErrorListener.java:44) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.Parser.notifyErrorListeners(Parser.java:543) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.DefaultErrorStrategy.notifyErrorListeners(DefaultErrorStrategy.java:154) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.reportInputMismatch(DescriptiveErrorStrategy.java:103) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.recover(DescriptiveErrorStrategy.java:55) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.recoverInline(DescriptiveErrorStrategy.java:68) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.Parser.match(Parser.java:213) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.GroovyParser.compilationUnit(GroovyParser.java:362) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildCST(AstBuilder.java:250) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildCST(AstBuilder.java:228) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildAST(AstBuilder.java:269) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.Antlr4ParserPlugin.buildAST(Antlr4ParserPlugin.java:58) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.SourceUnit.buildAST(SourceUnit.java:256) ~[groovy-3.0.20.jar:3.0.20]
	at java.base/java.util.Iterator.forEachRemaining(Iterator.java:133) ~[?:?]
	at java.base/java.util.Spliterators$IteratorSpliterator.forEachRemaining(Spliterators.java:1939) ~[?:?]
	at java.base/java.util.stream.ReferencePipeline$Head.forEach(ReferencePipeline.java:762) ~[?:?]
	at org.codehaus.groovy.control.CompilationUnit.buildASTs(CompilationUnit.java:667) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.CompilationUnit.compile(CompilationUnit.java:633) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.doParseClass(GroovyClassLoader.java:389) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.lambda$parseClass$3(GroovyClassLoader.java:332) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.runtime.memoize.StampedCommonCache.compute(StampedCommonCache.java:163) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.runtime.memoize.StampedCommonCache.getAndPut(StampedCommonCache.java:154) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:330) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:314) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:257) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.getScriptClass(GroovyScriptEngineImpl.java:336) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.compile(GroovyScriptEngineImpl.java:181) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	... 15 more
2026-02-25 16:17:26,892 ERROR o.a.j.e.JSR223PostProcessor: Problem in JSR223 script, JSR223 PostProcessor
javax.script.ScriptException: org.codehaus.groovy.control.MultipleCompilationErrorsException: startup failed:
Script11.groovy: 3: Unexpected input: '(' @ line 3, column 9.
   vars.put("counter", c.toString
           ^

1 error

	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.compile(GroovyScriptEngineImpl.java:183) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	at org.apache.jmeter.util.JSR223TestElement.lambda$processFileOrScript$1(JSR223TestElement.java:225) ~[ApacheJMeter_core.jar:5.6.3]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.lambda$doComputeIfAbsent$14(BoundedLocalCache.java:2406) ~[caffeine-2.9.3.jar:?]
	at java.base/java.util.concurrent.ConcurrentHashMap.compute(ConcurrentHashMap.java:1916) ~[?:?]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.doComputeIfAbsent(BoundedLocalCache.java:2404) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.computeIfAbsent(BoundedLocalCache.java:2387) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.LocalCache.computeIfAbsent(LocalCache.java:108) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.LocalManualCache.get(LocalManualCache.java:62) ~[caffeine-2.9.3.jar:?]
	at org.apache.jmeter.util.JSR223TestElement.getCompiledScript(JSR223TestElement.java:252) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.util.JSR223TestElement.processFileOrScript(JSR223TestElement.java:223) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.extractor.JSR223PostProcessor.process(JSR223PostProcessor.java:45) ~[ApacheJMeter_components.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.runPostProcessors(JMeterThread.java:973) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:585) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
	Suppressed: java.lang.IllegalStateException: Unable to compile script StringScriptCacheKey{contents='f78324d73594e82a842199c520580f48'}
		at org.apache.jmeter.util.JSR223TestElement.getCompiledScript(JSR223TestElement.java:264) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.util.JSR223TestElement.processFileOrScript(JSR223TestElement.java:223) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.extractor.JSR223PostProcessor.process(JSR223PostProcessor.java:45) ~[ApacheJMeter_components.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.runPostProcessors(JMeterThread.java:973) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:585) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
		at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
Caused by: org.codehaus.groovy.control.MultipleCompilationErrorsException: startup failed:
Script11.groovy: 3: Unexpected input: '(' @ line 3, column 9.
   vars.put("counter", c.toString
           ^

1 error

	at org.codehaus.groovy.control.ErrorCollector.failIfErrors(ErrorCollector.java:292) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.ErrorCollector.addFatalError(ErrorCollector.java:148) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.collectSyntaxError(AstBuilder.java:4301) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.access$000(AstBuilder.java:176) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder$1.syntaxError(AstBuilder.java:4312) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.ProxyErrorListener.syntaxError(ProxyErrorListener.java:44) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.Parser.notifyErrorListeners(Parser.java:543) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.DefaultErrorStrategy.notifyErrorListeners(DefaultErrorStrategy.java:154) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.reportInputMismatch(DescriptiveErrorStrategy.java:103) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.recover(DescriptiveErrorStrategy.java:55) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.recoverInline(DescriptiveErrorStrategy.java:68) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.Parser.match(Parser.java:213) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.GroovyParser.compilationUnit(GroovyParser.java:362) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildCST(AstBuilder.java:250) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildCST(AstBuilder.java:228) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildAST(AstBuilder.java:269) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.Antlr4ParserPlugin.buildAST(Antlr4ParserPlugin.java:58) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.SourceUnit.buildAST(SourceUnit.java:256) ~[groovy-3.0.20.jar:3.0.20]
	at java.base/java.util.Iterator.forEachRemaining(Iterator.java:133) ~[?:?]
	at java.base/java.util.Spliterators$IteratorSpliterator.forEachRemaining(Spliterators.java:1939) ~[?:?]
	at java.base/java.util.stream.ReferencePipeline$Head.forEach(ReferencePipeline.java:762) ~[?:?]
	at org.codehaus.groovy.control.CompilationUnit.buildASTs(CompilationUnit.java:667) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.CompilationUnit.compile(CompilationUnit.java:633) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.doParseClass(GroovyClassLoader.java:389) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.lambda$parseClass$3(GroovyClassLoader.java:332) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.runtime.memoize.StampedCommonCache.compute(StampedCommonCache.java:163) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.runtime.memoize.StampedCommonCache.getAndPut(StampedCommonCache.java:154) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:330) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:314) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:257) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.getScriptClass(GroovyScriptEngineImpl.java:336) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.compile(GroovyScriptEngineImpl.java:181) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	... 15 more
2026-02-25 16:17:27,903 ERROR o.a.j.e.JSR223PostProcessor: Problem in JSR223 script, JSR223 PostProcessor
javax.script.ScriptException: org.codehaus.groovy.control.MultipleCompilationErrorsException: startup failed:
Script12.groovy: 3: Unexpected input: '(' @ line 3, column 9.
   vars.put("counter", c.toString
           ^

1 error

	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.compile(GroovyScriptEngineImpl.java:183) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	at org.apache.jmeter.util.JSR223TestElement.lambda$processFileOrScript$1(JSR223TestElement.java:225) ~[ApacheJMeter_core.jar:5.6.3]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.lambda$doComputeIfAbsent$14(BoundedLocalCache.java:2406) ~[caffeine-2.9.3.jar:?]
	at java.base/java.util.concurrent.ConcurrentHashMap.compute(ConcurrentHashMap.java:1916) ~[?:?]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.doComputeIfAbsent(BoundedLocalCache.java:2404) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.computeIfAbsent(BoundedLocalCache.java:2387) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.LocalCache.computeIfAbsent(LocalCache.java:108) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.LocalManualCache.get(LocalManualCache.java:62) ~[caffeine-2.9.3.jar:?]
	at org.apache.jmeter.util.JSR223TestElement.getCompiledScript(JSR223TestElement.java:252) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.util.JSR223TestElement.processFileOrScript(JSR223TestElement.java:223) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.extractor.JSR223PostProcessor.process(JSR223PostProcessor.java:45) ~[ApacheJMeter_components.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.runPostProcessors(JMeterThread.java:973) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:585) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
	Suppressed: java.lang.IllegalStateException: Unable to compile script StringScriptCacheKey{contents='f78324d73594e82a842199c520580f48'}
		at org.apache.jmeter.util.JSR223TestElement.getCompiledScript(JSR223TestElement.java:264) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.util.JSR223TestElement.processFileOrScript(JSR223TestElement.java:223) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.extractor.JSR223PostProcessor.process(JSR223PostProcessor.java:45) ~[ApacheJMeter_components.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.runPostProcessors(JMeterThread.java:973) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:585) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
		at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
Caused by: org.codehaus.groovy.control.MultipleCompilationErrorsException: startup failed:
Script12.groovy: 3: Unexpected input: '(' @ line 3, column 9.
   vars.put("counter", c.toString
           ^

1 error

	at org.codehaus.groovy.control.ErrorCollector.failIfErrors(ErrorCollector.java:292) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.ErrorCollector.addFatalError(ErrorCollector.java:148) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.collectSyntaxError(AstBuilder.java:4301) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.access$000(AstBuilder.java:176) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder$1.syntaxError(AstBuilder.java:4312) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.ProxyErrorListener.syntaxError(ProxyErrorListener.java:44) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.Parser.notifyErrorListeners(Parser.java:543) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.DefaultErrorStrategy.notifyErrorListeners(DefaultErrorStrategy.java:154) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.reportInputMismatch(DescriptiveErrorStrategy.java:103) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.recover(DescriptiveErrorStrategy.java:55) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.recoverInline(DescriptiveErrorStrategy.java:68) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.Parser.match(Parser.java:213) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.GroovyParser.compilationUnit(GroovyParser.java:362) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildCST(AstBuilder.java:250) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildCST(AstBuilder.java:228) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildAST(AstBuilder.java:269) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.Antlr4ParserPlugin.buildAST(Antlr4ParserPlugin.java:58) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.SourceUnit.buildAST(SourceUnit.java:256) ~[groovy-3.0.20.jar:3.0.20]
	at java.base/java.util.Iterator.forEachRemaining(Iterator.java:133) ~[?:?]
	at java.base/java.util.Spliterators$IteratorSpliterator.forEachRemaining(Spliterators.java:1939) ~[?:?]
	at java.base/java.util.stream.ReferencePipeline$Head.forEach(ReferencePipeline.java:762) ~[?:?]
	at org.codehaus.groovy.control.CompilationUnit.buildASTs(CompilationUnit.java:667) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.CompilationUnit.compile(CompilationUnit.java:633) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.doParseClass(GroovyClassLoader.java:389) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.lambda$parseClass$3(GroovyClassLoader.java:332) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.runtime.memoize.StampedCommonCache.compute(StampedCommonCache.java:163) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.runtime.memoize.StampedCommonCache.getAndPut(StampedCommonCache.java:154) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:330) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:314) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:257) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.getScriptClass(GroovyScriptEngineImpl.java:336) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.compile(GroovyScriptEngineImpl.java:181) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	... 15 more
2026-02-25 16:17:28,914 ERROR o.a.j.e.JSR223PostProcessor: Problem in JSR223 script, JSR223 PostProcessor
javax.script.ScriptException: org.codehaus.groovy.control.MultipleCompilationErrorsException: startup failed:
Script13.groovy: 3: Unexpected input: '(' @ line 3, column 9.
   vars.put("counter", c.toString
           ^

1 error

	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.compile(GroovyScriptEngineImpl.java:183) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	at org.apache.jmeter.util.JSR223TestElement.lambda$processFileOrScript$1(JSR223TestElement.java:225) ~[ApacheJMeter_core.jar:5.6.3]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.lambda$doComputeIfAbsent$14(BoundedLocalCache.java:2406) ~[caffeine-2.9.3.jar:?]
	at java.base/java.util.concurrent.ConcurrentHashMap.compute(ConcurrentHashMap.java:1916) ~[?:?]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.doComputeIfAbsent(BoundedLocalCache.java:2404) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.computeIfAbsent(BoundedLocalCache.java:2387) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.LocalCache.computeIfAbsent(LocalCache.java:108) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.LocalManualCache.get(LocalManualCache.java:62) ~[caffeine-2.9.3.jar:?]
	at org.apache.jmeter.util.JSR223TestElement.getCompiledScript(JSR223TestElement.java:252) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.util.JSR223TestElement.processFileOrScript(JSR223TestElement.java:223) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.extractor.JSR223PostProcessor.process(JSR223PostProcessor.java:45) ~[ApacheJMeter_components.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.runPostProcessors(JMeterThread.java:973) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:585) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
	Suppressed: java.lang.IllegalStateException: Unable to compile script StringScriptCacheKey{contents='f78324d73594e82a842199c520580f48'}
		at org.apache.jmeter.util.JSR223TestElement.getCompiledScript(JSR223TestElement.java:264) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.util.JSR223TestElement.processFileOrScript(JSR223TestElement.java:223) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.extractor.JSR223PostProcessor.process(JSR223PostProcessor.java:45) ~[ApacheJMeter_components.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.runPostProcessors(JMeterThread.java:973) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:585) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
		at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
Caused by: org.codehaus.groovy.control.MultipleCompilationErrorsException: startup failed:
Script13.groovy: 3: Unexpected input: '(' @ line 3, column 9.
   vars.put("counter", c.toString
           ^

1 error

	at org.codehaus.groovy.control.ErrorCollector.failIfErrors(ErrorCollector.java:292) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.ErrorCollector.addFatalError(ErrorCollector.java:148) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.collectSyntaxError(AstBuilder.java:4301) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.access$000(AstBuilder.java:176) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder$1.syntaxError(AstBuilder.java:4312) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.ProxyErrorListener.syntaxError(ProxyErrorListener.java:44) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.Parser.notifyErrorListeners(Parser.java:543) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.DefaultErrorStrategy.notifyErrorListeners(DefaultErrorStrategy.java:154) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.reportInputMismatch(DescriptiveErrorStrategy.java:103) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.recover(DescriptiveErrorStrategy.java:55) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.recoverInline(DescriptiveErrorStrategy.java:68) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.Parser.match(Parser.java:213) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.GroovyParser.compilationUnit(GroovyParser.java:362) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildCST(AstBuilder.java:250) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildCST(AstBuilder.java:228) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildAST(AstBuilder.java:269) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.Antlr4ParserPlugin.buildAST(Antlr4ParserPlugin.java:58) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.SourceUnit.buildAST(SourceUnit.java:256) ~[groovy-3.0.20.jar:3.0.20]
	at java.base/java.util.Iterator.forEachRemaining(Iterator.java:133) ~[?:?]
	at java.base/java.util.Spliterators$IteratorSpliterator.forEachRemaining(Spliterators.java:1939) ~[?:?]
	at java.base/java.util.stream.ReferencePipeline$Head.forEach(ReferencePipeline.java:762) ~[?:?]
	at org.codehaus.groovy.control.CompilationUnit.buildASTs(CompilationUnit.java:667) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.CompilationUnit.compile(CompilationUnit.java:633) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.doParseClass(GroovyClassLoader.java:389) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.lambda$parseClass$3(GroovyClassLoader.java:332) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.runtime.memoize.StampedCommonCache.compute(StampedCommonCache.java:163) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.runtime.memoize.StampedCommonCache.getAndPut(StampedCommonCache.java:154) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:330) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:314) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:257) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.getScriptClass(GroovyScriptEngineImpl.java:336) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.compile(GroovyScriptEngineImpl.java:181) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	... 15 more
2026-02-25 16:17:29,924 ERROR o.a.j.e.JSR223PostProcessor: Problem in JSR223 script, JSR223 PostProcessor
javax.script.ScriptException: org.codehaus.groovy.control.MultipleCompilationErrorsException: startup failed:
Script14.groovy: 3: Unexpected input: '(' @ line 3, column 9.
   vars.put("counter", c.toString
           ^

1 error

	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.compile(GroovyScriptEngineImpl.java:183) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	at org.apache.jmeter.util.JSR223TestElement.lambda$processFileOrScript$1(JSR223TestElement.java:225) ~[ApacheJMeter_core.jar:5.6.3]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.lambda$doComputeIfAbsent$14(BoundedLocalCache.java:2406) ~[caffeine-2.9.3.jar:?]
	at java.base/java.util.concurrent.ConcurrentHashMap.compute(ConcurrentHashMap.java:1916) ~[?:?]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.doComputeIfAbsent(BoundedLocalCache.java:2404) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.computeIfAbsent(BoundedLocalCache.java:2387) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.LocalCache.computeIfAbsent(LocalCache.java:108) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.LocalManualCache.get(LocalManualCache.java:62) ~[caffeine-2.9.3.jar:?]
	at org.apache.jmeter.util.JSR223TestElement.getCompiledScript(JSR223TestElement.java:252) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.util.JSR223TestElement.processFileOrScript(JSR223TestElement.java:223) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.extractor.JSR223PostProcessor.process(JSR223PostProcessor.java:45) ~[ApacheJMeter_components.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.runPostProcessors(JMeterThread.java:973) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:585) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
	Suppressed: java.lang.IllegalStateException: Unable to compile script StringScriptCacheKey{contents='f78324d73594e82a842199c520580f48'}
		at org.apache.jmeter.util.JSR223TestElement.getCompiledScript(JSR223TestElement.java:264) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.util.JSR223TestElement.processFileOrScript(JSR223TestElement.java:223) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.extractor.JSR223PostProcessor.process(JSR223PostProcessor.java:45) ~[ApacheJMeter_components.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.runPostProcessors(JMeterThread.java:973) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:585) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
		at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
Caused by: org.codehaus.groovy.control.MultipleCompilationErrorsException: startup failed:
Script14.groovy: 3: Unexpected input: '(' @ line 3, column 9.
   vars.put("counter", c.toString
           ^

1 error

	at org.codehaus.groovy.control.ErrorCollector.failIfErrors(ErrorCollector.java:292) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.ErrorCollector.addFatalError(ErrorCollector.java:148) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.collectSyntaxError(AstBuilder.java:4301) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.access$000(AstBuilder.java:176) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder$1.syntaxError(AstBuilder.java:4312) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.ProxyErrorListener.syntaxError(ProxyErrorListener.java:44) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.Parser.notifyErrorListeners(Parser.java:543) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.DefaultErrorStrategy.notifyErrorListeners(DefaultErrorStrategy.java:154) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.reportInputMismatch(DescriptiveErrorStrategy.java:103) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.recover(DescriptiveErrorStrategy.java:55) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.recoverInline(DescriptiveErrorStrategy.java:68) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.Parser.match(Parser.java:213) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.GroovyParser.compilationUnit(GroovyParser.java:362) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildCST(AstBuilder.java:250) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildCST(AstBuilder.java:228) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildAST(AstBuilder.java:269) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.Antlr4ParserPlugin.buildAST(Antlr4ParserPlugin.java:58) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.SourceUnit.buildAST(SourceUnit.java:256) ~[groovy-3.0.20.jar:3.0.20]
	at java.base/java.util.Iterator.forEachRemaining(Iterator.java:133) ~[?:?]
	at java.base/java.util.Spliterators$IteratorSpliterator.forEachRemaining(Spliterators.java:1939) ~[?:?]
	at java.base/java.util.stream.ReferencePipeline$Head.forEach(ReferencePipeline.java:762) ~[?:?]
	at org.codehaus.groovy.control.CompilationUnit.buildASTs(CompilationUnit.java:667) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.CompilationUnit.compile(CompilationUnit.java:633) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.doParseClass(GroovyClassLoader.java:389) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.lambda$parseClass$3(GroovyClassLoader.java:332) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.runtime.memoize.StampedCommonCache.compute(StampedCommonCache.java:163) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.runtime.memoize.StampedCommonCache.getAndPut(StampedCommonCache.java:154) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:330) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:314) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:257) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.getScriptClass(GroovyScriptEngineImpl.java:336) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.compile(GroovyScriptEngineImpl.java:181) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	... 15 more
2026-02-25 16:17:30,935 ERROR o.a.j.e.JSR223PostProcessor: Problem in JSR223 script, JSR223 PostProcessor
javax.script.ScriptException: org.codehaus.groovy.control.MultipleCompilationErrorsException: startup failed:
Script15.groovy: 3: Unexpected input: '(' @ line 3, column 9.
   vars.put("counter", c.toString
           ^

1 error

	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.compile(GroovyScriptEngineImpl.java:183) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	at org.apache.jmeter.util.JSR223TestElement.lambda$processFileOrScript$1(JSR223TestElement.java:225) ~[ApacheJMeter_core.jar:5.6.3]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.lambda$doComputeIfAbsent$14(BoundedLocalCache.java:2406) ~[caffeine-2.9.3.jar:?]
	at java.base/java.util.concurrent.ConcurrentHashMap.compute(ConcurrentHashMap.java:1916) ~[?:?]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.doComputeIfAbsent(BoundedLocalCache.java:2404) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.computeIfAbsent(BoundedLocalCache.java:2387) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.LocalCache.computeIfAbsent(LocalCache.java:108) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.LocalManualCache.get(LocalManualCache.java:62) ~[caffeine-2.9.3.jar:?]
	at org.apache.jmeter.util.JSR223TestElement.getCompiledScript(JSR223TestElement.java:252) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.util.JSR223TestElement.processFileOrScript(JSR223TestElement.java:223) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.extractor.JSR223PostProcessor.process(JSR223PostProcessor.java:45) ~[ApacheJMeter_components.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.runPostProcessors(JMeterThread.java:973) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:585) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
	Suppressed: java.lang.IllegalStateException: Unable to compile script StringScriptCacheKey{contents='f78324d73594e82a842199c520580f48'}
		at org.apache.jmeter.util.JSR223TestElement.getCompiledScript(JSR223TestElement.java:264) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.util.JSR223TestElement.processFileOrScript(JSR223TestElement.java:223) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.extractor.JSR223PostProcessor.process(JSR223PostProcessor.java:45) ~[ApacheJMeter_components.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.runPostProcessors(JMeterThread.java:973) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:585) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
		at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
Caused by: org.codehaus.groovy.control.MultipleCompilationErrorsException: startup failed:
Script15.groovy: 3: Unexpected input: '(' @ line 3, column 9.
   vars.put("counter", c.toString
           ^

1 error

	at org.codehaus.groovy.control.ErrorCollector.failIfErrors(ErrorCollector.java:292) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.ErrorCollector.addFatalError(ErrorCollector.java:148) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.collectSyntaxError(AstBuilder.java:4301) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.access$000(AstBuilder.java:176) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder$1.syntaxError(AstBuilder.java:4312) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.ProxyErrorListener.syntaxError(ProxyErrorListener.java:44) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.Parser.notifyErrorListeners(Parser.java:543) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.DefaultErrorStrategy.notifyErrorListeners(DefaultErrorStrategy.java:154) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.reportInputMismatch(DescriptiveErrorStrategy.java:103) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.recover(DescriptiveErrorStrategy.java:55) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.recoverInline(DescriptiveErrorStrategy.java:68) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.Parser.match(Parser.java:213) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.GroovyParser.compilationUnit(GroovyParser.java:362) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildCST(AstBuilder.java:250) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildCST(AstBuilder.java:228) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildAST(AstBuilder.java:269) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.Antlr4ParserPlugin.buildAST(Antlr4ParserPlugin.java:58) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.SourceUnit.buildAST(SourceUnit.java:256) ~[groovy-3.0.20.jar:3.0.20]
	at java.base/java.util.Iterator.forEachRemaining(Iterator.java:133) ~[?:?]
	at java.base/java.util.Spliterators$IteratorSpliterator.forEachRemaining(Spliterators.java:1939) ~[?:?]
	at java.base/java.util.stream.ReferencePipeline$Head.forEach(ReferencePipeline.java:762) ~[?:?]
	at org.codehaus.groovy.control.CompilationUnit.buildASTs(CompilationUnit.java:667) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.CompilationUnit.compile(CompilationUnit.java:633) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.doParseClass(GroovyClassLoader.java:389) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.lambda$parseClass$3(GroovyClassLoader.java:332) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.runtime.memoize.StampedCommonCache.compute(StampedCommonCache.java:163) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.runtime.memoize.StampedCommonCache.getAndPut(StampedCommonCache.java:154) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:330) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:314) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:257) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.getScriptClass(GroovyScriptEngineImpl.java:336) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.compile(GroovyScriptEngineImpl.java:181) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	... 15 more
2026-02-25 16:17:31,945 ERROR o.a.j.e.JSR223PostProcessor: Problem in JSR223 script, JSR223 PostProcessor
javax.script.ScriptException: org.codehaus.groovy.control.MultipleCompilationErrorsException: startup failed:
Script16.groovy: 3: Unexpected input: '(' @ line 3, column 9.
   vars.put("counter", c.toString
           ^

1 error

	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.compile(GroovyScriptEngineImpl.java:183) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	at org.apache.jmeter.util.JSR223TestElement.lambda$processFileOrScript$1(JSR223TestElement.java:225) ~[ApacheJMeter_core.jar:5.6.3]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.lambda$doComputeIfAbsent$14(BoundedLocalCache.java:2406) ~[caffeine-2.9.3.jar:?]
	at java.base/java.util.concurrent.ConcurrentHashMap.compute(ConcurrentHashMap.java:1916) ~[?:?]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.doComputeIfAbsent(BoundedLocalCache.java:2404) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.BoundedLocalCache.computeIfAbsent(BoundedLocalCache.java:2387) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.LocalCache.computeIfAbsent(LocalCache.java:108) ~[caffeine-2.9.3.jar:?]
	at com.github.benmanes.caffeine.cache.LocalManualCache.get(LocalManualCache.java:62) ~[caffeine-2.9.3.jar:?]
	at org.apache.jmeter.util.JSR223TestElement.getCompiledScript(JSR223TestElement.java:252) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.util.JSR223TestElement.processFileOrScript(JSR223TestElement.java:223) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.extractor.JSR223PostProcessor.process(JSR223PostProcessor.java:45) ~[ApacheJMeter_components.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.runPostProcessors(JMeterThread.java:973) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:585) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
	at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
	at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
	Suppressed: java.lang.IllegalStateException: Unable to compile script StringScriptCacheKey{contents='f78324d73594e82a842199c520580f48'}
		at org.apache.jmeter.util.JSR223TestElement.getCompiledScript(JSR223TestElement.java:264) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.util.JSR223TestElement.processFileOrScript(JSR223TestElement.java:223) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.extractor.JSR223PostProcessor.process(JSR223PostProcessor.java:45) ~[ApacheJMeter_components.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.runPostProcessors(JMeterThread.java:973) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.executeSamplePackage(JMeterThread.java:585) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.processSampler(JMeterThread.java:501) ~[ApacheJMeter_core.jar:5.6.3]
		at org.apache.jmeter.threads.JMeterThread.run(JMeterThread.java:268) ~[ApacheJMeter_core.jar:5.6.3]
		at java.base/java.lang.Thread.run(Thread.java:1583) [?:?]
Caused by: org.codehaus.groovy.control.MultipleCompilationErrorsException: startup failed:
Script16.groovy: 3: Unexpected input: '(' @ line 3, column 9.
   vars.put("counter", c.toString
           ^

1 error

	at org.codehaus.groovy.control.ErrorCollector.failIfErrors(ErrorCollector.java:292) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.ErrorCollector.addFatalError(ErrorCollector.java:148) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.collectSyntaxError(AstBuilder.java:4301) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.access$000(AstBuilder.java:176) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder$1.syntaxError(AstBuilder.java:4312) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.ProxyErrorListener.syntaxError(ProxyErrorListener.java:44) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.Parser.notifyErrorListeners(Parser.java:543) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.DefaultErrorStrategy.notifyErrorListeners(DefaultErrorStrategy.java:154) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.reportInputMismatch(DescriptiveErrorStrategy.java:103) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.recover(DescriptiveErrorStrategy.java:55) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.internal.DescriptiveErrorStrategy.recoverInline(DescriptiveErrorStrategy.java:68) ~[groovy-3.0.20.jar:3.0.20]
	at groovyjarjarantlr4.v4.runtime.Parser.match(Parser.java:213) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.GroovyParser.compilationUnit(GroovyParser.java:362) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildCST(AstBuilder.java:250) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildCST(AstBuilder.java:228) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.AstBuilder.buildAST(AstBuilder.java:269) ~[groovy-3.0.20.jar:3.0.20]
	at org.apache.groovy.parser.antlr4.Antlr4ParserPlugin.buildAST(Antlr4ParserPlugin.java:58) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.SourceUnit.buildAST(SourceUnit.java:256) ~[groovy-3.0.20.jar:3.0.20]
	at java.base/java.util.Iterator.forEachRemaining(Iterator.java:133) ~[?:?]
	at java.base/java.util.Spliterators$IteratorSpliterator.forEachRemaining(Spliterators.java:1939) ~[?:?]
	at java.base/java.util.stream.ReferencePipeline$Head.forEach(ReferencePipeline.java:762) ~[?:?]
	at org.codehaus.groovy.control.CompilationUnit.buildASTs(CompilationUnit.java:667) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.control.CompilationUnit.compile(CompilationUnit.java:633) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.doParseClass(GroovyClassLoader.java:389) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.lambda$parseClass$3(GroovyClassLoader.java:332) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.runtime.memoize.StampedCommonCache.compute(StampedCommonCache.java:163) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.runtime.memoize.StampedCommonCache.getAndPut(StampedCommonCache.java:154) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:330) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:314) ~[groovy-3.0.20.jar:3.0.20]
	at groovy.lang.GroovyClassLoader.parseClass(GroovyClassLoader.java:257) ~[groovy-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.getScriptClass(GroovyScriptEngineImpl.java:336) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	at org.codehaus.groovy.jsr223.GroovyScriptEngineImpl.compile(GroovyScriptEngineImpl.java:181) ~[groovy-jsr223-3.0.20.jar:3.0.20]
	... 15 more
2026-02-25 16:17:32,536 INFO o.a.j.g.a.Start: Stopping test
2026-02-25 16:17:32,543 INFO o.a.j.t.JMeterThread: Stopping: ThreadsLoraDevices 1-1
2026-02-25 16:17:32,544 WARN o.a.j.t.JMeterThread: The delay timer was interrupted - probably did not wait as long as intended.
2026-02-25 16:17:32,544 INFO o.a.j.t.JMeterThread: Thread finished: ThreadsLoraDevices 1-1
2026-02-25 16:17:32,544 INFO o.a.j.e.StandardJMeterEngine: Notifying test listeners of end of test
2026-02-25 16:17:32,553 INFO o.a.j.g.u.JMeterMenuBar: setRunning(false, *local*)
