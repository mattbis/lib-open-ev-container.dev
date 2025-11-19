- a schema is added on swrite and any set operation, it describes teh chunks, this means any container export will be exportable into data to be read by another host without explictly suppporting it....

- the schema has always a local id, given canonical or a generated one that matches the known host config ( todo: this is an operation on save ... matt )

- standard start from the library container - but are welcome to be generalised to each host... so that conversion is more efficient.

- all paths within a schema are a canon
- all data paths within a container are dotpaths.. the schema can be embedded or derived from a std buffer... so long as the optype and idents match to trigger a lookup....
- all schema data is strict.. no binary or readable definition can have any syntax mistakes or errors...
   -DDiagnoseSchema
