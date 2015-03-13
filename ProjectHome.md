This class validates lots of different inputs.  Useful for validating web forms, among other things.  I was inspired to make an omnibus validater, instead of one that does only the major input types, such as http://pear.php.net/package/Validate/ (of course, I use that project as a starting point).  Other sources of types come from MySQL field types.  One purpose of this class is to be able to validate all writes to a MySQL database, which is why I include every MySQL data type.  This allows a writer of a DBAL to use this class as a input-mask for their webapp.