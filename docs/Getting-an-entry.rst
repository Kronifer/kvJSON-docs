################
Getting an entry
################

To get an entry from the JSON file, use:

.. code-block:: python
    
    kvJSON.getData(key)

But all this does is issue a return statement.
To save the value to a variable, use:

.. code-block:: python

    value = kvJSON.getData(key)
