# BE Assessment II

## Answer the following questions

1.  (multiple choice) ORM...

    - [ ] stands for Object-Relational-Mapper
    - [ ] is the technique of accessing a relational database using an object-oriented programming language
    - [ ] focus more on business logic and less on writing interfaces
    - [ ] All of the above

2.  (T/F) An ORM maps between an Object Model and a Relational Database. An ODM maps between an Object Model and a Document Database.

    - [ ] True
    - [ ] False

3.  (fill in your answer) How can you install Mongoose in your application

    - 

4.  (multiple answer) Which of the following sentences are correct?

    - [ ] ‘Collections’ in Mongo are equivalent to tables in relational databases.
    - [ ] ‘Schema’ in Mongo is defined via a table definition
    - [ ] ‘Documents’ are equivalent to records or rows of data in SQL.
    - [ ] ‘Models’ are higher-order constructors that take a schema and create an instance of a document equivalent to records in a relational database.

5.  (T/F) A Mongoose schema defines the structure of the document, default values, validators, etc.

    - [ ] True
    - [ ] False

6.  (multiple answer) Which of the following Schema Types are permitted?

    - [ ] Array
    - [ ] Boolean
    - [ ] Buffer
    - [ ] Object
    - [ ] Mixed
    - [ ] ObjectId

7.  (T/F) Should I create/destroy a new connection for each database operation?

    - [ ] No. Open your connection when your application starts up and leave it open until the application shuts down.
    - [ ] Yes. The connection is automatically closed by the application when the operation is completed.

8.  (multiple answer) A mongoose Schema describes the attributes of the properties of a Mongoose Model. These attributes can include:

    - [ ] if the value is required
    - [ ] the data type
    - [ ] if the value is unique

9.  (T/F) An ObjectId is a special type typically used for unique identifiers.

    - [ ] True
    - [ ] False

10.  (T/F) An ObjectId is typically represented using a 24 hexadecimal character string, like '5e4bad2a0ab24550afceed7a'. 
    
    - [ ] True
    - [ ] False

11.  (multiple answer) Which of the following statements are correct Population?
    
    - [ ] it is the process of automatically replacing the specified paths in the document with document(s) from other collection(s).
    - [ ] We may populate a single document, multiple documents, a plain object, multiple plain objects, or all objects returned from a query
    - [ ] it is required in every application for at least one document
    - [ ] All of the above

12.  (T/F) With Mongoose, you can prevent duplicates in your databases using validation. Validation is defined in the SchemaType and is a middleware. You can also create your own validation in the schema or you can use Mongooses's built in validation.
    
    - [ ] True
    - [ ] False

13.  (multiple choice) You can connect to a MongoDB local instance using
    
    - [ ] mongoose.connect('https://localhost:27017/myapp', {useNewUrlParser: true});
    - [ ] mongoose.connect('ssh://localhost:27017/myapp', {useNewUrlParser: true});
    - [ ] mongoose.connect('mongodb://localhost:27017/myapp', {useNewUrlParser: true});
    - [ ] mongoose.connect('mongoose://localhost:27017/myapp', {useNewUrlParser: true});

14.  (multiple choice) The timestamps option tells mongoose to assign 'createdAt' and 'updatedAt' fields to your schema.
    
    - [ ] True
    - [ ] False

15.  (T/F) The bcrypt hashing function allows us to build a password security platform that scales with computation power and always hashes every password with a salt. It can only be used with Javascript.
    
    - [ ] True
    - [ ] False

16.  (multiple choice) JSON Web Tokens can be used to
    
    - [ ] generate, decode and store a token
    - [ ] decode, verify and generate a token
    - [ ] generate, verify and upload a token
    - [ ] None of the above

17.  (multiple answer) Which of these, if any, are parts of a JWT?
    
    - [ ] Header
    - [ ] Payload
    - [ ] Signature
    - [ ] Hash

18.  (T/F) Multipart requests combine one or more sets of data into a single body, separated by boundaries. You typically use these requests for file uploads and for transferring data of several types in a single request (for example, a file along with a JSON object).
    
    - [ ] True
    - [ ] False

19.  (T/F) CSRF stands for Cross-Site Response Forgery
    
    - [ ] True
    - [ ] False

20.  (T/F) An HTTP cookie is a small piece of data stored on the user's computer by the web browser. Cookies were designed to be a reliable mechanism for websites to remember stateful information or to record the user's browsing activity.
    
    - [ ] True
    - [ ] False
