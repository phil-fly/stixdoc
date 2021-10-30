# STIX Relationship Objects（SRO）
    用于SDO之间、SCO之间、SDO和SCO之间的关系

## SRO的大类包括以下两种：
- Relationship:大多数关系所采用的类型，其relation_type字段包括
    - 内置关系: 如Indicator到Malware之间的关系，可以用indicates 表示，它描述了该Indicator可用于检测对应的恶意软件
    - 自定义关系
- Sighting: 用于捕获实体在SDO中出现的案例，如sighting an indicator。没有明确指明连接哪两个object。之所以将其作为独立的SRO，是因为其具有一些独有的属性，如count。


除了SRO，STIX还用ID references来表示嵌入关系（embedded relationship）。当使用嵌入关系时，表示该属性时该对象的内置属性，从而不需要使用SRO表示，如create_by_ref。因此，SRO可以视为两个节点直接的边，而embedded relationship则可以视为属性（只不过其表示了二元关系）