---

layout: default

---
<!-- CDS SITE SEAL -->
<div class='site-trust-seal'>
        <div class='trust-seal-link container'>
          <div class='row'>
            <div class='col ml-2 trust-seal-link-container'  data-toggle="collapse" data-target="#trust-seal-content" role="button"
            aria-expanded="false" aria-controls="trust-seal-content">
              <img src='assets/img/safari-pinned-tab.svg' class='trust-seal-flag' title='Flag'>
              <div>
                <span>An official website of the City of Chicago</span>
                <button class="trust-seal-action" title='Here’s how you know' 
                    data-target="#trust-seal-content" role="button"
                    data-toggle="collapse" 
                    aria-expanded="false" aria-controls="trust-seal-content">
                  <span>Here’s how you know</span>
                </button>	
              </div>										
            </div>
          </div>
        </div>
        <div class='trust-seal-content collapse container mt-4' aria-hidden='true' id='trust-seal-content'>
          <div class='row'>
            <div class='col-sm-6'>
                <div class="media">
                    <img class="mr-3 trust-seal-icon" src="assets/img/icon-dot-gov.svg" alt="Generic placeholder image">
                    <div class="media-body">
                    <h5 class="mt-0">The .gov means it’s official.</h5>
                    Municipal government websites often end in .gov or .org. Before sharing sensitive information, make sure you’re on a City of Chicago government site.
                    </div>
                </div>
            </div>
            <div class='col-sm-6'>
                <div class="media">
                    <img class="mr-3 trust-seal-icon" src="assets/img/icon-https.svg" alt="Generic placeholder image">
                    <div class="media-body">
                    <h5 class="mt-0">The site is secure.</h5>
                    The <strong>https://</strong> ensures that you are connecting to the official website and that any information you provide is encrypted and transmitted securely.
                    </div>
                </div>						
            </div>					
          </div>								
        </div>					
      </div>	
<!-- CDS NAVBAR -->
<header class="cds-header" role="banner">
	<div class="cds-navbar">
	  <button class="cds-menu-btn">MENU</button>
	  <div class="cds-logo" id="logo">
	    <em class="cds-logo-text">
	      <a href="#" title="Home">
	        <img src="assets/img/chicago.gov-logo.png" alt="Logo of the City of Chicago">
			    <h1 class="cds-header-title">Chicago</h1>
	      </a>
	    </em>
	  </div>
	</div>
 	<!--Start Navigation-->
<nav role="navigation" class="cds-nav">
    <div class="cds-nav-inner">
      <button class="cds-nav-close">
        <img src="assets/img/close.svg" alt="close">
      </button>
      <ul class="cds-nav-primary cds-accordion">
        <li><a class="cds-nav-link" href="#"><span>Home</span></a></li>
        <li><a class="cds-nav-link" href="#"><span>Page title</span></a></li>
        <li>
          <button class="cds-accordion-button cds-nav-link" aria-expanded="false" aria-controls="nav-5">
            <span>Dropdown</span>
          </button>
          <ul id="nav-5" class="cds-nav-submenu" aria-hidden="true">
              <li><a href="#">Page title</a></li>
              <li><a href="#">Page title one</a></li>
              <li><a href="#">Page title two</a></li>
              <li><a href="#">Link</a></li>
          </ul>
        </li>
        <li>
          <button class="cds-accordion-button cds-nav-link" aria-expanded="false" aria-controls="nav-0">
            <span>Mega menu</span>
          </button>
          <div id="nav-0" class="cds-nav-submenu cds-nav-megamenu row"  aria-hidden="true">
            <div class="col-4">
                <ul>
                    <li><a href="#">Page title</a></li>
                    <li><a href="#">Page title one</a></li>
                    <li><a href="#">Page title two</a></li>
                    <li><a href="#">Link</a></li>
                  </ul>
            </div>
            <div class="col-4">
                <ul>
                    <li><a href="#">Page title</a></li>
                    <li><a href="#">Page title one</a></li>
                    <li><a href="#">Page title two</a></li>
                    <li><a href="#">Link</a></li>
                  </ul>
            </div>
          </div>
        </li>
			</ul>		
      <div class="cds-nav-secondary">
        <ul class="cds-unstyled-list cds-nav-secondary-links">
            <li>
              <a href="#">
                Secondary nav
              </a>
            </li>
            <li>
              <a href="#">
                External link
              </a>
            </li>
        </ul>
      </div>

    </div>
  </nav>
</header>



