# CountUp Script - Unity C# Example

This project demonstrates the use of various C# features within a Unity script. The `CountUp` script is designed to update multiple `TextMeshPro` UI elements with a continually increasing value or randomly generated values. 

## Topics Learned

- **Unity Basics**: Understanding `MonoBehaviour`, `Start()`, and `Update()` methods.
- **TextMeshPro**: Using `TextMeshProUGUI` for displaying text in Unity's UI system.
- **Access Modifiers**: Working with `private`, `public`, and other access modifiers.
- **Serialized Fields**: Making private fields visible and adjustable within the Unity Inspector using `[SerializeField]`.
- **Arrays**: Creating and initializing arrays for storing multiple values and references.
- **Loops**:
  - `for` loop
  - `while` loop
  - `do-while` loop
  - `foreach` loop
- **Time Handling**: Using `Time.deltaTime` for frame-rate independent time-based operations.
- **Random Numbers**: Generating random numbers using `Random.Range()`.

## How to Use

1. **Set Up in Unity**:
   - Create a new Unity project or use an existing one.
   - Attach the `CountUp` script to a GameObject in the scene.
   - Drag and drop multiple `TextMeshProUGUI` objects into the `Atext` array field via the Unity Inspector.
   - Adjust the `Speed` variable to control how fast the values update.

2. **Customization**:
   - Modify the `Speed` value to change the rate at which the time value increases.
   - Use the loops section in the `Update` method to experiment with different ways of updating multiple text fields.

## Conclusion

This script demonstrates a variety of core Unity and C# concepts, including arrays, loops, time handling, and working with UI elements using TextMeshPro. It serves as a good starting point for learning and experimenting with these topics in Unity.
