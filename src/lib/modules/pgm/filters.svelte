<div class="card mb-3">
  <div class="card-header">Filter</div>
  <div class="card-body">
    <div class="form-floating mb-3">
      <select class="form-select" id="filterType">
        <optgroup label="Generic Filters">
          <option value="1">Pre-existing filter</option>
          <option value="2">Always</option>
          <option value="3">Never</option>
          <option value="4">Time</option>
          <option value="5">Objective</option>
          <option value="6">Flag-carried</option>
          <option value="7">Flag-dropped</option>
          <option value="8">Flag-returned</option>
          <option value="9">Flag-captured</option>
        </optgroup>
        <optgroup label="Spatial Filters">
          <option value="10">Void</option>
          <option value="11">(Original) Blocks</option>
        </optgroup>
        <optgroup label="Block Filters">
          <option value="12">Material</option>
          <option value="13">Structural Load</option>
        </optgroup>
        <optgroup label="Entity Filters">
          <option value="14">Spawn</option>
          <option value="15">Mob</option>
          <option value="16">Entity</option>
        </optgroup>
        <optgroup label="Competitor Filters">
          <option value="17">Carrying-flag</option>
          <option value="18">Score</option>
        </optgroup>
        <optgroup label="Player Filters">
          <option value="19">Participating</option>
          <option value="20">Team</option>
          <option value="21">Class</option>
          <option value="22">Kill-streak</option>
          <option value="23">Lives</option>
          <option value="24">Crouching</option>
          <option value="25">Walking</option>
          <option value="26">Sprinting</option>
          <option value="27">Grounded</option>
          <option value="28">Flying</option>
          <option value="29">Can-fly</option>
          <option value="30">Effect</option>
          <option value="31">Carrying</option>
          <option value="32">Holding</option>
          <option value="33">Wearing</option>
        </optgroup>
        <optgroup label="Event Filters">
          <option value="34">Cause</option>
          <option value="35">Random</option>
        </optgroup>
        <optgroup label="Damage Filters">
          <option value="36">Relation</option>
        </optgroup>
        </select>
        <label for="filterType">Filter Type</label>
    </div>
    <div class="form-floating mb-3">
      <input type="text" class="form-control" id="filterID" placeholder=" ">
      <label for="filterID">Filter ID</label>
    </div>
  </div>
</div>
<div class="text-end">
  <div class="btn-group btn-group-sm" role="group" aria-label="Filters control">
    <button type="button" class="btn btn-success"><i class="bi bi-plus-lg"></i> New Filter</button>
    <button type="button" class="btn btn-danger"><i class="bi bi-dash-lg"></i> Delete Filter</button>
  </div>
</div>