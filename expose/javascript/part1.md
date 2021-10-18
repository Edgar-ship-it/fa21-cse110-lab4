1.) values added: 20
2.) final result: 20
3.) value added: 20
4.) ReferenceError because "result" is being used outside of the if-statement
where it was defined. If it was defined using "var" instead of "let" then there
would be no error.
5.) Error because you can not reassign a "const" variable. It was first assigned to
0 and then it tried getting assigned to the sum of "num1" and "num2", which is not
allowed
6.) Error because the "const" variable is being used outside of its scope. It was defined in
if-statement, so it can only be called inside of the if-statement.