<p>Very object-oriented graphs. An ongoing project.</p>
<p>Nodes and edges are a priori indistinguishable graph elements, in as much as they both:</p>
<pre><code>- have an index;

- hold data;

- have neighbours.
</code></pre>
<p>And that's it. A node's neighbours are edges; an edge's neighbours are nodes.</p>
<p>There are of course differences:</p>
<pre><code>- an edge has exactly 2 neighbours (excluding loops), whereas a node can have any number (including 0);

- an edge can have a direction and a multiplicity, whereas a node cannot.
</code></pre>
<p>These differences may be used to improve the implementation.</p>
<p>The symmetry, however, can be used to:</p>
<pre><code>- dualise a graph;

- generalise a graph to structures where:

    - "edges / links" have more, or less, than 2 neighbours (a fixed number or not);

    - "nodes" have "directions"... After all, orienting an edge is equivalent to ordering its neighbours.
</code></pre>
<p>Applications:</p>
<pre><code>- Other graphs

- Finite state machines

- Incidence structures

- ...
</code></pre>
</article>
  </div>
