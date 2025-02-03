# Ruby Bug: Unexpected Behavior from Directly Modifying Instance Variables

This repository demonstrates a common Ruby bug involving directly manipulating instance variables using `instance_variable_set` and `instance_variable_get`.  Directly accessing instance variables bypasses the intended encapsulation and can lead to unpredictable program behavior, particularly in larger, more complex projects.

The `bug.rb` file showcases the problem.  The solution (`bugSolution.rb`) demonstrates a better approach involving accessor methods.