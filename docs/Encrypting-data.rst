###############
Encrypting data
###############

.. _-disclaimer-encryption-is-not-completely-secure-do-not-use-it-to-store-important-data-such-as-passwords:

\**\* DISCLAIMER: Encryption is not completely secure, do not use it to store important data such as passwords.**\*
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

To encrypt data, use:

.. code:: py

   kvJSON.encryptData("key")

As of now, only alphanumerical characters work for encryption. Anything
else will cause an error.