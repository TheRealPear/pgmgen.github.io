<div class="card mb-3">
  <div class="card-header">Action</div>
  <div class="card-body">
    <div class="form-floating mb-3">
      <input type="text" class="form-control" id="actionID" placeholder=" ">
      <label for="actionID">Action ID</label>
    </div>
    <div class="form-floating mb-3">
      <select class="form-select" id="actionScopeType">
          <option value="1">Player</option>
          <option value="2">Team</option>
          <option value="3">Match</option>
        </select>
        <label for="actionScopeType">Action Scope</label>
    </div>
    <div class="form-floating mb-3">
      <input type="text" class="form-control" id="actionFilter" placeholder=" ">
      <label for="actionFilter">Filter</label>
    </div>
  </div>
</div>
<div class="text-end">
  <div class="btn-group btn-group-sm" role="group" aria-label="Actions control">
    <button type="button" class="btn btn-success"><i class="bi bi-plus-lg"></i> New Action</button>
    <button type="button" class="btn btn-danger"><i class="bi bi-dash-lg"></i> Delete Action</button>
  </div>
</div>