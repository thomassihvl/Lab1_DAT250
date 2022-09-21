# DAT250 expass 3
I followed the tutorials closely and all went well. I encountered a explanatory gap where the tutorial didn't tell me where my mongodb.exe had been installed when it told me to set the PATH, but I found it myself.

## Installation Validation
![](installation_validation.png)

## Insert Operations
![](insert_operations.png)

## Query Operations
![](query_operations.png)

## Delete Operations
![](delete_operations.png)

## Update Operations
![](update_operations.png)

## Bulk Write
![](bulk_write.png)

## Example 2 Working Example
![](example_2_working.png)

## My Map Reduce
```
// Return total orders per customer
var myMapFunc = function() {
	emit(this.cust_id, this.items.length);
};

var myReduceFunc = function(keyCustId, nOrderItems) {
	return Array.sum(nOrderItems);
};
```
![](myMapReduce.png)
