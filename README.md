## Architecture 1: (Baseline)  
- Everything is on one machine.  
- Should produce best results and provide a performance goal.  
````
+------------+           
|WEB ADAPTER |           
|GIS SERVER  |           
|           +-----------+
+------------+          |
            |   STORAGE |
            |           |
            +-----------+
````

## Architecture 2:  
- `STORAGE` will be **HNAS** and **SAN**  
- `STORAGE` will be attached to the `WEB ADAPTER` and _shared_ to the `GIS SERVER`'s via a **UNC** share.
 
````
             +-------+            
             |STORAGE|            
             +---+---+            
                 |                
                 |                
           +-----+-----+          
      +----+WEB ADAPTER+----+     
      |    +-----------+    |     
      |                     |     
      |                     |     
+-----+----+          +-----+----+
|GIS SERVER|          |GIS SERVER|
+----------+          +----------+
````

## Architecture 3:  
- `STORAGE` will be **clustured file system SAN**
- `STORAGE` will be directly mounted to the `GIS SERVER`'s
````
          +-----------+         
     +----+WEB ADAPTER+----+    
     |    +-----------+    |    
     |                     |    
+----+-------+    +--------+---+
|            |    |            |
| GIS SERVER |    | GIS SERVER |
|          +---------+         |
+------------+    +------------+
           | STORAGE |          
           |         |          
           +---------+          
````
