# std:op
## container library operations
- todo(matt): move into lib/op
#### calc
- calc the size of a path within container
#### create
- recreate a new empty container
#### ctest
- test the container
#### ctier
- extend container with new tier
#### ctree
- used by consolidate to restructure container
#### empty 
- completely empty header only container, with markers and word empty section
#### export
- container export - this is controlled by modes...
#### id 
- get a std container id that is unique
#### import
- import another container into the current container
#### imut
- make a dotpath as immutable
#### mod
- change a container path using selector format to change _anything_
#### mut 
- mutate a direct path and just one value, fast
#### q 
- query paths
#### qbuf
- get all buffers
#### ...
#### repair
- check inner consistency and data stored within buffers
#### rtest
- check repair is needed
#### sbuf
- set a new buffer as an interface, this is how anything is added
#### sfixed
- sets a fixed sized buffer for arbitrary data
#### sign
- signs a data buffer, for checksum, optional
#### stest
- sets a test that the container must perform this is not transmutable to other hosts
#### stier
- creates a tier level - a container can have tiers of tiers, as an auto tree, tiers are typically used to differ from vendor protected data and free data... in practive you want to avoid such complexities.. a consolidation will serialise super deep structures into faster chunks...
#### swrite
- standard write for bulk data, or one data etc
