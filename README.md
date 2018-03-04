download local dynamodb from:
https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/DynamoDBLocal.html
>extract > cmd
>chang dir to the dynamodb_local_latest
>use the following cmd to start the server:

java -Djava.library.path=./DynamoDBLocal_lib -jar DynamoDBLocal.jar -sharedDb -inMemory

continue with the code!
refer to best documentation
>>
https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/GettingStarted.Python.html