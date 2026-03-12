<head>
<title>To Do App</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<h1>My To Do App</h1>

<input type="text" id="taskInput">
<button onclick="addTask()">Add Task</button>

<ul id="taskList"></ul>

<script src="script.js"></script>

</body>
<!DOCTYPE html>
<html>
<head>
<title>To Do App</title>

<link rel="stylesheet" href="style.css">

</head>

<body>

<h1>My To Do App</h1>

<input type="text" id="taskInput" placeholder="Enter a task">

<button onclick="addTask()">Add Task</button>

<ul id="taskList"></ul>

<script src="script.js"></script>

</body>
</html>
body{
    font-family: Arial, sans-serif;
    background-color: #f2f2f2;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.container{
    background: white;
    padding: 20px;
    width: 350px;
    border-radius: 10px;
    box-shadow: 0px 0px 10px rgba(0,0,0,0.2);
    text-align: center;
}

h1{
    margin-bottom: 20px;
}

input{
    width: 70%;
    padding: 8px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

button{
    padding: 8px 12px;
    border: none;
    background-color: #28a745;
    color: white;
    border-radius: 5px;
    cursor: pointer;
}

button:hover{
    background-color: #218838;
}

ul{
    list-style: none;
    padding: 0;
    margin-top: 20px;
}

li{
    background: #eee;
    margin: 5px 0;
    padding: 8px;
    border-radius: 5px;
    display: flex;
    justify-content: space-between;
}

.delete{
    background: red;
    padding: 4px 8px;
    border-radius: 4px;
}
