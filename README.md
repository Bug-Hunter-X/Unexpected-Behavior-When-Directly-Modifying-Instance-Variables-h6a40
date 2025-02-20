# Ruby Bug: Unexpected Behavior When Directly Modifying Instance Variables

This example demonstrates a common issue in Ruby: directly modifying instance variables using `instance_variable_set` or `instance_variable_get`. While this might seem convenient, it can make code harder to maintain, debug, and lead to unexpected side effects.

The `bug.rb` file shows code that directly manipulates an instance variable. The `bugSolution.rb` shows the improved version using getter and setter methods.
