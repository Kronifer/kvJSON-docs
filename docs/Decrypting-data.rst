###############
Decrypting data
###############

To decrypt data, you would do something like this:

.. code:: py

   key = kvJSON.getEncryptKey("1")

   kvJSON.decryptData("datakey", key)

This decrypts the data in the table. Make sure replace "datakey" with
the key of the value you want to decrypt. If you want the decrypted
value in a variable immediately, use:

.. code:: py

   key = kvJSON.getEncryptKey("1")

   value = kvJSON.decryptData("datakey", key)