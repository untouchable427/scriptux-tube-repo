# scriptux-tube-repo

Applying YouTube tutorials to be implemented in script form via terminal emulator.

## Plan to follow

This repository is currently a lightweight starting point, so the plan is intentionally simple and transparent:

1. Pick one tutorial task to reproduce in a terminal-friendly script.
2. Break the tutorial into small, repeatable command-line actions.
3. Write those actions in script form so they can be rerun without guessing.
4. Test the script steps in the terminal and confirm the expected output.
5. Refine the instructions until someone else can follow them from start to finish.

## How work should be carried out

To keep the work understandable, any contributor or automation working in this repository should explain actions in plain language so it is clear what is happening:

1. **Understand the request**
   - Read the issue or prompt first.
   - Identify the real requirement before touching any files.
   - Restate the requirement in simple terms before starting the implementation.

2. **Inspect the repository**
   - Check which files already exist.
   - Look for source code, tests, or setup files before deciding what to change.
   - If the repository is still mostly documentation, make the change there; if code exists, change the smallest relevant source files instead.

3. **Choose the smallest complete change**
   - Avoid adding unnecessary files or tools.
   - Update only the parts of the repository that are needed to satisfy the request.
   - Match the solution to the current request and the current state of the repository, whether that means documentation, scripts, tests, or source code.

4. **Document the plan clearly**
   - Write the plan as ordered steps.
   - Describe each step so readers know both **what** happens and **why** it happens.
   - This makes the repository easier to follow for future work.

5. **Verify the result**
   - Reread the changed file to confirm the wording is clear.
   - Check that the change matches the request and does not introduce unrelated edits.
   - Since there is no test suite yet, manual verification of the documentation is the appropriate validation here.

6. **Report progress**
   - Record what has been completed and what is still pending.
   - This gives readers a traceable summary of the work instead of silent changes.

## Expected next step

The next practical step for this repository is to add the first real script and keep the same style of step-by-step explanation so both the script behavior and the agent behavior stay easy to understand.
