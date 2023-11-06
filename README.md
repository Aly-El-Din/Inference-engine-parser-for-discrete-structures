# Inference-engine-parser-for-discrete-structures
# Overview
This project involves designing and implementing an inference engine that can apply inference rules to logical expressions. The engine takes logical expressions as input, identifies applicable inference rules, and generates the corresponding output based on the rules' logic. The supported inference rules are Modus Ponens, Modus Tollens, Hypothetical Syllogism, Disjunctive Syllogism, and Resolution.

# Supported Inference Rules
Modus Ponens: Given expressions of the form "P > Q" and "P," the rule allows inferring "Q."

Modus Tollens: Given expressions of the form "P > Q" and "~Q," the rule allows inferring "~P."

Hypothetical Syllogism: Given expressions of the form "P > Q" and "Q > R," the rule allows inferring "P > R."

Disjunctive Syllogism: Given expressions of the form "P v Q" and "~P," the rule allows inferring "Q."

Resolution: Given expressions of the form "P v Q" and "~P v R," the rule allows inferring "Q v R."

# Implementation Details
The program will take two logical expressions as input and apply the inference rules to generate the output. The input expressions should be simple, without parentheses, and should contain at most one binary operation.

The program will identify the type of inference rule that can be applied to the given input expressions and then perform the corresponding logical deduction. It will output the result of the inference process along with the applied rule.

# How to Use the Program
Compile and run the program.

Input two logical expressions, one per line, following the specified format.

The program will determine the applicable inference rule and generate the output.

The output will include the inferred expression and the name of the applied rule.

# Future Improvements
Enhance the program to handle more complex expressions and support additional inference rules.
Provide a user-friendly interface for input and output.
Allow for the inclusion of parentheses for grouping expressions.
Implement error handling for invalid inputs.
