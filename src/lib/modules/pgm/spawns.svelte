<div class="card mb-3">
  <div class="card-header">Spawn</div>
  <div class="card-body">
    <div class="form-floating mb-3">
      <select class="form-select" id="spawnType">
          <option value="1">Team/Individual spawn</option>
          <option value="2">Default spawn (limit: 1)</option>
        </select>
        <label for="spawnType">Spawn Type</label>
    </div>
    <div class="form-floating mb-3">
      <input type="text" class="form-control" id="spawnTeam" placeholder=" ">
      <label for="spawnTeam">Spawn Team</label>
    </div>
    <div class="form-floating mb-3">
      <input type="text" class="form-control" id="spawnFilter" placeholder=" ">
      <label for="spawnFilter">Spawn Filter</label>
    </div>
    <div class="form-floating mb-3">
      <input type="text" class="form-control" id="spawnKit" placeholder=" ">
      <label for="spawnKit">Spawn Kit</label>
    </div>
    <div class="card mb-3">
      <div class="card-header">Spawn Properties</div>
      <div class="card-body">
        <div class="form-check form-check-inline" title="Validate that the player spawns in a safe location.">
          <input class="form-check-input" type="checkbox" value="" id="isSpawnSafe">
          <label class="form-check-label" for="isSpawnSafe">Safe</label>
        </div>
        <div class="form-check form-check-inline" title="Spawns players at the next region in a list if the one prior to it isn't safe (requires Safe to be enabled).">
          <input class="form-check-input" type="checkbox" value="" id="isSpawnSequential">
          <label class="form-check-label" for="isSpawnSequential">Sequential</label>
        </div>
        <div class="form-check form-check-inline" title="Spawn players as far away as possible from enemy players.">
          <input class="form-check-input" type="checkbox" value="" id="isSpawnSpread">
          <label class="form-check-label" for="isSpawnSpread">Spread</label>
        </div>
        <div class="form-check form-check-inline" title="Spawn regions are assigned exclusively to one player/team and only spawn there.">
          <input class="form-check-input" type="checkbox" value="" id="isSpawnExclusive">
          <label class="form-check-label" for="isSpawnExclusive">Exclusive</label>
        </div>
        <div class="form-check form-check-inline" title="Once a player has been assigned a spawn, they will spawn there even if they leave and rejoin.">
          <input class="form-check-input" type="checkbox" value="" id="isSpawnPersistent">
          <label class="form-check-label" for="isSpawnPersistent">Persistent</label>
        </div>
      </div>
    </div>
    <hr class="my-3">
    <div class="text-end">
      <div class="btn-group btn-group-sm" role="group" aria-label="Spawns control">
        <button type="button" class="btn btn-success"><i class="bi bi-plus-lg"></i> New Spawn</button>
        <button type="button" class="btn btn-danger"><i class="bi bi-dash-lg"></i> Delete Spawn</button>
      </div>
    </div>
  </div>
</div>
<div class="card mb-3">
  <div class="card-header">Respawn Module</div>
  <div class="card-body">
    <div class="form-floating mb-3" title="Delay a player's respawn for this duration.">
      <input type="text" class="form-control" id="respawnDelay" placeholder=" ">
      <label for="respawnDelay">Delay Time</label>
    </div>
    <div class="form-floating mb-3" title="Filters when this respawn rule is used.">
      <input type="text" class="form-control" id="respawnFilter" placeholder=" ">
      <label for="respawnFilter">Respawn Filter</label>
    </div>
    <div class="form-floating mb-3" title="Message to display on the respawn screen to respawning players.">
      <input type="text" class="form-control" id="respawnMessage" placeholder=" ">
      <label for="respawnMessage">Respawn Message</label>
    </div>
    <div class="card mb-3">
      <div class="card-header">Respawn Attributes</div>
      <div class="card-body">
        <div class="form-check form-check-inline" title="Auto respawn the player after the delay time has elapsed.">
          <input class="form-check-input" type="checkbox" value="" id="isRespawnAuto">
          <label class="form-check-label" for="isRespawnAuto">Auto</label>
        </div>
        <div class="form-check form-check-inline" title="Dead players get a blindness effect applied.">
          <input class="form-check-input" type="checkbox" value="" id="isRespawnBlackout">
          <label class="form-check-label" for="isRespawnBlackout">Blackout</label>
        </div>
        <div class="form-check form-check-inline" title="Allow dead players to fly around.">
          <input class="form-check-input" type="checkbox" value="" id="isRespawnSpectate">
          <label class="form-check-label" for="isRespawnSpectate">Spectate</label>
        </div>
        <div class="form-check form-check-inline" title="Allow players to respawn from beds.">
          <input class="form-check-input" type="checkbox" value="" id="isRespawnInBed" aria-disabled="true" disabled>
          <label class="form-check-label" for="isRespawnInBed">Beds</label>
        </div>
      </div>
    </div>
    <hr class="my-3">
    <div class="text-end">
      <div class="btn-group btn-group-sm" role="group" aria-label="Respawns control">
        <button type="button" class="btn btn-success"><i class="bi bi-plus-lg"></i> New Respawn</button>
        <button type="button" class="btn btn-danger"><i class="bi bi-dash-lg"></i> Delete Respawn</button>
      </div>
    </div>
  </div>
</div>