# esdemo

bin/elasticsearch-plugin list

bin/elasticsearch-plugin install analysis-icu

bin/elasticsearch -d

bin/elasticsearch -E node.name=node0 -E cluster.name=geektime -E path.data=node0_data -d
bin/elasticsearch -E node.name=node1 -E cluster.name=geektime -E path.data=node1_data -d
bin/elasticsearch -E node.name=node2 -E cluster.name=geektime -E path.data=node2_data -d
bin/elasticsearch -E node.name=node3 -E cluster.name=geektime -E path.data=node3_data -d
