# Part1 Answer

1. Line 9 print "values added: 20".
2. Line 13 print "final result: 20".
3. Line 9 print "values added: 20".
4. Line 13 returns an error that result is not defined. Because result is declared and assigned insided the if statement block, the scope of variable result is within the if statement, while line 13 is outside of the if statement. Thus, line 13 can't find the variable result.
5. Line 9 returns a TypeError: Assignment to constant variable. Because constant variable can't be reassigned value after initilization.
6. Line 13 returns the same error as line 9, and the reason is the same.