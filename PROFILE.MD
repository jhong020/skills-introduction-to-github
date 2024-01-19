# This is a test
- While I think html tags work <bold>test</bold>, it is faster to use markdown. For example instead of <code>int i</code>, we can use `int i`
This can be seen to have tremendous advantage, for example, traditionaly, a unordered list is declared like the following:
<ul>
  <li>item 1</li>
  <li>item 2</li>
</ul>
it can be simply done through adding `-` infront of the statements, and child items added using identation. <br>

1. This is an example
   - this is a child

<br>
Or at least that is what it seems to be.. the documentation mentions that you have to specify it <bold>DIRECTLY BELOW</bold> the bloody <emphasis>character</emphasis>. Jesus christ.
Jamie pull up how it was done in <code>html</code>:<br><br>

```
  <ul>
    <li>List</li>
      <ul>
        <li>child</li>
      </ul>
    <li>List2</li>
  </ul>
```


