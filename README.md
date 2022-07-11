# Lambda_Function
We have two lambda functions 
Invoker : calling another lambda function
ToInvoke : Lambda function to be called 
the invoker will call the ToInvoke function with a payload(In JSON ) . LambdaToInvoke function will read the value and give the desired response in this case transactionId ( corresponding to CustomerId and Amount) .
