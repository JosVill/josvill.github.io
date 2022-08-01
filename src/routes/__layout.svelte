<script>
    import "../styles/global.css";
    import "../assets/css/styles.css";
</script>

<title>Portfolio website complete</title>
<header class="l-header">
    <nav class="nav bd-grid">
        <div>
            <a href="/" class="nav_logo">Marlon</a>
        </div>

        <div class="nav_menu" id="nav-menu">
            <ul class="nav_list">
                <li class="nav_item"><a href="/" class="nav_link active">Home</a></li>
                <li class="nav_item"><a href="/about" class="nav_link">About</a></li>
                <li class="nav_item"><a href="/skills" class="nav_link">Skills</a></li>
                <li class="nav_item"><a href="/work" class="nav_link">Work</a></li>
                <li class="nav_item"><a href="/contact" class="nav_link">Contact</a></li>
            </ul>
        </div>

        <div class="nav_toggle" id="nav-toggle">
            <i class='bx bx-menu'></i>
        </div>
    </nav>
</header>


<main lass="l-main">
    <slot></slot>
</main>

<footer class="footer">
    <p class="footer_title">Marlon</p>
    <div class="footer_social">
        <a href="/" class="footer_icon"><i class="bx bxl-facebook" /></a>
        <a href="/" class="footer_icon"><i class="bx bxl-instagram" /></a>
        <a href="/" class="footer_icon"><i class="bx bxl-twitter" /></a>
    </div>
    <p class="footer_copy">&#169; Bedimcode. All rigths reserved</p>
</footer>

<style>
  .footer {
    background-color: var(--second-color);
    color: #fff;
    text-align: center;
    font-weight: var(--font-semi);
    padding: 2rem 0;
  }
  
  .footer_title {
    font-size: 2rem;
    margin-bottom: var(--mb-4);
  }
  
  .footer_social {
    margin-bottom: var(--mb-4);
  }
  
  .footer_icon {
    font-size: 1.5rem;
    color: #fff;
    margin: 0 var(--mb-2);
  }
  
  .footer_copy {
    font-size: var(--smaller-font-size);
  }
</style>
