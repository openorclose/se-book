<span id="title">Alternative Paths</span>

<span id="prereqs"></span>

<span id="outcomes">{{ icon_outcome }} Can interpret sequence diagrams with alternative paths</span>

<div id="body">

**UML uses `alt` frames to indicate alternative paths.**

Notation:

<img src="{{baseUrl}}/uml/sequenceDiagrams/alternativePaths/images/notation.png" height="100" />
<p/>

<box>

{{ icon_example }} `Minefield` calls the `Cell#setMine` if the cell is supposed to be a mined cell, and calls the `Cell:setMineCount(...)` method otherwise.

<img src="{{baseUrl}}/uml/sequenceDiagrams/alternativePaths/images/minefieldCell.png" height="180" />
<p/>

</box>

</div>

<div id="extras">
</div>