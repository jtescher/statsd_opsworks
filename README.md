# statsd-container cookbook

# AWS Opsworks

Fix OpsWorks issues by applying [this patch](https://github.com/awestendorf/chef-statsd/commit/ba150790d1877c1273b7918e3ab4f626a442f79d)

Basically just change the following in `recipes/default.rb`:
```ruby
-  notifies :restart, "runit_service[statsd]"
+  notifies :restart, "service[statsd]", :delayed
```
