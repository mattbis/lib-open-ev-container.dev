### standard

1. this is bare bones . it just supports a binary serialiser, json, or xml.
2. its first purpose is to ensure rescue of projects no matter waht,....

  i. an export should be symbols and containers of export serialisers... it can just be this in the common formats.. it can be in various resolution containers so long as the chunk data is compatible.. ( todo ) 

a. scale, standard, precision, units. 
- standard is a grouping of all these ( todo )
- precision is the container, a subcontainer, and global for example m1 m2

the reason for this is making a fast save over a complete save with all data expected by the container should it implement and IL that you already generated and extended from the base language. In this scenario you could change the precision of the buffer data type symbols ... and how big your juicy numbers are.

b. the library doesnt know you own IL: but it can export this into a general format. 

c. tiers allow a proejct to have inner par revisions and linking common data... ( TODO: this would allow one project ot have its own complete history ) 

d. drm or vendor info is discouraged but is just another protected tier

#### examples

- mod metadata of author to the container and set software, create a free tier, and serialise a buffer into the internal buffer format.. using the standard IL symbol langauge
- do the same but use structured data ( xml, json ... )  and string format
- compare paths of the free and open tier to merge inner parts into another frakenstein project
