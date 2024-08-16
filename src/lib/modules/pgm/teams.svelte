<div class="card mb-3">
  <div class="card-header">Teams</div>
  <div class="card-body">
    <div class="form-floating mb-3">
      <input type="text" class="form-control" id="teamID" placeholder=" ">
      <label for="teamID">Team ID</label>
    </div>
    <div class="input-group mb-3">
      <div class="form-floating flex-grow-1">
          <input type="text" class="form-control rounded-0 rounded-start" name="teamName" placeholder=" ">
          <label for="teamName">Team Name</label>
      </div>
      <div class="input-group-text" title="Display the team's name as plural, used in status messages.">
        <input class="form-check-input mt-0" type="checkbox" id="teamPlural" value="" aria-label="Plural">
        <label class="form-check-label ms-2" for="teamPlural">Plural?</label>
      </div>
    </div>
    <div class="form-floating mb-3" title="Specify who can see the name tags of players in this team.">
      <select class="form-select" id="teamNameTag">
          <option value="1" selected>-</option>
          <option value="2">True</option>
          <option value="3">False</option>
          <option value="4">Allies</option>
          <option value="5">Enemies</option>
        </select>
        <label for="teamNametag">Show nametags</label>
    </div>
    <div class="input-group mb-3" title="The team's display color.">
      <div class="form-floating flex-grow-1">
        <select class="form-select rounded-0 rounded-start" id="teamColor">
          <option value="1">Black</option>
          <option value="2">Dark Blue</option>
          <option value="3">Dark Green</option>
          <option value="4">Dark Aqua</option>
          <option value="5">Dark Red</option>
          <option value="6">Dark Purple</option>
          <option value="7">Gold</option>
          <option value="8">Gray</option>
          <option value="9">Dark Gray</option>
          <option value="10">Blue</option>
          <option value="11">Green</option>
          <option value="12">Aqua</option>
          <option value="13">Red</option>
          <option value="14">Light Purple</option>
          <option value="15">Yellow</option>
          <option value="16">White</option>
        </select>
        <label for="teamColor">Team Color</label>
      </div>
      <div class="form-floating flex-grow-1">
        <select class="form-select rounded-0 rounded-end" id="teamColor">
          <option value="0" selected>-</option>
          <option value="1">Black</option>
          <option value="2">Dark Blue</option>
          <option value="3">Dark Green</option>
          <option value="4">Dark Aqua</option>
          <option value="5">Dark Red</option>
          <option value="6">Dark Purple</option>
          <option value="7">Gold</option>
          <option value="8">Gray</option>
          <option value="9">Dark Gray</option>
          <option value="10">Blue</option>
          <option value="11">Green</option>
          <option value="12">Aqua</option>
          <option value="13">Red</option>
          <option value="14">Light Purple</option>
          <option value="15">Yellow</option>
          <option value="16">White</option>
        </select>
        <label for="teamColor">Team Overhead Color</label>
      </div>
    </div>
    <div class="input-group mb-3" title="Required amount of players for this team.">
      <div class="form-floating flex-grow-1">
        <input type="number" class="form-control rounded-0 rounded-start" id="teamMinSize" placeholder="1">
        <label for="teamMinSize">Minimum Size</label>
      </div>
      <div class="form-floating flex-grow-1" title="Maximum players for this team, normal players cannot join the team once it reaches this size.">
        <input type="number" class="form-control rounded-0" id="teamMaxSize" placeholder=" ">
        <label for="teamMaxSize">Maximum Size</label>
      </div>
      <div class="form-floating flex-grow-1" title="Maximum players hard limit for this team, nobody can join the team once this limit is reached.">
        <input type="number" class="form-control" id="teamMaxOverfill" placeholder=" ">
        <label for="teamMaxOverfill">Maximum Overfill</label>
      </div>
    </div>
    <hr class="my-3">
    <div class="text-end">
      <div class="btn-group btn-group-sm" role="group" aria-label="Teams control">
        <button type="button" class="btn btn-success"><i class="bi bi-plus-lg"></i> New Team</button>
        <button type="button" class="btn btn-danger"><i class="bi bi-dash-lg"></i> Delete Team</button>
      </div>
    </div>
  </div>
</div>