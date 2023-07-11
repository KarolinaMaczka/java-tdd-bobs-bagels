| Class  | Members                         | Methods                             | Scenario                                                          | Output                     |
|--------|---------------------------------|-------------------------------------|-------------------------------------------------------------------|----------------------------| 
| Basket | HashMap<String, Integer> bagels | add(String bagelType, int count)    | if basket is full, the bagel is not added and we return a message | String: "overfilled cart"  |
|        | int capacity                    | add(String bagelType)               | if basket is full, the bagel is not added and we return a message | String: "overfilled cart"  |
|        |                                 |                                     | if adding to the basket was possible, we return a message         | String: "bagel added"      |
|        | int total                       | remove(String bagelType, int count) | if bagel is not found we return message                           | String: "bagel not found"  |
|        |                                 | remove(String bagelType)            | if bagel is not found we return message                           | String: "bagel not found"  |
|        |                                 | emptyBasket()                       | remove all items from the basket                                  | String: "bagel(s) removed" |
|        |                                 |                                     | if removal goes well (remove, emptyBasket), we return a message   | String: "bagel(s) removed" |
|        |                                 | isOverfilled()                      | if basket is overfilled                                           | boolean: true              |
|        |                                 |                                     | if basket is not overfilled                                       | boolean: false             |
|        |                                 | changeCapacity(int)                 | changes capacity of the basket                                    | -                          |
