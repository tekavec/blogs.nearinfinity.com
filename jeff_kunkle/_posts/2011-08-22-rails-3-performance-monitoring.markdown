---
atom_id: tag:www.nearinfinity.com,2011:/blogs//7.1873 # This is for backwards compatibility do not change!
permalink: /blogs/jeff_kunkle/rails_3_performance_monitoring.html
layout: blogs
title: Rails 3 Performance Monitoring with System Metrics
date: 2011-08-22 09:42:18 -04:00
tags: Ruby
---
System Metrics is a new Rails 3 Engine providing a clean web interface to the performance metrics instrumented with `ActiveSupport::Notifications`. It will collect and display the notifications baked into Rails and any additional custom ones you add using `ActiveSupport::Notification#instrument`.

System Metrics is not intended to be a replacement for performance monitoring solutions such as New Relic. However, it is especially handy for quickly identifying performance problems in a development environment. It's also a great alternative for private networks disconnected from the Internet.

You can find more information about System Metrics on the [System Metrics site](http://nearinfinity.github.com/system-metrics). Please kick the tires and let us know what you think.

<img src="/blogs/jeff_kunkle/assets/smdetails.png" alt="System Metrics Detail View" />
