### Pipeline

```mermaid
flowchart TD
	node1["data_load"]
	node2["data_split"]
	node3["evaluate"]
	node4["featurize"]
	node5["train"]
	node1-->node4
	node2-->node3
	node2-->node5
	node4-->node2
	node5-->node3
```
