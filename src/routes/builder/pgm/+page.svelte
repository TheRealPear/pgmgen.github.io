<script>
  import '$lib/css/override.css';
  import MainMapElement from '$lib/modules/pgm/main.svelte';
  import AuthorsContributors from '$lib/modules/pgm/authors.svelte';
  import Teams from '$lib/modules/pgm/teams.svelte';
  import Objectives from '$lib/modules/pgm/objectives.svelte';
  import Kits from '$lib/modules/pgm/kits.svelte';
  import Filters from '$lib/modules/pgm/filters.svelte';
  import Regions from '$lib/modules/pgm/regions.svelte';
  import ActionsTrigger from '$lib/modules/pgm/actions-trigger.svelte';
  import Variables from '$lib/modules/pgm/variables.svelte';
  import Spawns from '$lib/modules/pgm/spawns.svelte';
  import Shop from '$lib/modules/pgm/shop.svelte';
</script>
<svelte:head>
  <title>XML</title>
</svelte:head>
<!-- Jumbotron -->
<div class="text-white bg-dark bg-gradient p-4 rounded-3 m-3">
  <h1 class="display-6">PGM XML Generator</h1>
  <p class="lead">A simple website to assist in formatting XML files for PvP Game Manager (PGM) maps.</p>
</div>
<hr class="my-4 m-4">
<!-- Main container divided into 2 small column and 1 large column -->
<div class="container"> <!-- mb-3 -->
  <div class="row">
    <!-- Left column -->
    <div class="col-sm-auto">
      <p class="h5">PGM Modules</p>
      <hr class="my-3">
      <div class="card bg-body-tertiary">
          <div class="card-body">
            The latest map proto is <code>1.4.2</code>.
          </div>
      </div>
      <hr class="my-3">
      <div class="nav flex-column nav-pills" id="sidebar-tab" role="tablist" aria-orientation="vertical">
        <p class="h6 fw-semibold">General</p>
        <button class="nav-link text-start active" id="main-map-tab" data-bs-toggle="pill" data-bs-target="#main-map-elements" type="button" role="tab" aria-controls="main-map-elements" aria-selected="true">Main Map Elements</button>
        <button class="nav-link text-start" id="authors-contributors-tab" data-bs-toggle="pill" data-bs-target="#authors-contributors" type="button" role="tab" aria-controls="authors-contributors" aria-selected="false">Authors &amp; Contributors</button>
        <p class="h6 fw-semibold">Format</p>
        <button class="nav-link text-start" id="teams-players-tab" data-bs-toggle="pill" data-bs-target="#teams-players" type="button" role="tab" aria-controls="teams-players" aria-selected="false">Teams/Players</button>
        <button class="nav-link text-start" id="objectives-tab" data-bs-toggle="pill" data-bs-target="#objectives" type="button" role="tab" aria-controls="objectives" aria-selected="false">Objectives</button>
        <p class="h6 fw-semibold">Mechanics</p>
        <button class="nav-link text-start" id="filters-tab" data-bs-toggle="pill" data-bs-target="#filters" type="button" role="tab" aria-controls="filters" aria-selected="false">Filters</button>
        <button class="nav-link text-start" id="regions-tab" data-bs-toggle="pill" data-bs-target="#regions" type="button" role="tab" aria-controls="regions" aria-selected="false">Regions</button>
        <button class="nav-link text-start" id="actions-tab" data-bs-toggle="pill" data-bs-target="#actions" type="button" role="tab" aria-controls="actions" aria-selected="false">Actions &amp; Trigger</button>
        <button class="nav-link text-start" id="variables-tab" data-bs-toggle="pill" data-bs-target="#variables" type="button" role="tab" aria-controls="variables" aria-selected="false">Variables</button>
        <button class="nav-link text-start" id="spawns-tab" data-bs-toggle="pill" data-bs-target="#spawns" type="button" role="tab" aria-controls="spawns" aria-selected="false">Spawns</button>
        <p class="h6 fw-semibold">Gear</p>
        <button class="nav-link text-start" id="kits-tab" data-bs-toggle="pill" data-bs-target="#kits" type="button" role="tab" aria-controls="kits" aria-selected="false">Kits</button>
        <button class="nav-link text-start" id="shops-tab" data-bs-toggle="pill" data-bs-target="#shops" type="button" role="tab" aria-controls="shops" aria-selected="false">Shops</button>
      </div>  
    </div>
    <!-- Center column -->
    <div class="col">
      <p class="h5">Map Attributes</p>
      <hr class="my-3">
      <div class="tab-content" id="sidebar-tabContent">
        <!-- Main Map Elements content -->
        <div class="tab-pane fade show active" id="main-map-elements" role="tabpanel" aria-labelledby="main-map-elements" tabindex="0">
          <MainMapElement />
        </div>
        <!-- Authors & Contributors content -->
        <div class="tab-pane fade" id="authors-contributors" role="tabpanel" aria-labelledby="authors-contributors-tab" tabindex="0">
          <AuthorsContributors />
        </div>
        <!-- Teams/Players content -->
        <div class="tab-pane fade" id="teams-players" role="tabpanel" aria-labelledby="teams-players-tab" tabindex="0">
          <Teams />
        </div>
        <!-- Kits content -->
        <div class="tab-pane fade" id="kits" role="tabpanel" aria-labelledby="kits-tab" tabindex="0">
          <Kits />
        </div>
        <!-- Objectives content -->
        <div class="tab-pane fade" id="objectives" role="tabpanel" aria-labelledby="objectives-tab" tabindex="0">
          <Objectives />
        </div>
        <!-- Filters content -->
        <div class="tab-pane fade" id="filters" role="tabpanel" aria-labelledby="filters-tab" tabindex="0">
          <Filters />
        </div>
        <!-- Regions content -->
        <div class="tab-pane fade" id="regions" role="tabpanel" aria-labelledby="regions-tab" tabindex="0">
          <Regions />
        </div>
        <!-- Actions & Trigger content -->
        <div class="tab-pane fade" id="actions" role="tabpanel" aria-labelledby="actions-tab" tabindex="0">
          <ActionsTrigger />
        </div>
        <!-- Variables content -->
        <div class="tab-pane fade" id="variables" role="tabpanel" aria-labelledby="variables-tab" tabindex="0">
          <Variables />
        </div>
        <!-- Spawns content -->
        <div class="tab-pane fade" id="spawns" role="tabpanel" aria-labelledby="spawn-tab" tabindex="0">
          <Spawns />
        </div>
        <!-- Shop content -->
        <div class="tab-pane fade" id="shops" role="tabpanel" aria-labelledby="shops-tab" tabindex="0">
          <Shop />
        </div>
      </div>
      <!-- Output Control -->
      <hr class="my-3">
      <button type="button" class="btn btn-success" title="Add all entries in the current form to the XML output"><i class="bi bi-plus-lg"></i> Add to Output</button>
      <button type="button" class="btn btn-secondary" title="Inserts an end tag for the selected XML element">&#47;&gt;</button>
      <div class="float-end">
        <button type="button" class="btn btn-danger" title="Clear all input for this form only">Clear Input</button>
      </div>
    </div>
    <!-- Right column -->
    <div class="col-sm-4">
      <p class="h5">XML Output</p>
      <hr class="my-3">
      <textarea class="form-control font-monospace bg-light-subtle" id="textAreaExample" rows="8" placeholder="Your XML file will appear here once the required map details are populated." readonly></textarea>
      <hr class="my-3">
      <div class="text-center">
          <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#importXMLModal" disabled aria-disabled="true"><i class="bi bi-upload"></i> Import XML</button>
          <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exportXMLModal"><i class="bi bi-download"></i> Export XML</button>
          <button type="button" class="btn btn-danger" data-bs-toggle="modal" data-bs-target="#clearallModal"><i class="bi bi-trash3"></i> Clear All</button>
      </div>
      <!-- Import XML modal -->
      <div class="modal fade" tabindex="-1" id="importXMLModal">
        <div class="modal-dialog modal-dialog-centered">
          <div class="modal-content">
            <div class="modal-header">
              <h5 class="modal-title">Import XML <span class="badge bg-warning">Beta</span></h5>
              <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
            </div>
            <div class="modal-body">
              <p>Select a valid <code>map.xml</code> document to import. This will clear any changes made prior to the upload.</p>
              <div class="mb-3">
                <input class="form-control" type="file" accept=".xml" id="xmlFileImport">
              </div>
            </div>
            <div class="modal-footer">
              <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Cancel</button>
              <button type="button" class="btn btn-success" disabled>Import</button>
            </div>
          </div>
        </div>
      </div>
      <!-- Export XML modal -->
      <div class="modal fade" tabindex="-1" id="exportXMLModal">
        <div class="modal-dialog modal-dialog-centered">
          <div class="modal-content">
            <div class="modal-header">
              <h5 class="modal-title">Export XML</h5>
              <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
            </div>
            <div class="modal-body">
              <p>Your <code>map.xml</code> document has been exported and is ready for download.</p>
            </div>
            <div class="modal-footer">
              <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Cancel</button>
              <button type="button" class="btn btn-success">Download</button>
            </div>
          </div>
        </div>
      </div>
      <!-- Clear All modal -->
      <div class="modal fade" tabindex="-1" id="clearallModal">
        <div class="modal-dialog modal-dialog-centered">
          <div class="modal-content">
            <div class="modal-header">
              <h5 class="modal-title">Confirm Clear All</h5>
              <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
            </div>
            <div class="modal-body">
              <p>Are you sure you want to clear all entries? Any unsaved changes will be lost.</p>
            </div>
            <div class="modal-footer">
              <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Cancel</button>
              <button type="button" class="btn btn-danger">Clear All</button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>