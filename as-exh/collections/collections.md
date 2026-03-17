# Collection membership and pages

## Preliminaries
In what follows, IRIs have to be resolved considering the base namespace `https://www.w3.org/ns/activitystreams#`

In Activity Streams, the members of a collection are identified through the property `items`. More specifically, an object `o` is a member of the collection `c` iff `c items o` holds.

A Collection can be divided into distinct subsets called _pages_ (see [Collection Paging](https://www.w3.org/TR/activitystreams-core/#h-paging)). The collection a collection page belongs to is identified through the property `partOf`. More specifically, 'p' is a page of a collection 'c' iff 'p partOf c' holds. In addition, collection pages are collections themselves, so that they have their own members. 
