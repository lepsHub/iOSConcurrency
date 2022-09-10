# iOSConcurrency

**DispatchQueue**
Basically allow you to submit code execution into either main queue or background queue 

**Serial vs. Concurrent**

Serial Queue is first and first out principal, In other words You can only do things in order one at the time. Once something happens or starts happening that task must finish before the next thing in that queue can happen.

Concurrent Queue use paraleleysm so we can concurrently do task at the same time, but not guarantee that every task it’s going to start or end at the same time.

**Sync vs. Async**
Sync queue it’s going to block the thread until the task is completed.
