#############
Grouping data
#############

To group data, do:

.. code:: py
    kvJSON.addData("test1", "value")
    kvJSON.addData("test2", "value1")
    kvJSON.groupData(["test1", "test2"], "testVars")

This allows you to kvJSON.getGroup() and pull the values into a list variable.
