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
      <td rowspan="3"><a href="https://www.w3.org/TR/activitystreams-vocabulary/#dfn-invite">Invite definition</a>.</td>
    </tr>
    <tr>
      <th name="CQ33"><a href="#CQ33">CQ33</a></th>
      <td>What objects a given actor invited a specific target for?</td>
    </tr>
    <tr>
      <th name="CQ34"><a href="#CQ34">CQ34</a></th>
      <td>What targets have been ivited for a given object by a specific actor?</td>
    </tr>
    <tr>
      <th name="CQ35"><a href="#CQ35">CQ35</a></th>
      <td>Which actors rejected a given object?</td>
      <td rowspan="2"><a href="https://www.w3.org/TR/activitystreams-vocabulary/#dfn-reject">Reject definition</a>.</td>
    </tr>
    <tr>
      <th name="CQ36"><a href="#CQ36">CQ36</a></th>
      <td>What objects were rejected by a given actor?</td>
    </tr>
    <!-- TODO TentativeReject -->
    <!-- TODO segnalare che remove dovrebbe avere un target -->
    <tr>
      <th name="CQ37"><a href="#CQ37">CQ37</a></th>
      <td>Which actors removed a given object?</td>
      <td rowspan="2"><a href="https://www.w3.org/TR/activitystreams-vocabulary/#dfn-remove">Remove definition</a>.</td>
    </tr>
    <tr>
      <th name="CQ38"><a href="#CQ38">CQ38</a></th>
      <td>What objects were removed by a given actor?</td>
    </tr>
    <tr>
      <th name="CQ39"><a href="#CQ39">CQ39</a></th>
      <td>Which actors have undone a given object?</td>
      <td rowspan="2"><a href="https://www.w3.org/TR/activitystreams-vocabulary/#dfn-undo">Undo definition</a>.</td>
    </tr>
    <tr>
      <th name="CQ40"><a href="#CQ40">CQ40</a></th>
      <td>What objects have been undone by a given actor?</td>
    </tr>
    <tr>
      <th name="CQ41"><a href="#CQ41">CQ41</a></th>
      <td>Which actors updated a given object?</td>
      <td rowspan="2"><a href="https://www.w3.org/TR/activitystreams-vocabulary/#dfn-update">Update definition</a>.</td>
    </tr>
    <tr>
      <th name="CQ42"><a href="#CQ42">CQ42</a></th>
      <td>What objects were updated by a given actor?</td>
    </tr>
    <tr>
      <th name="CQ43"><a href="#CQ43">CQ43</a></th>
      <td>Which actors viewed a given object?</td>
      <td rowspan="2"><a href="https://www.w3.org/TR/activitystreams-vocabulary/#dfn-view">View definition</a>.</td>
    </tr>
    <tr>
      <th name="CQ44"><a href="#CQ44">CQ44</a></th>
      <td>What objects were viewed by a given actor?</td>
    </tr>
    <tr>
      <th name="CQ45"><a href="#CQ45">CQ45</a></th>
      <td>Which actors have listened a given object?</td>
      <td rowspan="2"><a href="https://www.w3.org/TR/activitystreams-vocabulary/#dfn-listen">Listen definition</a>.</td>
    </tr>
    <tr>
      <th name="CQ46"><a href="#CQ46">CQ46</a></th>
      <td>What objects were lietened by a given actor?</td>
    </tr>
    <tr>
      <th name="CQ47"><a href="#CQ47">CQ47</a></th>
      <td>Which actors read a given object?</td>
      <td rowspan="2"><a href="https://www.w3.org/TR/activitystreams-vocabulary/#dfn-read">Read definition</a>.</td>
    </tr>
    <tr>
      <th name="CQ48"><a href="#CQ48">CQ48</a></th>
      <td>What objects were read by a given actor?</td>
    </tr>
    <tr>
      <th name="CQ49"><a href="#CQ49">CQ49</a></th>
      <td>Which actors moved a given object from a specific origin to a specific target?</td>
      <td rowspan="4"><a href="https://www.w3.org/TR/activitystreams-vocabulary/#dfn-move">Move definition</a>.</td>
    </tr>
    <tr>
      <th name="CQ50"><a href="#CQ50">CQ50</a></th>
      <td>What objects were moved by a given actor from a specific origin to a specific target?</td>
    </tr>
    <tr>
      <th name="CQ51"><a href="#CQ51">CQ51</a></th>
      <td>What origins a specific object was moved from by a given actor and to a specific target?</td>
    </tr>
    <tr>
      <th name="CQ52"><a href="#CQ52">CQ52</a></th>
      <td>What targets a specific object was moved to by a given actor from a specific origin?</td>
    </tr>
    <tr>
      <th name="CQ53"><a href="#CQ53">CQ53</a></th>
      <td>Which actors traveled from a specific origin to a specific target?</td>
      <td rowspan="3"><a href="https://www.w3.org/TR/activitystreams-vocabulary/#dfn-travel">Travel definition</a>.</td>
    </tr>
    <tr>
      <th name="CQ54"><a href="#CQ54">CQ54</a></th>
      <td>What origins a specific agent has traveled from to a specific target?</td>
    </tr>
    <tr>
      <th name="CQ55"><a href="#CQ55">CQ55</a></th>
      <td>What targets a specific actor has traveled to from a specific origin?</td>
    </tr>
    <tr>
      <th name="CQ56"><a href="#CQ56">CQ56</a></th>
      <td>Which actors announced a given object to a specific target?</td>
      <td rowspan="3"><a href="https://www.w3.org/TR/activitystreams-vocabulary/#dfn-announce">Announce definition</a>.</td>
    </tr>
    <tr>
      <th name="CQ57"><a href="#CQ57">CQ57</a></th>
      <td>What objects were announced by a given actor to a specific target?</td>
    </tr>
    <tr>
      <th name="CQ58"><a href="#CQ58">CQ58</a></th>
      <td>What targets were announced about a specific object by a given actor?</td>
    </tr>
    
  </tbody>
</table>
