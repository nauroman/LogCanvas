# Unity Log Canvas

**HTML5 Example:**

http://flashunity.com/logcanvas

![Screenshot](http://flashunity.com/assets/logcanvas/1.png)

**Using:**

Put LogCanvas prefab on your scene, then:

```
using Flashunity.Logs;

void Test()
{
    Log.Add("Hello World!");
    Log.Add("Green", "green");
    Log.Add("Black", "black");
    Log.Warning("Warning test");
    Log.Error("Error test");
    Log.Add(Log.Props(this));
}
```