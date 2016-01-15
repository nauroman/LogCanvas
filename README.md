# Unity Log Canvas

**Using:**

Put LogCanvas prefab on your scene, then:

```
using UnityEngine;
using System.Collections;
using Flashunity.Logs;


public class BTest : MonoBehaviour
{

    void Start()
    {
        Log.Add("Hello World!");
        Log.Add("Green", "green");
        Log.Add("Black", "black");
        Log.Warning("Warning test");
        Log.Error("Error test");
        Log.Add(Log.Props(this));

        Log.Visible = true;
    }
}
```