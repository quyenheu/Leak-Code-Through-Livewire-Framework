This is a trick I discovered during the testing to leak source code via LiveWire (when Laravel has debugging enabled)
This trick works by exploiting conflicts between the input and the parameters the function receives (different data types, prohibited data, ...)
