# ASYNCHRONOUS PROCESSING

<p align="center">
  <img src="https://github.com/iamabhishekmaurya/syetem-design/blob/ee4fef9001bda8f1aa527f5a4007e9c3fc6d2046/assets/async.png" alt="image"/>
</p>

Asynchronous processing is one of the most useful concepts when you are working on a large scalable project, then there are most of the use cases that you can solve very easily by using it. It is mostly useful when you are working on a distributed system.
It helps you to reduce the response time for an API or function.
> For example: If you are calling a function and in somewhere middle of the function it performs some IO operations and it will take a long time to complete so you have to wait for it to complete then it will start executing further operations. That will increase the response time. On the other hand, if you do not perform any further actions based on IO operations response then it was just west of time. 

If you call an API or a function and if it is not blocking or waiting for a thread to complete their entire processing to sent the response then it is known as asynchronous processing.
