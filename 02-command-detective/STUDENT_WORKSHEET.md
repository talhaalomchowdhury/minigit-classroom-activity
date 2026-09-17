# Activity 2 Student Worksheet

Do not merely define a command. Explain what the user observes, wants, and risks.

| Command | What does the user observe? | What is the user trying to accomplish? | What problem or risk is addressed? |
|---|---|---|---|
| `status` | User can see the state of the tracked or untracked files | check the working directory before and after staging | mistakenly commit unwanted files |
| `diff` | Line by line changes like addition deletion and modification | inspect the code to make sure they are correct | unwanted changes and bugs. |
| `add <file>` | files move to staged area | can select single or a bundle of files from working tree for staging. | save a working file from getting messedup |
| `commit -m "message"` | A way to save changes using a text of the changes into local | permanently record a working file including changing history | Prevent from losing a working files |
| `log` |  |  |  |

Example for a non-Git command: A “print” command produces a paper copy; the user wants information usable away from the computer; the risk is lacking access during a meeting.

**UN-01:** A developer needs a way to inspect line by line code modification and the state of the current working tree before stage them.

because blindly saving code can create bugs.
Evidence command(s): git diff, git status
**UN-02:** A team member needs a way to know what the new changes and the previous working tree to understand the changes and working flow.
because without knowing the new changes and the previous workflow or commit history they may write some unwanted changes outside of the project requirement.

Evidence command(s): git log, git commit, git add.
