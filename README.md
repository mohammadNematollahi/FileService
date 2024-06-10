# FileService

Upload the file to the Public folder 👇

FileBuilder::setFile(file)->setExclusiveDirectory(filePath)->upload();

Upload the file to the Storage folder 👇

FileBuilder::setFile(file)->setExclusiveDirectory(filePath)->upload(true);

The upload method takes an input value that specifies whether to be placed in storageThis method has the default value false that stores the value in the public folder

false => public 

true => storage/public

You can call the methods in a row in the same way

good luck ... ✔
