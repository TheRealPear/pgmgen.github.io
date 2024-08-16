<div class="card mb-3">
  <div class="card-header">Objective</div>
  <div class="card-body">
    <div class="form-floating mb-3">
      <select class="form-select" id="objectiveType">
          <option value="0">-</option>
          <option value="1">Capture the Wool</option>
          <option value="2">Capture the Flag</option>
          <option value="3">Control Points</option>
          <option value="4">Destroy the Monument</option>
          <option value="5">Destroy the Core</option>
          <option value="6">Monument Modes</option>
          <option value="7">Blitz</option>
          <option value="8">Scoring (custom)</option>
          <option value="9">Payload (experimental)</option>
        </select>
        <label for="objectiveType">Objective Type</label>
    </div>
    <div class="form-floating mb-3">
      <input type="text" class="form-control" id="objectiveID" placeholder=" ">
      <label for="kitFilter">Objective ID</label>
    </div>
    <div class="form-floating mb-3">
      <input type="text" class="form-control" id="objectiveName" placeholder=" ">
      <label for="kitFilter">Objective Name</label>
    </div>
  </div>
</div>
<div class="text-end">
  <div class="btn-group btn-group-sm" role="group" aria-label="Objectives control">
    <button type="button" class="btn btn-success"><i class="bi bi-plus-lg"></i> New Objective</button>
    <button type="button" class="btn btn-danger"><i class="bi bi-dash-lg"></i> Delete Objective</button>
  </div>
</div>