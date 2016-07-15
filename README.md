# Todo-App-Backend

This is the backend built for Todo App with Flask framework.

Our tasks resource will use HTTP methods as follows:

| HTTP Method   | URI                                                   |Action                   |
|:------------- |:------------------------------------------------------|:------------------------|
| GET           | http://[hostname]/todo/api/v1.0/tasks                 | Retrieve list of tasks  |
| GET           | http://[hostname]/todo/api/v1.0/tasks/[task_id]       | Retrieve a task         |
| POST          | http://[hostname]/todo/api/v1.0/tasks                 | Create a new task       |
| PUT           | http://[hostname]/todo/api/v1.0/tasks/[task_id]       | Update an existing task |
| DELETE        | http://[hostname]/todo/api/v1.0/tasks/[task_id]       | Delete a task           |


#### We can define a task as having the following fields:

id: unique identifier for tasks (Numeric type).<br>
title: short task description (String type).<br>
description: long task description (Text type).<br>
done: task completion state (Boolean type).<br>

