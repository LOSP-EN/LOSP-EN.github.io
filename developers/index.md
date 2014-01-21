---
layout: nodate
title: Developers
subtitle: Opening, Sharing, Communication
---
Light OpenSource Project is fully open-souce under Apache License 2.0. For developers, you can easily download our source of Xposed modules and then complie/modify them. The following steps are for those who want to build the pure LOSP ROM for a device.

Syncing: 
{% highlight sh %}
repo init -u git://github.com/LOSP/platform_manifest.git -b kk
repo sync
repo start kk
{% endhighlight %}

Commiting:  
First, you should fork your modified repository to your own github  
{% highlight sh %}
cd /THE-LOCAL-PATH-OF-YOUR-MODIFIED-REPOSITORY
git add -A
git commit -m "WHAT-YOU-CHANGED"
git push https://github.com/PATH-AFTER-YOUR-FORK kk
{% endhighlight %}
Then send a pull request to us on github.