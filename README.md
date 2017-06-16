# apache-storm-demo
1) spout : A spout is a source of streams in a topology
Java implements BaseRichSpout with method open(), nextTuple() [values] and declareOutputFields()[name of fields]

2) Bolt : All processing in topologies is done in bolts. Bolts can do anything from filtering, functions, aggregations, joins, talking to databases, and more.
prepare() similar to open() in spoutazazaz
excute() emits new Tuple
declareOutputFields
cleanup() clean like close connection to database
