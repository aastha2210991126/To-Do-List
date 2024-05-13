<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="todoList.css">
</head>
<body>
    <div class="container">
        <div class="todo-app">
            <div>
                <h2><div>To-Do List</div><img src="https://tse2.mm.bing.net/th?id=OIP.5o6Oa-Mo7a3lzAIfQ-6kOQHaHa&pid=Api&P=0&h=180"></h2>
                <div class="row">
                    <input type="text" id="input-box" placeholder="Add your task">
                    <button onclick="addTask()">Add</button>
                </div>
                <ul id="list-container">
                    
                </ul>
            </div>
        </div>
    </div>
    <script src="todoList.js"></script>
</body>
</html>
