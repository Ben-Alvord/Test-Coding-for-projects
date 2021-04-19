<button type="button" class="btn btn-primary">Primary</button>

<form>
    <div class="form-group row">
      <label for="inputName3" class="col-sm-2 col-form-label">Name</label>
      <div class="col-sm-10">
        <input type="name" class="form-control" id="inputName3">
      </div>
    </div>
  
 <div class="form-group row">
      <label for="inputDescription3" class="col-sm-2 col-form-label">Description</label>
      <div class="col-sm-10">
        <input type="description" class="form-control" id="inputDescription3">
      </div>
    </div>
   
 <div class="form-group row">
      <label for="inputAssigned-To3" class="col-sm-2 col-form-label">Assigned To</label>
      <div class="col-sm-10">
        <input type="Assigned" class="form-control" id="inputAssigned-To3">
      </div>
    </div>
   
   <fieldset class="form-group">
      <div class="row">
        <legend class="col-form-label col-sm-2 pt-0">Description</legend>
        <div class="col-sm-10">
          <div class="form-check">
            <input class="form-check-input" type="description" name="gridDescription" id="gridDescription1" value="option1" checked>
            <label class="form-check-label" for="gridDescription1">
              First radio
            </label>
          </div>
          <div class="form-check">
            <input class="form-check-input" type="radio" name="gridRadios" id="gridRadios2" value="option2">
            <label class="form-check-label" for="gridRadios2">
              Second radio
            </label>
          </div>
          <div class="form-check disabled">
            <input class="form-check-input" type="radio" name="gridRadios" id="gridRadios3" value="option3" disabled>
            <label class="form-check-label" for="gridRadios3">
              Third disabled radio
            </label>
          </div>
        </div>
      </div>
    </fieldset>
    <div class="form-group row">
      <div class="col-sm-2">Checkbox</div>
      <div class="col-sm-10">
        <div class="form-check">
          <input class="form-check-input" type="checkbox" id="gridCheck1">
          <label class="form-check-label" for="gridCheck1">
            Example checkbox
          </label>
        </div>
      </div>
    </div>
    <div class="form-group row">
      <div class="col-sm-10">
        <button type="task" class="btn btn-primary">Add Task</button>
      </div>
    </div>
  </form>

  <div class="card" style="width: 18rem;">
    <img src="..." class="card-img-top" alt="...">
    <div class="card-body">
      <h5 class="task">Task</h5>
      <p class="card-text">Here is your task.</p>
    </div>
    <ol class="list-group list-group-flush">
      <li class="inputName3"></li>
      <li class="inputDescription3"></li>
      <li class="inputAssigned-To3"></li>
      <li class="list-group-item"></li>
      <li class="list-group-item"></li>
    </ol>
    <div class="card-body">
      <a href="#" class="card-link">Card link</a>
      <a href="#" class="card-link">Another link</a>
    </div>
  </div>
