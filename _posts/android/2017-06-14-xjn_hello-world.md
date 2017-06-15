---
layout: post
title: "xjn Hello World"
description: ""
category: cat1
tags: []
---
{% include JB/setup %}

xjn test

Directly following the intro we'll learn exactly _how_ Jekyll does what it does.

![local picture](../res/aa.png)

asdfadf

![github picture](https://github.com/igiantpanda/igiantpanda.github.io/blob/master/_posts/res/aa.png?raw=true)

{% highlight java linenos %}
```java
private void makeDefault(NetworkAgentInfo newNetwork) {
    if (DBG) log("Switching to new default network: " + newNetwork);
    setupDataActivityTracking(newNetwork);
    try {
        mNetd.setDefaultNetId(newNetwork.network.netId);
    } catch (Exception e) {
        loge("Exception setting default network :" + e);
    }
    notifyLockdownVpn(newNetwork);
    handleApplyDefaultProxy(newNetwork.linkProperties.getHttpProxy());
    updateTcpBufferSizes(newNetwork);
    setDefaultDnsSystemProperties(newNetwork.linkProperties.getDnsServers());
}
```
{% endhighlight %}





```java
private void makeDefault(NetworkAgentInfo newNetwork) {
    if (DBG) log("Switching to new default network: " + newNetwork);
    setupDataActivityTracking(newNetwork);
    try {
        mNetd.setDefaultNetId(newNetwork.network.netId);
    } catch (Exception e) {
        loge("Exception setting default network :" + e);
    }
    notifyLockdownVpn(newNetwork);
    handleApplyDefaultProxy(newNetwork.linkProperties.getHttpProxy());
    updateTcpBufferSizes(newNetwork);
    setDefaultDnsSystemProperties(newNetwork.linkProperties.getDnsServers());
}
```
