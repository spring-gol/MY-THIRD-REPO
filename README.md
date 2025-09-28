<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>To-Do List</title>
  <style>
    body { font-family: Arial, sans-serif; background:#f4f4f4; padding:20px; }
    h1 { text-align:center; }
    #taskInput { padding:10px; width:70%; }
    #addBtn { padding:10px; }
    ul { list-style:none; padding:0; }
    li { padding:10px; background:#fff; margin:5px 0; display:flex; justify-content:space-between; }
    button { background:red; color:#fff; border:none; padding:5px 10px; cursor:pointer; }
  </style>
</head>
<body>
  <h1>To-Do List</h1>
  <input id="taskInput" type="text" placeholder="Enter tas...">
  <button id="addBtn">Add</button>
  <ul id="taskList"></ul>
  <script src="script.js"></script>
</body>
</html>
