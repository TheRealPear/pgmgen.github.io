<div class="card mb-3">
  <div class="card-header">Kit</div>
  <div class="card-body">
    <div class="input-group mb-3">
      <div class="form-floating flex-grow-1">
          <input type="text" class="form-control rounded-0 rounded-start" name="kitID" placeholder=" ">
          <label for="kitID">Kit ID</label>
      </div>
      <div class="form-floating flex-grow-1">
        <input type="text" class="form-control rounded-0 rounded-end" name="kitParents" placeholder=" ">
        <label for="kitParents">Kit Parents</label>
      </div>
    </div>
    <div class="form-floating mb-3">
      <input type="text" class="form-control" id="kitFilter" placeholder=" ">
      <label for="kitFilter">Filter</label>
    </div>
    <div class="form-floating mb-3">
      <select class="form-select" id="kitForce">
          <option value="0" selected>-</option>
          <option value="1">True</option>
          <option value="2">False</option>
        </select>
        <label for="kitForce">Force Kit</label>
    </div>
    <div class="text-start mb-3">
      <div class="form-check form-check-inline" title="Enable or disable potion particles.">
        <input class="form-check-input" type="checkbox" id="kitPotionParticles" value="option1">
        <label class="form-check-label" for="kitPotionParticles">Show potion particles</label>
      </div>
      <div class="form-check form-check-inline" title="Reset any ender pearls a player may have thrown before the kit application.">
        <input class="form-check-input" type="checkbox" id="inlineCheckbox2" value="option2">
        <label class="form-check-label" for="inlineCheckbox2">Reset ender pearls</label>
      </div>
    </div>
    <div class="card mb-3">
      <div class="card-header">Item</div>
      <div class="card-body">
        <div class="text-end">
          <div class="input-group mb-3">
            <div class="form-floating flex-grow-1 w-25">
              <input type="text" class="form-control rounded-0 rounded-start" name="itemSlot" placeholder=" ">
              <label for="itemSlot">Slot</label>
            </div>
            <div class="form-floating flex-grow-1 w-25">
              <input type="number" class="form-control rounded-0" name="itemCount" placeholder=" ">
              <label for="itemCount">Count</label>
            </div>
            <div class="form-floating flex-grow-1">
              <input type="text" class="form-control rounded-0 rounded-end" name="itemType" placeholder=" ">
              <label for="itemType">Item</label>
            </div>
            <div class="input-group-text">
              <input class="form-check-input mt-0" type="checkbox" id="itemUnbreakable" value="" aria-label="Plural">
              <label class="form-check-label ms-2" for="itemUnbreakable">Unbreakable</label>
            </div>
          </div>
          <div class="btn-group btn-group-sm" role="group" aria-label="Item control">
            <button type="button" class="btn btn-success"><i class="bi bi-plus-lg"></i> New Item</button>
            <button type="button" class="btn btn-danger"><i class="bi bi-dash-lg"></i> Delete Item</button>
          </div>
        </div>
      </div>
    </div>
    <hr class="my-3">
    <div class="text-end">
      <div class="btn-group btn-group-sm" role="group" aria-label="Kits control">
        <button type="button" class="btn btn-success"><i class="bi bi-plus-lg"></i> New Kit</button>
        <button type="button" class="btn btn-danger"><i class="bi bi-dash-lg"></i> Delete Kit</button>
      </div>
    </div>
  </div>
</div>