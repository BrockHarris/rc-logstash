source "https://supermarket.getchef.com"

# metadata

#cookbook 'tabula_rasa', git: 'https://github.com/shlomoswidler/tabula_rasa.git'

# until https://github.com/elasticsearch/cookbook-elasticsearch/pull/230
cookbook 'elasticsearch', '~> 0.3', git:'https://github.com/racker/cookbook-elasticsearch.git'
# until https://github.com/lusis/chef-logstash/pull/336
cookbook 'logstash', git:'https://github.com/racker/chef-logstash.git'

# until https://github.com/poise/python/pull/120
cookbook 'python', git: 'https://github.com/racker/python.git'

cookbook 'rackspace_iptables', git: 'https://github.com/rackspace-cookbooks/rackspace_iptables.git'
cookbook 'rackspacecloud', git: 'https://github.com/rackspace-cookbooks/rackspacecloud.git'
cookbook 'rackspace_gluster', git: 'https://github.com/rackspace-cookbooks/rackspace_gluster.git'
cookbook 'rackops_rolebook', git: 'https://github.com/rackops/rackops_rolebook.git'

# not published
cookbook 'rackspace_cloudbackup', git:'https://github.com/rackspace-cookbooks/rackspace_cloudbackup.git'

group :integration do
  cookbook 'wrapper', path: 'elkstack/test/fixtures/cookbooks/wrapper'
  cookbook 'apt'
  cookbook 'yum'
end

# until https://github.com/opscode-cookbooks/openssl/pull/11
cookbook 'openssl', git: 'https://github.com/racker/openssl.git'
