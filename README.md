<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>To Do List</title>
    <link rel="stylesheet" href="ToDo1.css">
</head>

<body>
    <main class="app">
        <section class="greeting">
            <h2 class="title">
                What's Up <input type="text" id="name" placeholder="Name Here">
            </h2>
        </section>

        <section class="create-todo">
            <h3>Create To Do</h3>

            <form id="new-todo-form">
                <h4>What's your todo List</h4>
                <input type="text" name="content" id="content" placeholder="my task 1">
                <h4>Pick a Category</h4>
                <div class="options">
                    <label>
                        <input type="radio" name="category" id="category1">
                        <span class="bubble business"></span>
                        <div>Business</div>
                    </label>
                    <label>
                        <input type="radio" name="category" id="category2">
                        <span class="bubble personal"></span>
                        <div>Personal</div>
                    </label>
                </div>

                <input type="submit" value="Add Task">
            </form>
        </section>

        <section class="todo-list">
            <h3>To Do List</h3>
            <div class="list" id="todo-list">
                <!-- <div class="todo-items done">
                    <label>
                        <input type="checkbox">
                        <span class="bubble business"></span>
                    </label>
                    <div class="todo-content">
                        <input type="text" value="my task 2" readonly>
                    </div>
                    <div class="actions">
                        <button class="edit">Edit</button>
                        <button class="delete">Delete</button>
                    </div>
                </div>
                <div class="todo-items done">
                    <label>
                        <input type="checkbox">
                        <span class="bubble personal"></span>
                    </label>
                    <div class="todo-content">
                        <input type="text" value="my task 3" readonly>
                    </div>
                    <div class="actions">
                        <button class="edit">Edit</button>
                        <button class="delete">Delete</button>
                    </div>
                </div> -->
            </div>
        </section>

    </main>

    <script src="TODO.js"></script>
</body>

</html>
