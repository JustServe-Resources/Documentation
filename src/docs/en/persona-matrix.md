# Persona Matrix
The targeted user is defined by a matrix of locations and personas, as illustrated in the below diagram. 

```mermaid
---
config:
  theme: dark
---
flowchart LR
 subgraph s2["Locations"]
        n8["All Supported Countries"]
        n9["Bordering Civic Boundaries <br>"]
  end
 subgraph s1["Persona"]
        n1(["Specialist"])
        n2(["Multi-Admin Organization"])
        n3(["Single Admin Organization"])
        n4(["School Club"])
        n5(["Single User"])
        n6(["Small Group of Users"])
        n7(["Large Group of Users"])
  end
 subgraph s3["Examples"]
        n11["Large group of users from USA <br>"]
        n10["Multi Admin Org from Langley, BC"]
        n12["Single User from Mulhouse, France <br>"]
        n13["School Club from Spokane, WA"]
  end
    n8 -- x17 --- n2 & n3
    n9 -- x?? --- n4 & n5
    n5 --> n12
    n8@{ shape: procs}
    n9@{ shape: procs}
    n11@{ shape: stored-data}
    n10@{ shape: stored-data}
    n12@{ shape: stored-data}
    n13@{ shape: stored-data}
     n8:::Rose
     n8:::Peach
     n9:::Peach
     n1:::Sky
     n2:::Sky
     n3:::Sky
     n4:::Sky
     n5:::Ash
     n5:::Aqua
     n6:::Aqua
     n7:::Aqua
     n11:::Ash
     n10:::Ash
     n12:::Ash
     n13:::Ash
    classDef Sky stroke-width:1px, stroke-dasharray:none, stroke:#374D7C, fill:#E2EBFF, color:#374D7C
    classDef Rose stroke-width:1px, stroke-dasharray:none, stroke:#FF5978, fill:#FFDFE5, color:#8E2236
    classDef Peach stroke-width:1px, stroke-dasharray:none, stroke:#FBB35A, fill:#FFEFDB, color:#8F632D
    classDef Aqua stroke-width:1px, stroke-dasharray:none, stroke:#46EDC8, fill:#DEFFF8, color:#378E7A
    classDef Ash stroke-width:1px, stroke-dasharray:none, stroke:#999999, fill:#EEEEEE, color:#000000
    style s1 stroke:#FFFFFF,fill:#616161,color:none

```