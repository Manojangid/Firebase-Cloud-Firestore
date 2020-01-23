# Firebase-Cloud-Firestore
Cloud firestore is a flexible, scalable NoSQL cloud database to store and sync data for client- and server-side development.

Cloud Firestore is a flexible, scalable database for mobile, web, and server development from Firebase and Google Cloud Platform. Like Firebase Realtime Database, it keeps your data in sync across client apps through realtime listeners and offers offline support for mobile and web so you can build responsive apps that work regardless of network latency or Internet connectivity. Cloud Firestore also offers seamless integration with other Firebase and Google Cloud Platform products, including Cloud Functions.

Firestore in glance
1. Cloud Firestore stores data in Documents, which are stored in Collections. Cloud Firestore creates collections and documents              implicitly the first time you add data to the document. You do not need to explicitly create collections or documents. 
2. Documents in a collection can contain different sets of information.
3. Each document contains a set of key-value pairs. Cloud Firestore is optimized for storing large collections of small documents.
4. All documents must be stored in collections. Documents can contain subcollections and nested objects, both of which can include primitive fields like strings or complex objects like lists.
5. Cloud Firestore supports a variety of data types for values: boolean, number, string, geo point, binary blob, and timestamp. You can also use arrays or nested objects, called maps, to structure data within a document.
6. A collection contains documents and nothing else. It can't directly contain raw fields with values, and it can't contain other collections.
7. The names of documents within a collection are unique. You can provide your own keys, such as user IDs, or you can let Cloud Firestore create random IDs for you automatically.
8. You do not need to "create" or "delete" collections. After you create the first document in a collection, the collection exists. If you delete all of the documents in a collection, it no longer exists.
9. Collection references and document references are two distinct types of references and let you perform different operations. For example, you could use a collection reference for querying the documents in the collection, and you could use a document reference to read or write an individual document.
10. For convenience, you can also create references by specifying the path to a document or collection as a string, with path components separated by a forward slash (/). 
11. You can query across subcollections with the same collection ID by using Collection Group Queries.
12. Documents in subcollections can contain subcollections as well, allowing you to further nest data. You can nest data up to 100 levels deep.
13. When you delete a document that has subcollections, those subcollections are not deleted.
14. 
