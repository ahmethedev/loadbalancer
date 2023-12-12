# Load Balancer with GO

I built a TCP load balancer with proxy for localhost. I used Go for this project.
You can reach the source from [here](https://www.youtube.com/watch?v=QTBZxDgRZM0&list=PLe1QWkyzVMv4y-sUq_z9wsrxqSH6Ka3Z5&index=7&ab_channel=ahmetalpbalkan).


How to test:

1. Download the code.
2. Create localhost http server on new terminal window. You can use npx for this. (ex: npx http-server -p 5001)
3. Run the Go code on new terminal window: (go run . )
4. Send request to server which is we are listening to: localhost:8080 (curl localhost:8080)
5. You can see the request on the http server we created on terminal (5001).
