# REST API #
## reserved URL words ##
  * _method_


|	Add a new interest| 	`/interest`  |`?_method=add`		|
|:------------------|:--------------|:---------------|
| 	Show a interest|	`/interest/{interest_id}` |`?_method=get`		|
|	Update a interest|	`/interest/{interest_id}` |`?_method=edit`	|
| 	List all markers|	`/interest/{interest_id}/marker` |`?_method=get`		|
|	Add a new marker|	`/interest/{interest_id}/marker` |`?_method=add`		|
| 	Show a marker|	`/interest/{interest_id}/marker/{marker_id}`|`?_method=get`		|
|	Update a marker|	`/interest/{interest_id}/marker/{marker_id}` |`?_method=edit`	|
|	Delete a marker|	`/interest/{interest_id}/marker/{marker_id}` 	|`?_method=delete`	|