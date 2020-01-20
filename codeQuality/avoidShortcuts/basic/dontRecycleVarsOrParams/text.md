<span id="title">Don't Recycle Variables or Parameters</span>

<span id="prereqs"></span>

<span id="outcomes">{{ icon_outcome }} Can improve code quality using technique: don't recycle variables or parameters </span>

<div id="body">

*	Use one variable for one purpose. Do not reuse a variable for a different purpose other than its intended one, just because the data type is the same.
*	Do not reuse formal parameters as local variables inside the method.

<box>

{{bad}}
```java
double computeRectangleArea(double length, double width) {
    length = length * width;
    return length;
}

```
{{good}}
```java
double computeRectangleArea(double length, double width) {
    double area;
    area = length * width;
    return area;
}
```

</box>

</div>

<div id="extras">
</div>