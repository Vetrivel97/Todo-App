# Todo-App
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CRUD Application Using JavaScript</title>
    <link rel="stylesheet" href="todo.css">

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css" />

</head>

<body>
    <div class="App">
        <h4>CRUD Application</h4>
        <div id="addNew" data-bs-toggle="modal" data-bs-target="#form">
            <span>Enter...</span>
            <button id="btn-add">Add</button>
        </div>
            <!--Task Section-->
            <div class="ad-task">
            <h5>Added Tasks</h5>
            <div id="tasks"></div>

    </div>

    <form id="form" class="modal fade" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
            <h5 class="model-title" id="exampleModalLabel">Add New Tasks</h5>
            <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="close"></button>
        </div>
        <div class="modal-body">
<p>Task Title</p>
<input type="text" class="form-control" name="" id="textInput"/>
<div id="message"></div>
<br/>
<p>Due Date</p>
<input type="date" class="form-control" name="" id="dateInput"/>
<br/>
<p>Description</p>
<textarea name="des" id="textarea" cols="30" rows="10" class="form-control"></textarea>
        </div>
        <div class="modal-footer">
            <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
            <button type="submit" id="add" class="btn btn-primary">Add</button>
        </div>
    </div>
</div>
    </form>

</body>
<script src="todo.js"></script>
</html> 
