##################
Index of Functions
##################

kvJSON.init(filename):
    Initiate your project for using kvJSON.

    :filename: The filename you want to use for storing data.
    

kvJSON.addData(key, value):
    Add data in the form of a key-value pair.

    :key: The key you want to store data under.

    :value: The data you want stored. Any native type of data should work fine.


kvJSON.getData(key):
    Used to store the value associated with a key in a variable.
    
    :key: The key associated with the value you want.


kvJSON.replaceData(key, newValue):
    USed to update data under a certain key.

    :key: The key related to the data you want to update.

    :newValue: The data you want to be updated under a key.


kvJSON.removeData(key):
    Used to delete the key specified and the data under it.

    :key: The key related with the data you want deleted.


kvJSON.encryptData(key):
    **DISCLAIMER: The encryption used is not completely secure and should not be used to store sensitive data.**
    Used to encrypt data.

    :key: The key related to the data you want encrypted.


kvJSON.getEncryptKey(number):
    *Make sure that the number you use is in quotes!*
    Used to retrieve an encryption key to decrypt data.
    
    :number: The number correlating with the data encrypted. Ex: 
    .. code:: py
        kvJSON.encryptData("key")
        # Get encryption key for first and only data encrypted.
        encryptKey = kvJSON.getEncryptKey("1")


kvJSON.decryptData(keyInData, encryptionKey):
    Used to decrypt data in storage, but can also be used to decrypt data and store it in a variable.
    
    :keyInData: The key related to the encrypted data.
    :encryptionKey: The encryption key related to the encrypted data.
