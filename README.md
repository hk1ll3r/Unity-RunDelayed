# Unity-RunDelayed
A helper method to easily execute delayed logic in MonoBehaviours. The syntax looks like below.

```csharp
void Start()
{
    RunDelayed(2f, () => {
        Debug.Log("delayed console log!"); 
    });
}
```

The implementation is a thin wrapper around Coroutines.

Read my [blog post](https://medium.com/@nosuchstudio/implementing-a-rundelayed-helper-in-unity-d359b757b2fa) to know the background.
