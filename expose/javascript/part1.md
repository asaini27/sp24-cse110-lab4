1. "values added: 20"
2. error, since 'result' is defined using 'var' and therefore is in the scope of the 'if' statement and not for the 'else' statement. 
3. "values added: 20"
4. ReferenceError because 'result' is declared with 'let' in the 'if' statement and thus is only accessible within that block. 
5. error will occur on line 7 because there's an attempt to reassign the const variable 'result'. Line 7 will therefore throw at 'TypeError'.
6. ReferenceError because 'result' is declared with 'let' in the 'if' statement and thus is only accessible within that block. 