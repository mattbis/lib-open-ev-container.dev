## todo
1. the monikiers should be all unified to be based on tag: brand-channel.
2. there is a ton of work here ... I need to spend an entire week on this at some point... 


### summary
The main aim is IL that then works with anything else but has the right level of compromise since nobody wants to dedicate a chunk of their dev year on this topic.. instead it makes it really easy... and we work around the rest.. assuming we have enough structure to go on..

Since the topic is finite.. it is reasonably easy to derive a common set of symbols and values... be it someting unique to the product, the topic, or broadly in the creative space... This is all we need to capture the sequence and linear and it can be the most minimal ( likely ) or enriched.

The complexity aspect is nested objects I assume, and then how that is exported in a painless way by implemting the `std/export` however such serialisation is likely already existing.. and since this is liberal in that it just has to export the basic contents and structure... 

### drafts

1. abstracts - this container can contain just the export, the original src in a protected tier... and open/free section which can follow the standards symbols or infact just be buffer chunks unstructured,... Since its open the standard will also provide a consolidate function to restructure a high speed export 
2. the symbols and allowed types are extremely limited.X1 is likely only text strings are allowed... plus whatever the model is exporting...
4. I'am are adding too much it will get consolidated some parts become parts of several groupings : `A0` dev/beta `B1` alpha `C2` -- uses by third party release branch --stable
5. the standard will have a proper name like  `loevcX1`
6. implementing a schema of standard means `std/export` `std/import` and serial via `std/formats` `::=> xml,json,openevcontf,<insert>` 

A. The standard is broader than most hosts will likely want to implement...
B. Therefore you can make your own schema which is a subset of the standard and annotate where you are voiding something you dont want public.
C. A valid export in the container has a Schema Section, a chunk section + plus if you implement thats it!
D. the program must implement `std/export` to get accepted at a minimum.

### general notes
A. This is not replacing your formats whatsoever.. its purpose is to ensure there is no gaming - it remains just this ....
i. this work is too important to not be freed... or lost forever.. some of it might want to escape and this will enable a painless process.
ii. Further this opens a whole world of amazing possibilities - ie diffing what went wrong - what you deleted using standard tools that worked for decades! imagine the joy - no longer being tied to an interface which is lacking in long term thinking... 
