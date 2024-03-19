# Learn to Debug

At the heart of programming lies debugging. Initially, "debugging" may seem to imply merely removing bugs. However, its true essence is the ability to trace a program's execution by closely examining it. A programmer who lacks proficiency in debugging is navigating in the dark.

Those who prioritize design, analysis, or complexity theory over debugging are often detached from the practical realities of programming. The reality for programmers is far from ideal; they must deal with their own creations as well as code from major tech companies, open-source projects like GNU, and their peers, which often comes with its own set of flaws and sparse documentation. The skill to understand and inspect the execution of such code is crucial, as even minor obstacles can become insurmountable. This understanding usually requires hands-on experimentation, or in other words, debugging.

Debugging focuses on the program in action, not the static code. Purchasing software doesn't typically grant access to its source code, yet users frequently encounter discrepancies between the software's behavior and its documentation. Such issues can lead to significant problems, including system crashes. Similarly, developers might find errors in their own code that are baffling at first glance. These situations suggest that some underlying assumptions are incorrect or unexpected conditions have occurred. While directly examining the source code can sometimes resolve these mysteries, there are occasions when it fails, necessitating debugging efforts.

Gaining insights into a program's operation involves executing the code and observing certain aspects of its behavior. This may include obvious indicators like output on a display or the time interval between events, as well as more subtle elements like variable states, code execution paths, or the validity of assumptions within complex data structures. Unveiling these hidden details is key.

Common strategies for delving into a program's internal workings include:

- Utilizing debugging tools,
- Printlining - Temporarily modifying the code to print diagnostic information,
- Logging - Establishing a permanent record of a program's execution through logs.

While debugging tools are invaluable when reliable and accessible, printlining and logging are indispensable. Debugging tools might not keep pace with new developments in programming languages, and at times, their use might alter how a program runs, rendering them impractical. Moreover, certain debugging tasks, such as validating an assertion against a vast data structure, necessitate custom code modifications. Knowing how to effectively use debugging tools is beneficial, but mastering printlining and logging is essential.

Novice programmers may hesitate to modify code for debugging purposes, fearing it's akin to risky exploratory surgery. However, learning to interact with the code, to test and tweak it without causing harm, is crucial. If this process seems daunting, seeking guidance from a mentor is a wise step.
