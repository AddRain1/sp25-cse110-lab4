1. Line 9 will prints 'values added: 20'
2. Line 13 will prints 'final result: 20'
3. You should not use var because it is function-scoped, meaning it ignores blocks and can lead to bugs since it is accessible outside the block.
4. Line 9 prints 'values added: 20'
5. Line 13 will return an error that says result is not defined. This is because result is block-scoped, so it cannot be accessed outside the if-else block.
6. Line 9 prints a TypeError because it cannot assign to a constant variable.
7. Line 13 prints a ReferenceError because result is not defined. Result is not accessible outside of the block.