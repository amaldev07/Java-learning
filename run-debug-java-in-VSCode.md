https://chatgpt.com/share/6901c978-df34-8009-82bf-58b00390b34d

1️⃣ Install Java JDK
Download JDK 17 (LTS): Search “Download JDK 17” → install
2️⃣ Install Java Extension Pack in VS Code
Extensions → search Java Extension Pack → Install

Step 1: Open terminal inside VS Code -> Ctrl + ` (You must be inside the same folder where file is saved.)

Step 3: Compile the program ✅
javac OddNumbers.java
OddNumbers.class

Step 4: Run the program ✅
java OddNumbers

----------------------------------------
Another ways

🌟 Option 1: Run Button (Easiest)
VS Code shows a Run play button above main method.
It looks like: ▶️ Run | Debug
Just click ▶️ Run → DONE ✅

🌟 Option 2: Right-click → Run Java
Right-click anywhere inside the editor:
Run Java

🌟 Then you can run from top-right play icon via Code Runner.

-----------------------------------
? how can i debug in vs code
 

1️⃣ Ensure you see the Run and Debug button
Install extensions (if not installed earlier):
Java Extension Pack
Debugger for Java

2️⃣ Set a Breakpoint
Click to the left of a line number
A red dot appears like a target 🎯
Example: set it inside your loop
if (i % 2 != 0) {
    System.out.println(i + " is odd"); // <-- CLICK HERE
}

3️⃣ Click Debug ▶️🐞
Above the main method:
▶ Debug

or press:
F5

VS Code will:

Pause the program exactly at your breakpoint

Show debugging tools at the top

4️⃣ Watch Variables Live
Open Run & Debug view:
Left sidebar → Bug icon 🐞
You will see:

Local variables (like i)

Their changing values every loop


You can also hover the mouse over variables to see values.
