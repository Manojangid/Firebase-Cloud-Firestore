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
7. 
