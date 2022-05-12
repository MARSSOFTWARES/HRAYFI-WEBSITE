<template>
  <div class="head">
    <nav class="navbar navbar-expand-lg navbar-light head-bar">
      <div class="container-fluid container">
        <router-link to="/" exact
          ><a class="navbar-brand"
            ><img src="../../images/logo.png" alt="" class="logo" />RAYFi</a
          ></router-link
        >
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNav"
          aria-controls="navbarNav"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav" id="navbar-ul">
            <li class="nav-item">
              <router-link to="/about">
                <a class="nav-link">
                  <svg
                    version="1.1"
                    id="Capa_1"
                    xmlns="http://www.w3.org/2000/svg"
                    xmlns:xlink="http://www.w3.org/1999/xlink"
                    x="0px"
                    y="0px"
                    width="45.532px"
                    height="45.532px"
                    viewBox="0 0 45.532 45.532"
                    style="enable-background: new 0 0 45.532 45.532"
                    xml:space="preserve"
                  >
                    <g>
                      <path
                        d="M22.766,0.001C10.194,0.001,0,10.193,0,22.766s10.193,22.765,22.766,22.765c12.574,0,22.766-10.192,22.766-22.765
		S35.34,0.001,22.766,0.001z M22.766,6.808c4.16,0,7.531,3.372,7.531,7.53c0,4.159-3.371,7.53-7.531,7.53
		c-4.158,0-7.529-3.371-7.529-7.53C15.237,10.18,18.608,6.808,22.766,6.808z M22.761,39.579c-4.149,0-7.949-1.511-10.88-4.012
		c-0.714-0.609-1.126-1.502-1.126-2.439c0-4.217,3.413-7.592,7.631-7.592h8.762c4.219,0,7.619,3.375,7.619,7.592
		c0,0.938-0.41,1.829-1.125,2.438C30.712,38.068,26.911,39.579,22.761,39.579z"
                      />
                    </g>
                  </svg>
                  Se connecter
                </a>
              </router-link>
            </li>
            <li class="nav-item">
              <router-link to="/Help">
                <a class="nav-link" tabindex="-1">
<svg version="1.1" id="Capa_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
	 width="36.174px" height="36.174px" viewBox="0 0 36.174 36.174" style="enable-background:new 0 0 36.174 36.174;"
	 xml:space="preserve">
<g>
	<path d="M23.921,20.528c0,3.217-2.617,5.834-5.834,5.834s-5.833-2.617-5.833-5.834s2.616-5.834,5.833-5.834
		S23.921,17.312,23.921,20.528z M36.174,12.244v16.57c0,2.209-1.791,4-4,4H4c-2.209,0-4-1.791-4-4v-16.57c0-2.209,1.791-4,4-4h4.92
		V6.86c0-1.933,1.566-3.5,3.5-3.5h11.334c1.934,0,3.5,1.567,3.5,3.5v1.383h4.92C34.383,8.244,36.174,10.035,36.174,12.244z
		 M26.921,20.528c0-4.871-3.963-8.834-8.834-8.834c-4.87,0-8.833,3.963-8.833,8.834s3.963,8.834,8.833,8.834
		C22.958,29.362,26.921,25.399,26.921,20.528z"/>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
</svg>
                Déposer Une Anounce</a>
              </router-link>
            </li>
            <li class="nav-item">
              <router-link to="/Help">
                <a class="nav-link" tabindex="-1">Nous Contacter</a>
              </router-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <nav class="navbar navbar-expand-lg navbar-light head-search">
      <div class="container-fluid container">
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNav2"
          aria-controls="navbarNav"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span>Rechercher</span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav2">
          <form action="" class="row container">
            <div class="col-sm-3">
              <select class="form-select" aria-label="Default select example">
                <option selected>Choisir Categorie</option>
                <option value="1">One</option>
                <option value="2">Two</option>
                <option value="3">Three</option>
              </select>
            </div>
            <div class="col-sm-3">
              <select class="form-select" aria-label="Default select example">
                <option selected>Choisir Ville</option>
                <option value="1">One</option>
                <option value="2">Two</option>
                <option value="3">Three</option>
              </select>
            </div>
            <div class="col-sm-5">
              <input
                id="search-input"
                type="search"
                class="form-control"
                placeholder="Rechercher"
              />
            </div>
            <div class="col-sm-1">
              <button type="button" class="btn btn-outline-primary">
                Rechercher
              </button>
            </div>
          </form>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>
<style lang="scss" scoped>
$principale: #8ecae6;
$second: #219ebc;
$third: #023047;
$four: #fdc500;
$five: #fb8500;
.head {
  position: fixed;
  width: 100%;
  z-index: 2;
  .head-bar {
    width: 100%;
    background: white;
    .logo {
      width: 50px;
    }
    .navbar-brand {
      color: black;
      font-weight: bold;
      font-size: 30px;
      line-height: 40px;
    }
    .container-fluid {
      margin: auto;
      .navbar-collapse {
        ul {
          margin-left: auto;
          li {
            border-bottom: solid 2px $four;
            margin-right: 15px;
          }
          svg {
            height: 20px;
            fill: $four;
          }
          a {
            text-decoration: none;
            font-weight: bold;
            color: rgb(0, 0, 0);
          }
        }
      }
    }
  }
  .head-search {
    width: 100%;
    max-height: 60px;
    background: $principale;
    box-shadow: 0px 1px 3px #7c7c7c;
    padding: 7px 0;
    .navbar-toggler {
      color: white;
      width: 60%;
      padding: 10px 0;
      margin: 0px auto;
    }
    svg {
      height: 30px;
      max-width: 30px;
    }
  }
}
</style>
