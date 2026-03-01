### Architecture Update: No-Code UI Logic 
- Method: JSONata Change Nodes (payload, payload, payload) 
- Reason: Resolving persistent syntax/invalid node errors 
### Syntax Correction: Array Indexing 
- JSONata requires to extract the first value from a Modbus payload. 
### UI Logic Fix: JSONata Expression Mode 
- Confirmed: Change nodes must use J: expression mode, not env variable. 
- Mapping: Eff(0), Supply(43), Extract(50) scaled by 0.1x 
### UI Logic: JSONata Final Configuration  - Efficiency: payload / 10 
- Supply: payload / 10 
### UI Logic Fix: JSONata Expression Mode 
- Confirmed: Change nodes must use J: expression mode, not env variable. 
- Mapping: Eff(0), Supply(43), Extract(50) scaled by 0.1x 
### UI Logic: JSONata Absolute Pathing 
- Resolved: Using $$.payload[index] in J: expression mode. 
- Efficiency(0), Supply(43), Extract(50) 
### UI Logic Fix: Expression Mode Implementation 
- Resolved "Invalid JSONata" error by switching Change nodes to J: expression mode. 
- Formula: payload / 10 for Efficiency. 
### UI Logic: Template Node Indexing 
- Method: Using Mustache templates {{payload.N}} to isolate registers. 
- Reason: Resolving JSONata function signature mismatches with arrays. 
### UI Logic: Multi-Rule Change Nodes Implementation 
- Efficiency isolated from Index 0 and scaled 0.1x 
- Temperatures isolated from Indices 43 and 50 
