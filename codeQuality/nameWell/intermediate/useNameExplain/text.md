<span id="title">Use Name to Explain</span>

<span id="prereqs"></span>

<span id="outcomes">{{ icon_outcome }} Can improve code quality using technique: use name to explain </span>

<div id="body">

**A name is not just for differentiation; it should explain the named entity to the reader accurately and at a sufficient level of detail.**

<box>

Examples:

| {{bad}}          |  {{good}}                     |
| ----------------- |  ----------------------------- |
|`processInput()`  (what 'process'?) |  `removeWhiteSpaceFromInput()` |
|`flag`   |  `isValidInput` |
|`temp`   |   |

</box>

**If the name has multiple words, they should be in a sensible order.**

<box>

Examples:

| {{bad}}        |  {{good}}       |
| --------------- |  --------------- |
|`bySizeOrder()`  |  `orderBySize()` |

</box>

Imagine going to the doctor's and saying "My eye1 is swollen"! Don’t use numbers or case to distinguish names.

<box>

Examples:

| {{bad}}          | {{bad}}          | {{good}}                     |
| ----------------- | ----------------- | ----------------------------- |
|`value1`, `value2` | `value`, `Value`  | `originalValue`, `finalValue` |

</box>


</div>

<div id="extras">
</div>