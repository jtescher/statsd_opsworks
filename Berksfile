site :opscode

metadata

# AWS OpsWorks verion of runit (Required by graphite)
cookbook 'apache2',                '~> 0.9',    github: 'aws/opsworks-cookbooks', rel: 'apache2'
cookbook 'memcached',              '~> 0.1',    github: 'aws/opsworks-cookbooks', rel: 'memcached'
cookbook 'runit',                  '~> 0.14.2', github: 'aws/opsworks-cookbooks', rel: 'runit'
cookbook 'deploy',                 '~> 0.1',    github: 'aws/opsworks-cookbooks', rel: 'deploy'
cookbook 'opsworks_agent_monit',   '~> 0.1',    github: 'aws/opsworks-cookbooks', rel: 'opsworks_agent_monit'
cookbook 'opsworks_initial_setup', '~> 0.1',    github: 'aws/opsworks-cookbooks', rel: 'opsworks_initial_setup'

# Copy that has metadata for AWS version of graphite dependencies
cookbook 'opsworks_commons', '~> 0.0.1', github: 'jtescher/opsworks-cookbooks', rel: 'opsworks_commons'
cookbook 'nodejs',           '~> 0.0.1', github: 'jtescher/opsworks-cookbooks', rel: 'opsworks_nodejs'

cookbook 'apt', '~> 1.9.2'
cookbook 'newrelic-sysmond', '~> 1.3.2', github: 'jtescher/chef-newrelic-sysmond'
cookbook 'graphite', '~> 0.4.2', github: 'jtescher/graphite', branch: 'opsworks'
cookbook 'statsd', '~> 0.1.1', github: 'librato/statsd-cookbook', ref: 'be5de4f7a6c78479947bd6c82d4c01d3a1c41f27'
