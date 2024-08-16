<svelte:head>
    <title>PGMGen</title> 
</svelte:head>
<!-- Main container -->
<div class="d-flex flex-column flex-fill justify-content-center align-items-center text-center">
  <h1>PGMGen</h1>
  <p>A simple website to assist in generating XML files for PvP Game Manager (PGM) maps.</p>
  <div class="row row-cols-1 row-cols-md-2 g-4">
    <div class="col">
      <div class="card h-100" style="width: 26rem;">
        <div class="card-body">
          <h5 class="card-title">PvP Game Manager (PGM)</h5>
          <hr>
          <div class="d-grid gap-2 mx-auto">
            <a class="btn btn-primary" href="/builder/pgm" role="button">Create a XML</a>
            <a class="btn btn-secondary disabled" role="button" aria-disabled="true">Create a XML from template</a>
          </div>
        </div>
      </div>
    </div>
    <!-- <div class="col">
      <div class="card h-100" style="width: 26rem;">
        <div class="card-body">
          <h5 class="card-title">Team Game Manager (TGM) <span class="badge text-bg-warning">Deprecated</span></h5>
          <hr>
          <div class="d-grid gap-2 mx-auto">
            <a class="btn btn-primary" href="#" role="button">Create a JSON</a>
            <a class="btn btn-secondary" href="#" role="button">Convert to PGM XML</a>
          </div>
        </div>
      </div>
    </div> -->
  </div>
</div>