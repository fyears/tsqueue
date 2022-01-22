## implementation of Queue and Stack in TypeScript/JavaScript

Inspired from [this](https://stackoverflow.com/questions/1590247/how-do-you-implement-a-stack-and-a-queue-in-javascript).

An array is a stack in js. But `Array.prototype.shift()` is **NOT** an O(1) operation. So a queue should be implemented using two stacks to get amortized O(1) `pop` time.
