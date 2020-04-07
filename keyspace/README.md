# Introducing Keyspace
## Keyspace

```
Redis' keyspace is essentially a dictionary (lookup table/associative array/hashmap) for keys' values. It is considered a "schemaless" model, although there are two schemas in play:

The key-value schema, i.e. a "table" of keys and their respective values
The implicit schema, or how keys are named, which basically dictates how keys are accessed

All keys (and pointers to their values) are stored in the server's global dictionary, a.k.a the keyspace.
```
## Keyspace memory overheads:
```
Redis maintains several private data structures for managing the internals of the keyspace. These internal administrative data structures incur some overhead in terms of RAM.The bigger the dataset becomes, so do global keyspace overheads. That said, the global overheads are comparatively negligible once the dataset starts growing.

```
### Key overhead:
```
"charged" for every key in the keyspace, regardless any of the key's properties.
```

### Key Names - Guidelines
```
1. Names - Redis Strings
2. Names are important and unique and should reflect the nature of data.
3. Keep names as short as possible- as it requires RAM.
4. ":" are used to delimit parts in the name. 
5. Considering using a hash function(eg. Sha1).

```
### Logical/Shared/numbered databases
```
```
### Pattern : Single application key namespacing
```

```