<div class="container-fluid">
  <div class="row mt-3">
    <div class="col-lg-3 col-md-6">

      <!--Badges-->
      <span class="badge badge-primary">Primary</span>
      <span class="badge badge-secondary">Secondary</span>
      <span class="badge badge-success">Success</span>
      <span class="badge badge-danger">Danger</span>
      <span class="badge badge-warning">Warning</span>
      <span class="badge badge-info">Info</span>
      <span class="badge badge-light">Light</span>
      <span class="badge badge-dark">Dark</span>

      <!--Breadcrumb-->
      <nav aria-label="breadcrumb" role="navigation">
        <ol class="breadcrumb mt-2">
          <li class="breadcrumb-item"><a href="#">Home</a></li>
          <li class="breadcrumb-item"><a href="#">Library</a></li>
          <li class="breadcrumb-item active" aria-current="page">Data</li>
        </ol>
      </nav>

      <!--Buttons-->
      <div>
        <button type="button" class="btn btn-primary">Primary</button>
        <button type="button" class="btn btn-secondary">Secondary</button>
        <button type="button" class="btn btn-success">Success</button>
        <button type="button" class="btn btn-danger">Danger</button>
      </div>
      <div class="mt-2">
        <button type="button" class="btn btn-warning">Warning</button>
        <button type="button" class="btn btn-info">Info</button>
        <button type="button" class="btn btn-light">Light</button>
        <button type="button" class="btn btn-dark">Dark</button>
      </div>

      <!--Outline Buttons-->
      <div class="mt-2">
        <button type="button" class="btn btn-outline-primary">Primary</button>
        <button type="button" class="btn btn-outline-secondary">Secondary</button>
        <button type="button" class="btn btn-outline-success">Success</button>
        <button type="button" class="btn btn-outline-danger">Danger</button>
      </div>
      <div class="mt-2">
        <button type="button" class="btn btn-outline-warning">Warning</button>
        <button type="button" class="btn btn-outline-info">Info</button>
        <button type="button" class="btn btn-outline-light">Light</button>
        <button type="button" class="btn btn-outline-dark">Dark</button>
      </div>

      <!--Checkbox buttons-->

      <div class="mt-3">
        <div class="btn-group btn-group-toggle" data-toggle="buttons">
          <label class="btn btn-primary active">
            <input type="checkbox" checked autocomplete="off"> Yes
          </label>
          <label class="btn btn-primary">
            <input type="checkbox" autocomplete="off"> No
          </label>
        </div>

        <div class="btn-group btn-group-toggle" data-toggle="buttons">
          <label class="btn btn-secondary active">
            <input type="checkbox" checked autocomplete="off"> Yes
          </label>
          <label class="btn btn-secondary">
            <input type="checkbox" autocomplete="off"> No
          </label>
        </div>
        <div class="btn-group btn-group-toggle" data-toggle="buttons">
          <label class="btn btn-success active">
            <input type="checkbox" checked autocomplete="off"> Yes
          </label>
          <label class="btn btn-success">
            <input type="checkbox" autocomplete="off"> No
          </label>
        </div>
        <div class="btn-group btn-group-toggle" data-toggle="buttons">
          <label class="btn btn-danger active">
            <input type="checkbox" checked autocomplete="off"> Yes
          </label>
          <label class="btn btn-danger">
            <input type="checkbox" autocomplete="off"> No
          </label>
        </div>

      </div>

      <div class="mt-2">
        <div class="btn-group btn-group-toggle" data-toggle="buttons">
          <label class="btn btn-warning active">
            <input type="checkbox" checked autocomplete="off"> Yes
          </label>
          <label class="btn btn-warning">
            <input type="checkbox" autocomplete="off"> No
          </label>
        </div>
        <div class="btn-group btn-group-toggle" data-toggle="buttons">
          <label class="btn btn-info active">
            <input type="checkbox" checked autocomplete="off"> Yes
          </label>
          <label class="btn btn-info">
            <input type="checkbox" autocomplete="off"> No
          </label>
        </div>
        <div class="btn-group btn-group-toggle" data-toggle="buttons">
          <label class="btn btn-light active">
            <input type="checkbox" checked autocomplete="off"> Yes
          </label>
          <label class="btn btn-light">
            <input type="checkbox" autocomplete="off"> No
          </label>
        </div>
        <div class="btn-group btn-group-toggle" data-toggle="buttons">
          <label class="btn btn-dark active">
            <input type="checkbox" checked autocomplete="off"> Yes
          </label>
          <label class="btn btn-dark">
            <input type="checkbox" autocomplete="off"> No
          </label>
        </div>
      </div>

      <!--Dropdown buttons-->

      <div class="mt-3">
        <div class="btn-group">
          <button type="button" class="btn btn-primary">Primary</button>
          <button type="button" class="btn btn-primary dropdown-toggle dropdown-toggle-split"
                  data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            <span class="sr-only">Toggle Dropdown</span>
          </button>
          <div class="dropdown-menu">
            <a class="dropdown-item" href="#">Action</a>
            <a class="dropdown-item" href="#">Another action</a>
            <a class="dropdown-item" href="#">Something else here</a>
            <div class="dropdown-divider"></div>
            <a class="dropdown-item" href="#">Separated link</a>
          </div>
        </div><!-- /btn-group -->
        <div class="btn-group">
          <button type="button" class="btn btn-secondary">Secondary</button>
          <button type="button" class="btn btn-secondary dropdown-toggle dropdown-toggle-split"
                  data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            <span class="sr-only">Toggle Dropdown</span>
          </button>
          <div class="dropdown-menu">
            <a class="dropdown-item" href="#">Action</a>
            <a class="dropdown-item" href="#">Another action</a>
            <a class="dropdown-item" href="#">Something else here</a>
            <div class="dropdown-divider"></div>
            <a class="dropdown-item" href="#">Separated link</a>
          </div>
        </div><!-- /btn-group -->
        <div class="btn-group">
          <button type="button" class="btn btn-success">Success</button>
          <button type="button" class="btn btn-success dropdown-toggle dropdown-toggle-split"
                  data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            <span class="sr-only">Toggle Dropdown</span>
          </button>
          <div class="dropdown-menu">
            <a class="dropdown-item" href="#">Action</a>
            <a class="dropdown-item" href="#">Another action</a>
            <a class="dropdown-item" href="#">Something else here</a>
            <div class="dropdown-divider"></div>
            <a class="dropdown-item" href="#">Separated link</a>
          </div>
        </div><!-- /btn-group -->
      </div>
      <div class="mt-2">
        <div class="btn-group">
          <button type="button" class="btn btn-info">Info</button>
          <button type="button" class="btn btn-info dropdown-toggle dropdown-toggle-split"
                  data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            <span class="sr-only">Toggle Dropdown</span>
          </button>
          <div class="dropdown-menu">
            <a class="dropdown-item" href="#">Action</a>
            <a class="dropdown-item" href="#">Another action</a>
            <a class="dropdown-item" href="#">Something else here</a>
            <div class="dropdown-divider"></div>
            <a class="dropdown-item" href="#">Separated link</a>
          </div>
        </div><!-- /btn-group -->
        <div class="btn-group">
          <button type="button" class="btn btn-warning">Warning</button>
          <button type="button" class="btn btn-warning dropdown-toggle dropdown-toggle-split"
                  data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            <span class="sr-only">Toggle Dropdown</span>
          </button>
          <div class="dropdown-menu">
            <a class="dropdown-item" href="#">Action</a>
            <a class="dropdown-item" href="#">Another action</a>
            <a class="dropdown-item" href="#">Something else here</a>
            <div class="dropdown-divider"></div>
            <a class="dropdown-item" href="#">Separated link</a>
          </div>
        </div><!-- /btn-group -->
        <div class="btn-group">
          <button type="button" class="btn btn-danger">Danger</button>
          <button type="button" class="btn btn-danger dropdown-toggle dropdown-toggle-split"
                  data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            <span class="sr-only">Toggle Dropdown</span>
          </button>
          <div class="dropdown-menu">
            <a class="dropdown-item" href="#">Action</a>
            <a class="dropdown-item" href="#">Another action</a>
            <a class="dropdown-item" href="#">Something else here</a>
            <div class="dropdown-divider"></div>
            <a class="dropdown-item" href="#">Separated link</a>
          </div>
        </div><!-- /btn-group -->

      </div>


      <!--Forms-->

      <div class="mt-3">
        <form>
          <div class="form-group">
            <label for="exampleInputEmail1">Form label</label>
            <input type="email" class="form-control" id="exampleInputEmail1"
                   aria-describedby="emailHelp"
                   placeholder="Enter email">
            <small id="emailHelp" class="form-text text-muted">Form Text - To give hints and things</small>
          </div>
        </form>

      </div>

      <div class="mt-2">
        <div class="custom-control custom-checkbox">
          <input type="checkbox" class="custom-control-input" id="customCheck1">
          <label class="custom-control-label" for="customCheck1">Custom check</label>
        </div>
        <div class="custom-control custom-radio">
          <input type="radio" id="customRadio1" name="customRadio" class="custom-control-input">
          <label class="custom-control-label" for="customRadio1">Custom radio</label>
        </div>
        <select class="custom-select">
          <option selected>Custom select menu</option>
          <option value="1">One</option>
          <option value="2">Two</option>
          <option value="3">Three</option>
        </select>
      </div>

      <div class="mt-2">
        <label class="custom-file">
          <input type="file" id="file" class="custom-file-input">
          <span class="custom-file-control"></span>
        </label>
      </div>


      <!--Pagination-->
      <div class="mt-2">
        <nav aria-label="...">
          <ul class="pagination">
            <li class="page-item disabled">
              <span class="page-link">Previous</span>
            </li>
            <li class="page-item">
              <a class="page-link" href="#!">1</a>
            </li>
            <li class="page-item active">
              <span class="page-link">
                2
                <span class="sr-only">(current)</span>
              </span>
            </li>
            <li class="page-item">
              <a class="page-link" href="#!">3</a>
            </li>
            <li class="page-item">
              <a class="page-link" href="#!">Next</a>
            </li>
          </ul>
        </nav>
      </div>

      <div class="mt-2">

        <div class="progress">
          <div class="progress-bar bg-primary" role="progressbar"
               style="width: 16%" aria-valuenow="16" aria-valuemin="0" aria-valuemax="100"></div>
          <div class="progress-bar bg-secondary" role="progressbar"
               style="width: 16%" aria-valuenow="16" aria-valuemin="0" aria-valuemax="100"></div>
          <div class="progress-bar bg-success" role="progressbar"
               style="width: 16%" aria-valuenow="16" aria-valuemin="0" aria-valuemax="100"></div>
          <div class="progress-bar bg-info" role="progressbar"
               style="width: 16%" aria-valuenow="16" aria-valuemin="0" aria-valuemax="100"></div>
          <div class="progress-bar bg-warning" role="progressbar"
               style="width: 16%" aria-valuenow="16" aria-valuemin="0" aria-valuemax="100"></div>
          <div class="progress-bar bg-danger" role="progressbar"
               style="width: 16%" aria-valuenow="16" aria-valuemin="0" aria-valuemax="100"></div>
          <div class="progress-bar bg-light" role="progressbar"
               style="width: 16%" aria-valuenow="16" aria-valuemin="0" aria-valuemax="100"></div>
          <div class="progress-bar bg-dark" role="progressbar"
               style="width: 16%" aria-valuenow="16" aria-valuemin="0" aria-valuemax="100"></div>
        </div>

        <div class="progress mt-2">
          <div class="progress-bar progress-bar-striped bg-primary" role="progressbar"
               style="width: 16%" aria-valuenow="16" aria-valuemin="0" aria-valuemax="100"></div>
          <div class="progress-bar progress-bar-striped bg-secondary" role="progressbar"
               style="width: 16%" aria-valuenow="16" aria-valuemin="0" aria-valuemax="100"></div>
          <div class="progress-bar progress-bar-striped bg-success" role="progressbar"
               style="width: 16%" aria-valuenow="16" aria-valuemin="0" aria-valuemax="100"></div>
          <div class="progress-bar progress-bar-striped bg-info" role="progressbar"
               style="width: 16%" aria-valuenow="16" aria-valuemin="0" aria-valuemax="100"></div>
          <div class="progress-bar progress-bar-striped bg-warning" role="progressbar"
               style="width: 16%" aria-valuenow="16" aria-valuemin="0" aria-valuemax="100"></div>
          <div class="progress-bar progress-bar-striped bg-danger" role="progressbar"
               style="width: 16%" aria-valuenow="16" aria-valuemin="0" aria-valuemax="100"></div>
          <div class="progress-bar progress-bar-striped bg-light" role="progressbar"
               style="width: 16%" aria-valuenow="16" aria-valuemin="0" aria-valuemax="100"></div>
          <div class="progress-bar progress-bar-striped bg-dark" role="progressbar"
               style="width: 16%" aria-valuenow="16" aria-valuemin="0" aria-valuemax="100"></div>
        </div>

      </div>


    </div>

    <div class="col-lg-3 col-md-6">

      <!--Alerts-->
      <div class="mb-2 alert alert-primary" role="alert">
        This is a primary alert with <a href="#" class="alert-link">an example link</a>.
      </div>
      <div class="mb-2 alert alert-secondary" role="alert">
        This is a secondary alert with <a href="#" class="alert-link">an example link</a>.
      </div>
      <div class="mb-2 alert alert-success" role="alert">
        This is a success alert with <a href="#" class="alert-link">an example link</a>.
      </div>
      <div class="mb-2 alert alert-danger" role="alert">
        This is a danger alert with <a href="#" class="alert-link">an example link</a>.
      </div>
      <div class="mb-2 alert alert-warning" role="alert">
        This is a warning alert with <a href="#" class="alert-link">an example link</a>.
      </div>
      <div class="mb-2 alert alert-info" role="alert">
        This is a info alert with <a href="#" class="alert-link">an example link</a>.
      </div>
      <div class="mb-2 alert alert-light" role="alert">
        This is a light alert with <a href="#" class="alert-link">an example link</a>.
      </div>
      <div class="mb-2 alert alert-dark" role="alert">
        This is a dark alert with <a href="#" class="alert-link">an example link</a>.
      </div>


      <div class="mt-2">
        <ul class="list-group">
          <li class="list-group-item list-group-item-primary">Dapibus ac facilisis in</li>
          <li class="list-group-item list-group-item-secondary">Cras justo odio</li>
          <li class="list-group-item list-group-item-success">Dapibus ac facilisis in</li>
          <li class="list-group-item list-group-item-danger">Porta ac consectetur ac</li>
          <li class="list-group-item list-group-item-warning">Vestibulum at eros</li>
          <li class="list-group-item list-group-item-info">Cras justo odio</li>
          <li class="list-group-item list-group-item-light">Dapibus ac facilisis in</li>
          <li class="list-group-item list-group-item-dark">Porta ac consectetur ac</li>
        </ul>


      </div>
    </div>

    <!--Progress-->
    <div class="col-lg-6 mt-lg-0 mt-4">
      <div class="card text-white bg-primary mb-2 d-inline-block" style="max-width: 18rem;">
        <div class="card-header">Header</div>
        <div class="card-body">
          <h4 class="card-title">Primary card title</h4>
          <p class="card-text">Some quick example text to build on the card title and make up the
            bulk of the card's content.</p>
        </div>
      </div>
      <div class="card text-white bg-secondary mb-2 d-inline-block" style="max-width: 18rem;">
        <div class="card-header">Header</div>
        <div class="card-body">
          <h4 class="card-title">Secondary card title</h4>
          <p class="card-text">Some quick example text to build on the card title and make up the
            bulk of the card's content.</p>
        </div>
      </div>
      <div class="card text-white bg-success mb-2 d-inline-block" style="max-width: 18rem;">
        <div class="card-header">Header</div>
        <div class="card-body">
          <h4 class="card-title">Success card title</h4>
          <p class="card-text">Some quick example text to build on the card title and make up the
            bulk of the card's content.</p>
        </div>
      </div>
      <div class="card text-white bg-danger mb-2 d-inline-block" style="max-width: 18rem;">
        <div class="card-header">Header</div>
        <div class="card-body">
          <h4 class="card-title">Danger card title</h4>
          <p class="card-text">Some quick example text to build on the card title and make up the
            bulk of the card's content.</p>
        </div>
      </div>
      <div class="card text-white bg-warning mb-2 d-inline-block" style="max-width: 18rem;">
        <div class="card-header">Header</div>
        <div class="card-body">
          <h4 class="card-title">Warning card title</h4>
          <p class="card-text">Some quick example text to build on the card title and make up the
            bulk of the card's content.</p>
        </div>
      </div>
      <div class="card text-white bg-info mb-2 d-inline-block" style="max-width: 18rem;">
        <div class="card-header">Header</div>
        <div class="card-body">
          <h4 class="card-title">Info card title</h4>
          <p class="card-text">Some quick example text to build on the card title and make up the
            bulk of the card's content.</p>
        </div>
      </div>
      <div class="card bg-light mb-2 d-inline-block" style="max-width: 18rem;">
        <div class="card-header">Header</div>
        <div class="card-body">
          <h4 class="card-title">Light card title</h4>
          <p class="card-text">Some quick example text to build on the card title and make up the
            bulk of the card's content.</p>
        </div>
      </div>
      <div class="card text-white bg-dark mb-2 d-inline-block" style="max-width: 18rem;">
        <div class="card-header">Header</div>
        <div class="card-body">
          <h4 class="card-title">Dark card title</h4>
          <p class="card-text">Some quick example text to build on the card title and make up the
            bulk of the card's content.</p>
        </div>
      </div>


      <div>

        <table class="table table-hover table-striped table-">
          <thead class="thead-dark">
          <tr>
            <th>#</th>
            <th>Column</th>
            <th>Column</th>
            <th>Column</th>
            <th>Column</th>
          </tr>
          </thead>
          <tbody>
          <tr>
            <th scope="row">1</th>
            <td class="table-primary">Content</td>
            <td class="table-secondary">Content</td>
            <td class="table-success">Content</td>
            <td class="table-danger">Content</td>
          </tr>
          <tr>
            <th scope="row">2</th>
            <td class="table-warning">Content</td>
            <td class="table-info">Content</td>
            <td class="table-light">Content</td>
            <td class="table-dark">Content</td>
          </tr>

          <tr>
            <th scope="row">1</th>
            <td class="bg-primary">Content</td>
            <td class="bg-secondary">Content</td>
            <td class="bg-success">Content</td>
            <td class="bg-danger">Content</td>
          </tr>
          <tr>
            <th scope="row">2</th>
            <td class="bg-warning">Content</td>
            <td class="bg-info">Content</td>
            <td class="bg-light">Content</td>
            <td class="bg-dark">Content</td>
          </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
