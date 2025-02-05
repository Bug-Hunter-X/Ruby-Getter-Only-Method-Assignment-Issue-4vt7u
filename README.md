# Ruby Getter-Only Method Assignment Issue

This example demonstrates a subtle issue in Ruby related to getter methods.  If you only define a getter method for an instance variable, using the getter's name to assign a value will not modify the instance variable. This can lead to unexpected behavior and hard-to-debug errors.