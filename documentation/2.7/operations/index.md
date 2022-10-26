---
---

# Operations Overview

The following sections provide a documentation Table of Contents and additional information sources about Ehcache operations.

## Operations Table of Contents

| Topic | Description |
|:-------|:------------|
|[Tuning GC](/documentation/2.7/operations/garbage-collection)|Detecting Garbage Collection problems, Garbage Collection tuning, and distributed caching Garbage Collection tuning.|
|[JMX Management](/documentation/2.7/operations/jmx)|As an alternative to the Ehcache Monitor, JMX creates a standard way of instrumenting classes and making them available to a management and monitoring infrastructure.|
|[Logging](/documentation/2.7/operations/logging)|Ehcache uses the the slf4j logging facade, so you can plug in your own logging framework. This page also provides recommended logging levels.|
|[Shutting Down Ehcache](/documentation/2.7/operations/shutdown)|If you are using persistent disk stores, or distributed caching, care should be taken when shutting down Ehcache. This page covers the ServletContextListener, the shutdown hook, and dirty shutdown.|
|[RMI Cache Remote Debugger](/documentation/2.7/operations/remotedebugger)|The Remote Debugger can be used to debug replicated cache operations. When started with the same configuration as the cluster, it will join the cluster and then report cluster events for the cache of interest. By providing a window into the cluster, it can help to identify the cause of cluster problems.|



## Additional Information about Operations
The following page provides additional information about the Ehcache Monitor:

* [Terracotta Console for Enterprise Ehcache](http://terracotta.org/documentation/2.7/terracotta-tools/dev-console#enterprise-ehcache-applications)
* [Cache Size and Statistics Code Samples](/documentation/2.7/code-samples#using-caches)
* [CacheManager Shutdown Code Sample](/documentation/2.7/code-samples#shutdown-the-cachemanager)




