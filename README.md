# Interview Questions
* [An Introduction to Exception Handling](https://developer.salesforce.com/page/An_Introduction_to_Exception_Handling)
* [Using Batch Apex](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_batch_interface.htm)
* [System.assert methods](https://developer.salesforce.com/forums/?id=906F00000008x42IAA)
* [Certificates and Keys](https://help.salesforce.com/articleView?id=security_keys_about.htm&type=5)

## Controllers
* Standard controller inherits all of the standard object properties and standard button functionality.  It contains the same functionality and logic that are used for standard Salesforce pages.
* Custom controller is an Apex class that implements all of the logic for a page without leveraging a standard controller.  Custom controllers are associated with Vfp throught the controller attribute.

## Collections
* List - an ordered collection of the primitive's data types dignified by an index.  You can have duplicates.
     * `List<DataType> listName = new List<DataType>0;`
* Set - an unordered collection of unique data of one primitive type or sObject that must have unique value. You CANNOT have duplicates.
     * `Set<DataType> setName = new Set<DataType>();` 
* Map - an unordered collection of unique keys of one primitive data type and their corresponding values.
    * `Map<PrimitiveKeyDataType, DataType> mapName = newMap<PrimitiveKeyDataType, DataType>();`
