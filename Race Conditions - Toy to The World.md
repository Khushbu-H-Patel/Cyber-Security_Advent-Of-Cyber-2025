# Race Conditions - Toy to The World

A race condition happens when two or more actions occur at the same time and the system outcome completely depends on the order in which they finish.

**Types of Race Conditions:**

**Time-of-Check to Time-of-Use (TOCTOU):** A TOCTOU race condition happens when a program checks something first and uses it later, but the data changes in between. This means what was true at the time of the check might no longer be true when the action happens.

**Shared resource:** This occurs when multiple users or systems try to change the same data simultaneously without proper control. Since both updates happen together, the final result depends on which one finishes last, creating confusion.

**Atomicity violation:** An atomic operation should happen all at once, either fully done or not at all. When parts of a process run separately, another request can sneak in between and cause inconsistent results.

This room also explains the BurpSuite which is web security testing tool. It sits between browser and website acting like man in the middle. So, every time whenever any actions are performed burp can see exactly same requests the browser sends.

[20 Race Conditions - Toy to The World.docx](https://github.com/user-attachments/files/24840341/20.Race.Conditions.-.Toy.to.The.World.docx)
