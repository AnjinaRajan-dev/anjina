# anjina
Bucket name : bucket-anjina
Topic name : aws_sns_anjina

cloud hub log: 

Advanced
14:12:31.560     11/17/2019     Deployment     system     SYSTEM
Application queued to be deployed...
14:12:31.615     11/17/2019     Deployment     system     SYSTEM
Deploying application to 1 workers in us-east-2 region(s).
14:12:32.012     11/17/2019     Deployment     system     SYSTEM
Provisioning CloudHub worker in region=us-east-2...
14:12:32.679     11/17/2019     Deployment     system     SYSTEM
Starting CloudHub worker at 18.218.135.110 ...
14:12:48.511     11/17/2019     Deployment     system     SYSTEM
Worker(18.218.135.110): Starting your application on mule=4.2.1...
14:12:51.097     11/17/2019     Worker-0     qtp451837257-37     INFO
The PersistentQueueManager is NOT configured. The normal VM queue manager will be used.
14:12:57.703     11/17/2019     Worker-0     qtp451837257-37     INFO
Loaded MuleMessageBuilderFactory implementation 'org.mule.runtime.core.internal.message.DefaultMessageBuilderFactory' from classloader 'org.mule.runtime.module.reboot.internal.MuleContainerSystemClassLoader@1a1c7dd0'
14:12:57.753     11/17/2019     Worker-0     qtp451837257-37     INFO
Loaded BindingContextBuilderFactory implementation 'org.mule.runtime.core.api.el.DefaultBindingContextBuilderFactory' from classloader 'org.mule.runtime.module.reboot.internal.MuleContainerSystemClassLoader@1a1c7dd0'
14:12:57.938     11/17/2019     Worker-0     qtp451837257-37     INFO
Loading configuration file: tls-default.conf
14:12:57.940     11/17/2019     Worker-0     qtp451837257-37     INFO
Loaded TlsContextFactoryBuilderFactory implementation 'org.mule.runtime.module.tls.api.DefaultTlsContextFactoryBuilderFactory' from classloader 'org.mule.runtime.module.reboot.internal.MuleContainerSystemClassLoader@1a1c7dd0'
14:12:58.322     11/17/2019     Worker-0     qtp451837257-37     INFO
Using files for tx logs /opt/mule/mule-4.2.1/./.mule/aws-s3/queue-tx-log/tx1.log and /opt/mule/mule-4.2.1/./.mule/aws-s3/queue-tx-log/tx2.log
14:12:58.329     11/17/2019     Worker-0     qtp451837257-37     INFO
Using files for tx logs /opt/mule/mule-4.2.1/./.mule/aws-s3/queue-xa-tx-log/tx1.log and /opt/mule/mule-4.2.1/./.mule/aws-s3/queue-xa-tx-log/tx2.log
14:12:58.998     11/17/2019     Worker-0     qtp451837257-37     INFO
Initialising Bean: org.mule.runtime.module.extension.internal.runtime.config.ConfigurationProviderToolingAdapter-HTTP_Listener_config
14:12:59.558     11/17/2019     Worker-0     qtp451837257-37     INFO
Initialising Bean: org.mule.runtime.module.extension.internal.runtime.config.ConfigurationProviderToolingAdapter-HTTP_Request_configuration
14:12:59.572     11/17/2019     Worker-0     qtp451837257-37     INFO
Initialising Bean: org.mule.runtime.module.extension.internal.runtime.config.ConfigurationProviderToolingAdapter-Amazon_S3_Configuration
14:12:59.591     11/17/2019     Worker-0     qtp451837257-37     INFO
Initialising Bean: org.mule.runtime.module.extension.internal.runtime.config.ConfigurationProviderToolingAdapter-HTTP_Listener_config1
14:12:59.645     11/17/2019     Worker-0     qtp451837257-37     INFO
Initialising flow: aws_s3Flow
14:12:59.820     11/17/2019     Worker-0     qtp451837257-37     INFO
Initialising Bean: listener
14:12:59.986     11/17/2019     Worker-0     qtp451837257-37     INFO
Initialising flow: aws_s3Flow1
14:12:59.988     11/17/2019     Worker-0     qtp451837257-37     INFO
Initialising Bean: listener
14:13:00.473     11/17/2019     Worker-0     qtp451837257-37     INFO
Persistent queues is not enabled for batch module as it was not configured in Cloudhub console
14:13:00.548     11/17/2019     Worker-0     qtp451837257-37     INFO
Starting ResourceManager
14:13:00.549     11/17/2019     Worker-0     qtp451837257-37     INFO
Started ResourceManager
14:13:00.562     11/17/2019     Worker-0     qtp451837257-37     INFO
Starting Bean: org.mule.runtime.module.extension.internal.runtime.config.ConfigurationProviderToolingAdapter-HTTP_Listener_config
14:13:00.608     11/17/2019     Worker-0     qtp451837257-37     INFO
Starting Bean: org.mule.runtime.module.extension.internal.runtime.config.ConfigurationProviderToolingAdapter-HTTP_Request_configuration
14:13:00.729     11/17/2019     Worker-0     qtp451837257-37     INFO
Starting Bean: org.mule.runtime.module.extension.internal.runtime.config.ConfigurationProviderToolingAdapter-Amazon_S3_Configuration
14:13:02.082     11/17/2019     Worker-0     qtp451837257-37     INFO
Starting Bean: org.mule.runtime.module.extension.internal.runtime.config.ConfigurationProviderToolingAdapter-HTTP_Listener_config1
14:13:02.086     11/17/2019     Worker-0     qtp451837257-37     INFO
Starting flow: aws_s3Flow
14:13:04.066     11/17/2019     Worker-0     qtp451837257-37     INFO
Starting flow: aws_s3Flow1
14:13:04.098     11/17/2019     Worker-0     qtp451837257-37     INFO
Starting Bean: listener
14:13:04.109     11/17/2019     Worker-0     qtp451837257-37     INFO
Starting Bean: listener
14:13:04.138     11/17/2019     Worker-0     qtp451837257-37     INFO

**********************************************************************
* Application: aws-s3                                                *
* OS encoding: UTF-8, Mule encoding: UTF-8                           *
*                                                                    *
**********************************************************************
14:13:04.481     11/17/2019     Deployment     system     SYSTEM
Worker(18.218.135.110): Your application has started successfully.
14:13:05.212     11/17/2019     Deployment     system     SYSTEM
Your application is started.
