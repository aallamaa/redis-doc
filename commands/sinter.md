@complexity

O(N*M) worst case where N is the cardinality of the smallest set and M is the
number of sets.

Returns the members of the set resulting from the intersection of all the given
sets.

For example:

    key1 = {a,b,c,d}
    key2 = {c}
    key3 = {a,c,e}
    SINTER key1 key2 key3 = {c}

Keys that do not exist are considered to be empty sets. With one of the keys
being an empty set, the resulting set is also empty (since set intersection
with an empty set always results in an empty set).

@return

@multi-bulk-reply: list with members of the resulting set.

