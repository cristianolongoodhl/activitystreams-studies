# Collection membership and pages

## Preliminaries
In what follows, IRIs have to be resolved considering the base namespace `https://www.w3.org/ns/activitystreams#`

In Activity Streams, the members of a collection are identified through the property `items`. More specifically,
an object `o` is a member of the collection `c` iff `c items o` holds.
