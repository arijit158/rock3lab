# rock3lab

CREATE :

http://localhost:3000/task/create

payload :
"task" : "task5",
  "priority":"3",
  "duedate":"20/03/2017"
}
Method : POST

SHOW ALL : 

http://localhost:3000/task
Method : GET

UPDATE

http://localhost:3000/task/update

{"_id": "59d5b259bc493c533c000001",
        "task": "task5",
        "priority": "2",
        "duedate": "30/03/2017"}
		
DELETE : 

http://localhost:3000/task/destroy/task2
METHOD : POST

