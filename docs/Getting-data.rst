#############
Getting data
#############

To get data from the JSON file, use:

.. code:: py

   kvJSON.getData(key)

However, all that does is issue a return statement. To store the data in
a variable, try this:

.. code:: py

   value = kvJSON.getData(key)
