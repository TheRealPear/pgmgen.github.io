<div class="card mb-3">
  <div class="card-header">Region</div>
  <div class="card-body">
    <div class="form-floating mb-3">
      <select class="form-select" id="regionType">
        <optgroup label="Block-Bounded Regions">
          <option value="1">Cuboid</option>
          <option value="2">Cylinder</option>
          <option value="3">Block</option>
          <option value="4">Sphere</option>
          <option value="5">Point</option>
        </optgroup>
        <optgroup label="Unbounded Regions">
          <option value="6">Rectangle</option>
          <option value="7">Circle</option>
          <option value="8">Half</option>
          <option value="9">Below/Above</option>
        </optgroup>
        </select>
        <label for="regionType">Region Type</label>
    </div>
    <div class="form-floating mb-3">
      <input type="text" class="form-control" id="regionID" placeholder=" ">
      <label for="regionID">Region ID</label>
    </div>
  </div>
</div>
<div class="text-end">
  <div class="btn-group btn-group-sm" role="group" aria-label="Regions control">
    <button type="button" class="btn btn-success"><i class="bi bi-plus-lg"></i> New Region</button>
    <button type="button" class="btn btn-danger"><i class="bi bi-dash-lg"></i> Delete Region</button>
  </div>
</div>