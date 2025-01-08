# Camunda 2 


```text
+----------------+----------------+----------------+----------------+  +-----------+
|    Client A    |    Client B    |    Client C    |    Client D    |  | Utilities |
+----------------+----------------+----------------+----------------+  +-----------+
                                                                       | Security  |
+----------------+----------------+----------------+----------------+  +-----------+
|   Manager A    |   Manager B    |   Manager C    |   Manager D    |  |Diagnostics|
+----------------+----------------+----------------+----------------+  +-----------+
|    Engine A    |    Engine B    |    Engine C    |                |  | Logging   |
+----------------+----------------+----------------+                |  +-----------+
                                                                    |  |    .      |
+----------------+----------------+----------------+                |  |    .      |
| ResourceAccess | ResourceAccess | ResourceAccess |                |  |    .      |
|       A        |       B        |       C        |                |  +-----------+
+----------------+----------------+----------------+                |  |  Pub/Sub  |
                                                                    |  +-----------+
+----------------+----------------+                                 |  | Message   |
|   Resource A   |   Resource B   |                                 |  |   Bus     |
+----------------+----------------+                                 |  +-----------+
                                                                    |  | Hosting   |
                                                                       +-----------+
```


## What 

A business process ~ state machine

## How

### Manager

Workflow ~ Business Process
State
Transition

https://xstate.js.org/
https://camunda.com/

### Engine

Business Rules
Business Object

https://github.com/gorules/zen


### Resource Access
Repository 

### Enterprise UI Patterns / Wizard

https://arco.design/
https://www.patternfly.org/
https://carbondesignsystem.com/


## Design

## Execution

Create workflow

