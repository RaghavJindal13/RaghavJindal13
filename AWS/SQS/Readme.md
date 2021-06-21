![image](https://user-images.githubusercontent.com/53964007/122661230-92584700-d1a5-11eb-9bfb-4186a1f27686.png)
![image](https://user-images.githubusercontent.com/53964007/122661239-b2880600-d1a5-11eb-96e8-989bfaca0f12.png)
![image](https://user-images.githubusercontent.com/53964007/122661257-ef53fd00-d1a5-11eb-9c28-8c566b179335.png)
![image](https://user-images.githubusercontent.com/53964007/122661268-ff6bdc80-d1a5-11eb-8157-ad7460f92c77.png)
![image](https://user-images.githubusercontent.com/53964007/122702266-a0bd6600-d26c-11eb-8dd2-fb8da4256364.png)


simple queue service provides a fully managed queue for storing messages as they travel between different applications or microservices. \
You can use Amazon SQS to transmit any volume of data, at any level of throughput, without
losing messages or requiring other services to be continuously available. \

![image](https://user-images.githubusercontent.com/53964007/122661449-0e538e80-d1a8-11eb-9225-c331b418272d.png)

An Amazon SQS queue is basically a buffer between the application components that receive
data and those components that process the data in your system. \

## Message Lifecycle
1. Component 1 sends Message A to a queue, and the message is redundantly distributed
across the Amazon SQS servers.
2. Now component 2 is notified that there is a message in the queue, now component 2 can pull the message a from the queue and now can start working on the task assigned to it at the same time the visibility timeout period starts.
3. Component who pulls the message from the queue, it can process the message and delete it from the queue.





## Important terms
<table>
  <tr>
    <th colspan=2>Basic Configuration definitions</th>
  </tr>
  <tr>
    <td><b>Producer</b></td>
    <td>The Component that is sending the message to the queue becomes the producer of the message.</td>
  </tr>
  <tr>
    <td><b>Consumer</b></td>
    <td>The Component that receives or processes the messaage becomes the consumer of the message.</td>
  </tr>
  <tr>
    <td><b>Visibility timeout period</b></td>
    <td><p>When a consumer receives and processes a message from the queue the message is not deleted and it remains in the queue,this is because there is no guarantee that the consumer has received the message,so only consumer must delete the message.</p>
    <p>So visibility timeout is a time period during which amazon sqs prvents other consumers from receiving and processing the same message. min-0,max-12hrs</p>
    </td>
  </tr>
</table>
