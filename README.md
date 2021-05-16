<!DOCTYPE html lang=’en’>

<div>
  <h2>Add new Tasks</h2>
</div>

<div>
 <div>
  <form>
   <div class="row">
    <div class="col">
      <input type="text" class="form-control" id = "firstName1" placeholder="First name">
    </div>
    <div class="col">
      <input type="text" class="form-control" id = "lastName1" placeholder="Last name">
    </div>
   </div>
  </form>
 </div>


 <form>
  <div class="row">
    <div class="col">
      <input type="text" class="form-control" id = "Task1" placeholder="1st Task">
    </div>
    <div class="col">
      <input type="text" class="form-control" id = "Task2" placeholder="2nd Task">
    </div>
  </div>
 </form>

 <form>
  <div class="row">
    <div class="col">
      <input type="text" class="form-control" id = "Task3" placeholder="3rd Task">
    </div>
    <div class="col">
      <input type="text" class="form-control" id = "Task4" placeholder="4th Task">
    </div>
  </div>
 </form>

 <form>
  <div class="row">
    <div class="col">
      <input type="text" class="form-control" id = "Task5" placeholder="5th Task">
    </div>
    <div class="col">
      <input type="text" class="form-control" id = "Task6" placeholder="6th Task">
    </div>
  </div>
 </form>

 <form>
  <div class="row">
    <div class="col">
      <input type="text" class="form-control" id = "Task7" placeholder="7thTask">
    </div>
    <div class="col">
      <input type="text" class="form-control" id = "Task8" placeholder="8th Task">
    </div>
  </div>
 </form>

 <div class="form-group">
  <label for="selectNameBelow1">Assigned To: </label>
  <select class="form-control" id="selectNameBelow1">
    <option>Select Names Below</option>
    <option>Ben Alvord</option>
    <option>Johnny Tyson</option>
    <option>Lalita Chauhan</option>
  </select>
 </div>

 <div>
  <button type="submit" class="btn btn-primary" id = "addTaskButton1">Add Task(s)</button>
</div>

<div>
  <h2>Tasks to accomplish</h2>
</div>

<div class="list-group">
  <a href="#" class="list-group-item list-group-item-action">
    <div class="d-flex w-100 justify-content-between" id = "taskCard1">
      <h5 class="mb-1">Assigned To</h5>
      <small class="text-muted">Assigned</small>
       <ul class="list-group">
        <li class="list-group-item">First Task</li>
        <li class="list-group-item">Second Task</li>
        <li class="list-group-item">Third Task</li>
        <li class="list-group-item">Fourth Task</li>
        <li class="list-group-item">Fifth task</li>
        <li class="list-group-item">Sixth Task</li>
        <li class="list-group-item">Seventh Task</li>
        <li class="list-group-item">Eight task</li> 
       </ul>
    <small class="text-muted" id = "assigned1">Assigned by</small>
  </a> 
  <div>
    <button type="submit" class="btn btn-primary" id = "doneButton1">Done</button><button type="submit" class="btn btn-primary" id = "deleteTaskButton1">Delete</button>
  </div>
  <a href="#" class="list-group-item list-group-item-action">
    <div class="d-flex w-100 justify-content-between" id = "taskCard2">
      <h5 class="mb-1">Assigned To</h5>
      <small class="text-muted">Assigned</small>
       <ul class="list-group">
        <li class="list-group-item">First Task</li>
        <li class="list-group-item">Second Task</li>
        <li class="list-group-item">Third Task</li>
        <li class="list-group-item">Fourth Task</li>
        <li class="list-group-item">Fifth task</li>
        <li class="list-group-item">Sixth Task</li>
        <li class="list-group-item">Seventh Task</li>
        <li class="list-group-item">Eight task</li> 
       </ul>
    <small class="text-muted" id = "assigned2">Assigned by</small>
  </a> 
  <div>
    <button type="submit" class="btn btn-primary" id = "doneButton2">Done</button><button type="submit" class="btn btn-primary" id = "deleteTaskButton2">Delete</button>
  </div>
  <a href="#" class="list-group-item list-group-item-action">
    <div class="d-flex w-100 justify-content-between" id = "taskCard3">
      <h5 class="mb-1">Assigned To</h5>
      <small class="text-muted">Assigned</small>
       <ul class="list-group">
        <li class="list-group-item">First Task</li>
        <li class="list-group-item">Second Task</li>
        <li class="list-group-item">Third Task</li>
        <li class="list-group-item">Fourth Task</li>
        <li class="list-group-item">Fifth task</li>
        <li class="list-group-item">Sixth Task</li>
        <li class="list-group-item">Seventh Task</li>
        <li class="list-group-item">Eight task</li> 
       </ul>
    <small class="text-muted" id = "assigned3">Assigned by</small>
  </a>  
  <div>
    <button type="submit" class="btn btn-primary" id = "doneButton3">Done</button><button type="submit" class="btn btn-primary" id = "deleteTaskButton3">Delete</button>
  </div>
  <a href="#" class="list-group-item list-group-item-action">
    <div class="d-flex w-100 justify-content-between" id = "taskCard4">
      <h5 class="mb-1">Assigned To</h5>
      <small class="text-muted">Assigned</small>
       <ul class="list-group">
        <li class="list-group-item">First Task</li>
        <li class="list-group-item">Second Task</li>
        <li class="list-group-item">Third Task</li>
        <li class="list-group-item">Fourth Task</li>
        <li class="list-group-item">Fifth task</li>
        <li class="list-group-item">Sixth Task</li>
        <li class="list-group-item">Seventh Task</li>
        <li class="list-group-item">Eight task</li> 
       </ul>
    <small class="text-muted" id = "assigned4">Assigned by</small>
  </a>  
  <div>
    <button type="submit" class="btn btn-primary" id = "doneButton4">Done</button><button type="submit" class="btn btn-primary" id = "deleteTaskButton4">Delete</button>
  </div>
  <a href="#" class="list-group-item list-group-item-action">
    <div class="d-flex w-100 justify-content-between" id = "taskCard5">
      <h5 class="mb-1">Assigned To</h5>
      <small class="text-muted">Assigned</small>
       <ul class="list-group">
        <li class="list-group-item">First Task</li>
        <li class="list-group-item">Second Task</li>
        <li class="list-group-item">Third Task</li>
        <li class="list-group-item">Fourth Task</li>
        <li class="list-group-item">Fifth task</li>
        <li class="list-group-item">Sixth Task</li>
        <li class="list-group-item">Seventh Task</li>
        <li class="list-group-item">Eight task</li> 
       </ul>
    <small class="text-muted" id = "assigned5">Assigned by</small>
  </a>  
  <div>
    <button type="submit" class="btn btn-primary" id = "doneButton5">Done</button><button type="submit" class="btn btn-primary" id = "deleteTaskButton5">Delete</button>
  </div>
</div>
