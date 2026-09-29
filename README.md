# Karel the Robot

My work from the first few weeks of COSC 10001 at TCU, where we focused on programming basics using Karel.  
Karel is a robot that only knows four commands: move(), turnLeft(), pickBeeper(), and putBeeper().  

---

To run it, open the folder in IntelliJ and press the green run button at the top of the screen.  
Alternatively, you can execute <code>run.ps1</code> on Windows or <code>run.sh</code> on macOS.  

---

<ul>
    <li>Karel has no turnRight() method, so I built one by calling turnLeft() three times.</li>
    <li>In a scenario where Karel cannot count, doubling the amount of beepers on a space requires some thought.  I accomplished this by using two spaces:
        <ul>
            <li>Every time I moved a beeper over one space, I placed an extra one.</li>
            <li>After this, I moved all of those beepers back to the original space.</li>
        </ul>
    </li>
</ul>