<!-- 
<nav class="navbar navbar-expand-lg navbar-dark bg-primary">
  <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse"
          data-target="#navbarTogglerDemo03" aria-controls="navbarTogglerDemo03"
          aria-expanded="false"
          aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <a class="navbar-brand" href="#">Navbar</a>
  <div class="collapse navbar-collapse" id="navbarTogglerDemo03">
    <ul class="navbar-nav mr-auto mt-2 mt-md-0">
      <li class="nav-item active">
        <a class="nav-link" href="#!">Home
          <span class="sr-only">(current)</span>
        </a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#!">Link</a>
      </li>
      <li class="nav-item">
        <a class="nav-link disabled" href="#!">Disabled</a>
      </li>
    </ul>
    <form class="form-inline my-2 my-lg-0">
      <input class="form-control mr-sm-2" type="text" placeholder="Search">
    </form>
  </div>
</nav>
-->
  <div>
    <div>
            <!--Body text-->
      <h1>The Quick Brown Fox Jumped Over The Lazy Dog</h1>
      <h2>The Quick Brown Fox Jumped Over The Lazy Dog</h2>
      <h3>The Quick Brown Fox Jumped Over The Lazy Dog</h3>
      <h4>The Quick Brown Fox Jumped Over The Lazy Dog</h4>
      <h5>The Quick Brown Fox Jumped Over The Lazy Dog</h5>
      <h6>The Quick Brown Fox Jumped Over The Lazy Dog</h6>
      <p>Hello. I'm a little bit of body text. Plain and simple. The quick brown fox jumped over the lazy dog. The quick brown fox jumped over the lazy dog. The quick brown fox jumped over the lazy dog. The quick brown fox jumped over the lazy dog. The quick brown fox jumped over the lazy dog. The quick brown fox jumped over the lazy dog.</p>
      
    </div>
  </div>
</div>
<!-- CDS SITE FOOTER -->
<footer>
    <div class='footer-primary'>
      <div class='footer-primary-nav container' role='navigation'>
        <a href='#'>Link 1</a>
        <a href='#'>Link 2</a>
        <a href='#'>Link 3</a>
      </div>
    </div>
    <div class='footer-main'>
    <div class='container'>
      <div class='row'>
        <div class='col-sm-6'>
    
          <div class="media footer-media">
            <img class="align-self-center mr-3" src="assets/img/city_seal_clr.png" alt="City of Chicago">
            <div class="media-body align-self-center">
              <h3 class="mt-0">City of Chicago</h3>
            </div>
            </div>

        </div>
        <div class='col-sm-6'>
          <div class='footer-main-right'>
            <div class='footer-social-links'>
              <a href='#'><i class="fab fa fa-twitter"></i></a>
              <a href='#'><i class="fab fa fa-facebook"></i></a>
              <a href='#'><i class="fab fa fa-youtube"></i></a>
            </div>
            <div class='footer-contact'>
                <h4>Contact Info</h4>
            </div>
            <div class='footer-contact-links'>
                <a href="#">info@chicago.gov</a>
                <a href="#">(312)-774-2828</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</footer>