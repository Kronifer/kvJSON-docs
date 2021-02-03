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


