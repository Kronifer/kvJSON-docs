#########################
Getting an encryption key
#########################

Once you've encrypted data, you have to get the encryption key before
you can decrypt the data. To pull the encryption key, use:

.. code:: py

   kvJSON.getEncryptKey("keynumber")

Keynumber corresponds with the data you encrypted. If you want the data
with the key "test" to decrypt and that was the first data you
encrypted, you would have key number as 1.