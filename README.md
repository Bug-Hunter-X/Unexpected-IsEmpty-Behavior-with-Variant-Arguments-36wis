This repository demonstrates a subtle bug in VBScript related to the IsEmpty function and Variant data types.  When a Variant parameter is passed to a function without an explicit assignment, IsEmpty might not correctly identify it as empty, leading to unexpected behavior.  The `bug.vbs` file shows the problem, while `bugSolution.vbs` provides a corrected approach using the `TypeName` function for more reliable emptiness checks.