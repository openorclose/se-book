<span id="prereqs"></span>

<span id="outcomes">{{ icon_outcome }} Can explain the meaning of composition</span>

<span id="title">Composition</span>

<div id="body">

**A composition is an association that represents a strong _whole-part_ relationship.** When the _whole_ is destroyed, _parts_ are destroyed too.

<box>

{{ icon_example }} A `Board` (used for playing board games) consists of `Square` objects.

</box>

**Composition also implies that there cannot be cyclical links**. 

<box>

{{ icon_example }} The ‘sub-folder’ association between `Folder` objects is a composition type association. That means if the `Folder` object `foo` is a sub folder of `Folder` object `bar`, `bar` cannot be a sub-folder of `foo`. 

</box>

##### Implementing composition

**Composition is implemented using a normal variable.** If correctly implemented, the ‘part’ object will be deleted when the ‘whole’ object is deleted. Ideally, the ‘part’ object may not even be visible to clients of the ‘whole’ object.

<box>


<div class="alt-java float-right ml-5">

```java
class Email {
    private Subject subject;
  ...
}
```

</div>
<div class="alt-python  float-right ml-5">

```python
class Email:

  def __init__(self):
    self.__subject = Subject()
```
</div>

{{ icon_example }} In this code, the `Email` has a composition type relationship with the `Subject` class, in the sense that the subject is part of the email.

</box>


</div>

<div id="extras">
</div>