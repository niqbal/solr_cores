# solr_cores
This repo has two cores: one managed schema (without explicity solrconfig.xml) and one classic schema (with solrconfig.xml)


Use this command to start solr from your `solr_lucene_folder/solr`: 

`bin/solr start -s /path/to/solr_core`


=== my local notes ===

bin/solr start -s ~/otherdev/solr_core

bin/solr stop


./bin/solr start -e cloud


// flush dns cache
sudo dscacheutil -flushcache;sudo killall -HUP mDNSResponder

