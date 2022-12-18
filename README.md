# ROS Actions
## 1.1. Why ROS Actions?
### 1.1.1. ROS communication tools:

- Topics:

![topics](/image/topic.png)

- Services:

![services](/image/service.png)

- Execution time can be quite long, client is stuck waiting
    - How to cancel current execution?
    - How to get feedback from the server?
    - How to handle multiple commands?

    ![example](/image/example_1.png)

- Proble with services:
    - Synchronous 
    - Only made for quick actions and computations

### 1.1.2. What are ROS Actions?
![ros actions](/image/ros_action_topics.png)
- With ROS Actions you can：
  - Asynchronously execute goals
  - Get status and feedback on the current executed goal(s)
  - Cancel a goal
- In this course you will:
  - Start with simple action clients/server
    - Send a goal
    - Get feedback
    - Cancel a goal
  - Then go to the next level
    - Handle multiple goals
    - Create your own goal policy 
    - more..