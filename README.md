This perfectly reduced demo project shows that the vitest extension for VSCode does not allow debugging of tests.

running tests works:

![image](https://github.com/user-attachments/assets/7b68f885-8c03-4014-bc3d-8d2e8b22a874)

but debuggung not:

![image](https://github.com/user-attachments/assets/a426cb6d-b34f-46fe-b08c-0b74e882c9dc)

```
[INFO 1:13:45 PM] [DEBUG] Starting debugging session C:\Program Files\nodejs\node.EXE
[INFO 1:13:45 PM] [DEBUG] Debugging started
[INFO 1:13:45 PM] Running 1 file(s): example.test.js
[1:13:45 PM] Starting a test run because example.test.js triggered a watch rerun event
[1:13:45 PM] No task result for "example.test.js", ignoring
[1:13:45 PM] Marking "example.test.js" as failed with 1 errors
[1:13:45 PM] Ending test run example.test.js
[1:13:45 PM] Test run promise is finished, the queue is 0
[1:13:46 PM] [VSCODE] Ignoring file: node_modules\.vite\results.json
[1:13:46 PM] [API] Vitest WebSocket connection closed, cannot call RPC anymore.
[1:13:46 PM] Disposing test runner
[1:13:46 PM] Ending test run <none>
```
