# Activity Streams 2.0 Competency Questions

Some [competency questions](https://doi.org/10.1007/978-3-031-47262-6_3) for a knowledge base adopting the [Activity Vocabulary](https://www.w3.org/TR/activitystreams-vocabulary/). 

<table>
  <thead>
    <tr>
      <th>Code</th><th>Question</th><th>Specification</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th colspan="3">Collections</th>
    </tr>
    <tr>
      <th name="CQ1"><a href="#CQ1">CQ1</a></th>
      <td>What are the members of a collection?</td>
      <td><a href="https://www.w3.org/TR/activitystreams-vocabulary/#dfn-collection">Collections definition</a>, <a href="https://www.w3.org/TR/activitystreams-core/#collection">Collection</a>.</td>
    </tr>
    <tr>
      <th name="CQ2"><a href="#CQ2">CQ2</a></th>
      <td>What are the pages of a collection?</td>
      <td><a href="https://www.w3.org/TR/activitystreams-core/#collection">Collection</a>.</td>
    </tr>
    <tr>
      <th name="CQ3"><a href="#CQ3">CQ3</a></th>
      <td>What collection a page belongs to?</td>
      <td><a href="https://www.w3.org/TR/activitystreams-core/#collection">Collection</a>, <a href="https://www.w3.org/TR/activitystreams-core/#dfn-collectionpage">Collection page</a>.</td>
    </tr>
    <tr>
      <th name="CQ4"><a href="#CQ4">CQ4</a></th>
      <td>Given a paged collection, what is its first page?</td>
      <td><a href="https://www.w3.org/TR/activitystreams-core/#collection">Collection</a>, <a href="https://www.w3.org/TR/activitystreams-core/#dfn-collectionpage">Collection page</a>, <a href="https://www.w3.org/TR/activitystreams-vocabulary/#dfn-first">first property definition</a>.</td>
    </tr>
    <tr>
      <th name="CQ5"><a href="#CQ5">CQ5</a></th>
      <td>Given a paged collection, what is its last page?</td>
      <td><a href="https://www.w3.org/TR/activitystreams-core/#collection">Collection</a>, <a href="https://www.w3.org/TR/activitystreams-core/#dfn-collectionpage">Collection page</a>, <a href="https://www.w3.org/TR/activitystreams-vocabulary/#dfn-last">last property definition</a>.</td>
    </tr>
    <tr>
      <th name="CQ6"><a href="#CQ6">CQ6</a></th>
      <td>Given a paged collection, what is its page containing the last updated items?</td>
      <td><a href="https://www.w3.org/TR/activitystreams-core/#collection">Collection</a>, <a href="https://www.w3.org/TR/activitystreams-core/#dfn-collectionpage">Collection page</a>, <a href="https://www.w3.org/TR/activitystreams-vocabulary/#dfn-current">current property definition</a>.</td>
    </tr>
    <tr>
      <th name="CQ7"><a href="#CQ7">CQ7</a></th>
      <td>Given a paged collection and one of its pages, what is the page predecessor in the collection?</td>
      <td><a href="https://www.w3.org/TR/activitystreams-core/#collection">Collection</a>, <a href="https://www.w3.org/TR/activitystreams-core/#dfn-collectionpage">Collection page</a>, <a href="https://www.w3.org/TR/activitystreams-vocabulary/#dfn-prev">prev property definition</a>.</td>
    </tr>
    <tr>
      <th name="CQ8"><a href="#CQ8">CQ8</a></th>
      <td>Given a paged collection and one of its pages, what is the page successor in the collection?</td>
      <td><a href="https://www.w3.org/TR/activitystreams-core/#collection">Collection</a>, <a href="https://www.w3.org/TR/activitystreams-core/#dfn-collectionpage">Collection page</a>, <a href="https://www.w3.org/TR/activitystreams-vocabulary/#dfn-prev">next property definition</a>.</td>
    </tr>
    <tr>
      <th name="CQ9"><a href="#CQ9">CQ9</a></th>
      <td>What are all the pages of a collection, if any?</td>
      <td><a href="https://www.w3.org/TR/activitystreams-core/#collection">Collection</a>, <a href="https://www.w3.org/TR/activitystreams-core/#dfn-collectionpage">Collection page</a>.</td>
    </tr>
    <tr>
      <th colspan="3">Activities</th>
    </tr>
    <tr>
      <th name="CQ10"><a href="#CQ10">CQ10</a></th>
      <td>Which actors accepted a given object?</td>
      <td rowspan="2"><a href="https://www.w3.org/TR/activitystreams-vocabulary/#dfn-accept">Accept definition</a>.</td>
    </tr>
    <tr>
      <th name="CQ11"><a href="#CQ11">CQ11</a></th>
      <td>What objects were accepted by a given actor?</td>
    </tr>
    <tr>
      <td colspan="3">TODO TentativeAccept</td>
    </tr>
    <tr>
      <th name="CQ12"><a href="#CQ12">CQ12</a></th>
      <td>Which actors added a given object to a specific target?</td>
      <td rowspan="3"><a href="https://www.w3.org/TR/activitystreams-vocabulary/#dfn-add">Add definition</a>.</td>
    </tr>
    <tr>
      <th name="CQ13"><a href="#CQ13">CQ13</a></th>
      <td>What objects were added by a given actor to a specific target?</td>
    </tr>
    <tr>
      <th name="CQ14"><a href="#CQ14">CQ14</a></th>
      <td>What targets a given object was added to by a specific actor?</td>
    </tr>
    <tr>
      <th name="CQ15"><a href="#CQ15">CQ15</a></th>
      <td>Which actors arrived at a specified location?</td>
      <td rowspan="2"><a href="https://www.w3.org/TR/activitystreams-vocabulary/#dfn-arrive">Arrive definition</a>.</td>
    </tr>
    <tr>
      <th name="CQ16"><a href="#CQ16">CQ16</a></th>
      <td>What are the locations a given actor has arrived?</td>
    </tr>
    <tr>
      <th name="CQ17"><a href="#CQ17">CQ17</a></th>
      <td>Which actors created a given object?</td>
      <td rowspan="2"><a href="https://www.w3.org/TR/activitystreams-vocabulary/#dfn-create">Create definition</a>.</td>
    </tr>
    <tr>
      <th name="CQ18"><a href="#CQ18">CQ18</a></th>
      <td>What objects were created by a given actor?</td>
    </tr>
    <tr>
      <th name="CQ19"><a href="#CQ19">CQ19</a></th>
      <td>Which actors deleted a given object?</td>
      <td rowspan="2"><a href="https://www.w3.org/TR/activitystreams-vocabulary/#dfn-delete">Delete definition</a>.</td>
    </tr>
    <tr>
      <th name="CQ20"><a href="#CQ20">CQ21</a></th>
      <td>What objects were deleted by a given actor?</td>
    </tr>
    <tr>
      <th name="CQ21"><a href="#CQ21">CQ21</a></th>
      <td>Which actors followed a given object?</td>
      <td rowspan="2"><a href="https://www.w3.org/TR/activitystreams-vocabulary/#dfn-follow">Follow definition</a>.</td>
    </tr>
    <tr>
      <th name="CQ22"><a href="#CQ22">CQ22</a></th>
      <td>What objects were followed by a given actor?</td>
    </tr>
    <tr>
      <th name="CQ23"><a href="#CQ23">CQ23</a></th>
      <td>Which actors ignored a given object?</td>
      <td rowspan="2"><a href="https://www.w3.org/TR/activitystreams-vocabulary/#dfn-ignore">Ignore definition</a>.</td>
    </tr>
    <tr>
      <th name="CQ24"><a href="#CQ24">CQ24</a></th>
      <td>What objects were ignored by a given actor?</td>
    </tr>
    <tr>
      <th name="CQ25"><a href="#CQ25">CQ25</a></th>
      <td>Which actors joined a given object?</td>
      <td rowspan="2"><a href="https://www.w3.org/TR/activitystreams-vocabulary/#dfn-join">Join definition</a>.</td>
    </tr>
    <tr>
      <th name="CQ26"><a href="#CQ26">CQ26</a></th>
      <td>What objects were joined by a given actor?</td>
    </tr>
    <tr>
      <th name="CQ27"><a href="#CQ27">CQ27</a></th>
      <td>Which actors left a given object?</td>
      <td rowspan="2"><a href="https://www.w3.org/TR/activitystreams-vocabulary/#dfn-left">Left definition</a>.</td>
    </tr>
    <tr>
      <th name="CQ28"><a href="#CQ28">CQ28</a></th>
      <td>What objects were left by a given actor?</td>
    </tr>
    <tr>
      <th name="CQ29"><a href="#CQ29">CQ29</a></th>
      <td>Which actors liked a given object?</td>
      <td rowspan="2"><a href="https://www.w3.org/TR/activitystreams-vocabulary/#dfn-like">Like definition</a>.</td>
    </tr>
    <tr>
      <th name="CQ30"><a href="#CQ30">CQ30</a></th>
      <td>What objects were liked by a given actor?</td>
    </tr>
    <tr>
      <th name="CQ31"><a href="#CQ31">CQ31</a></th>
      <td>Which actors offered a given object?</td>
      <td rowspan="2"><a href="https://www.w3.org/TR/activitystreams-vocabulary/#dfn-offer">Offer definition</a>.</td>
    </tr>
    <tr>
      <th name="CQ30"><a href="#CQ30">CQ30</a></th>
      <td>What objects were liked by a given actor?</td>
    </tr>
    <!-- TODO TARGET -->
    <tr>
      <th name="CQ32"><a href="#CQ32">CQ32</a></th>
      <td>Which actors invited a given target for a specific object?</td>
      <td rowspan="2"><a href="https://www.w3.org/TR/activitystreams-vocabulary/#dfn-invite">Invite definition</a>.</td>
    </tr>
    <tr>
      <th name="CQ33"><a href="#CQ33">CQ33</a></th>
      <td>What objects a given actor invited a specific target for?</td>
    </tr>
    <tr>
      <th name="CQ34"><a href="#CQ34">CQ34</a></th>
      <td>What targets have been ivited for a given object by a specific actor?</td>
    </tr>

  </tbody>
</table>
