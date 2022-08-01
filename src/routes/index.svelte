<script>
</script>

<section class="home bd-grid" id="home">
  <div class="home_data">
      <h1 class="home_title">Hi,<br>I'am <span class="home_title-color">Marlon</span><br> Web Designer</h1>
      
      <a href="/contact" class="button">Contact</a>
  </div>

  <div class="home_social">
      <a href="/" class="home_social-icon"><i class='bx bxl-linkedin'></i></a>
      <a href="/" class="home_social-icon"><i class='bx bxl-behance' ></i></a>
      <a href="/" class="home_social-icon"><i class='bx bxl-github' ></i></a>
  </div>

  <div class="home_img">
      <svg class="home_blob" viewBox="0 0 479 467" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
          <mask id="mask0" mask-type="alpha">
              <path d="M9.19024 145.964C34.0253 76.5814 114.865 54.7299 184.111 29.4823C245.804 6.98884 311.86 -14.9503 370.735 14.143C431.207 44.026 467.948 107.508 477.191 174.311C485.897 237.229 454.931 294.377 416.506 344.954C373.74 401.245 326.068 462.801 255.442 466.189C179.416 469.835 111.552 422.137 65.1576 361.805C17.4835 299.81 -17.1617 219.583 9.19024 145.964Z"/>
          </mask>
          <g mask="url(#mask0)">
              <path d="M9.19024 145.964C34.0253 76.5814 114.865 54.7299 184.111 29.4823C245.804 6.98884 311.86 -14.9503 370.735 14.143C431.207 44.026 467.948 107.508 477.191 174.311C485.897 237.229 454.931 294.377 416.506 344.954C373.74 401.245 326.068 462.801 255.442 466.189C179.416 469.835 111.552 422.137 65.1576 361.805C17.4835 299.81 -17.1617 219.583 9.19024 145.964Z"/>
              <image class="home_blob-img" x="50" y="60" href="/img/perfil.png"/>
          </g>
      </svg>
  </div>
</section>

<style>
  .home {
    position: relative;
    row-gap: 5rem;
    padding: 4rem 0 5rem;
  }

  .home_data {
    align-self: center;
  }

  .home_title {
    font-size: var(--big-font-size);
    margin-bottom: var(--mb-5);
  }

  .home_title-color {
    color: var(--first-color);
  }

  .home_social {
    display: flex;
    flex-direction: row;
  }

  .home_social-icon {
    width: max-content;
    margin-bottom: var(--mb-2);
    font-size: 1.5rem;
    color: var(--second-color);
  }

  .home_social-icon:hover {
    color: var(--first-color);
  }

  .home_img {
    position: absolute;
    right: 0;
    bottom: 0;
    width: 260px;
  }

  .home_blob {
    padding: auto;
    margin: 50px;
    width: 350px;
    fill: var(--first-color);
  }

  .home_blob-img {

    width: 360px;
  }
</style>
