<script>
</script>

<section>
    <h2 class="section-title">Skills</h2>
    <div class="skills_container bd-grid">
        <div>
            <h2 class="skills_subtitle">Profesional Skills</h2>
            <p class="skills_text">
                Lorem ipsum dolor sit, amet consectetur adipisicing elit. Velit
                optio id vero amet, alias architecto consectetur error eum eaque
                sit.
            </p>
            <div class="skills_data">
                <div class="skills_names">
                    <i class="bx bxl-html5 skills_icon" />
                    <span class="skills_name">HTML5</span>
                </div>
                <div class="skills_bar skills_html" />
                <div>
                    <span class="skills_percentage">95%</span>
                </div>
            </div>
            <div class="skills_data">
                <div class="skills_names">
                    <i class="bx bxl-css3 skills_icon" />
                    <span class="skills_name">CSS3</span>
                </div>
                <div class="skills_bar skills_css" />
                <div>
                    <span class="skills_percentage">85%</span>
                </div>
            </div>
            <div class="skills_data">
                <div class="skills_names">
                    <i class="bx bxl-javascript skills_icon" />
                    <span class="skills_name">JAVASCRIPT</span>
                </div>
                <div class="skills_bar skills_js" />
                <div>
                    <span class="skills_percentage">65%</span>
                </div>
            </div>
            <div class="skills_data">
                <div class="skills_names">
                    <i class="bx bxs-paint skills_icon" />
                    <span class="skills_name">UX/UI</span>
                </div>
                <div class="skills_bar skills_ux" />
                <div>
                    <span class="skills_percentage">85%</span>
                </div>
            </div>
        </div>

        <div>
            <img src="/img/work3.jpg" alt="" class="skills_img" />
        </div>
    </div>
</section>

<style>
  .skills_container {
    row-gap: 2rem;
    text-align: center;
  }
  
  .skills_subtitle {
    margin-bottom: var(--mb-2);
  }
  
  .skills_text {
    margin-bottom: var(--mb-4);
  }
  
  .skills_data {
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: relative;
    font-weight: var(--font-semi);
    padding: .5rem 1rem;
    margin-bottom: var(--mb-4);
    border-radius: .5rem;
    box-shadow: 0px 4px 25px rgba(14, 36, 49, 0.15);
  }
  
  .skills_icon {
    font-size: 2rem;
    margin-right: var(--mb-2);
    color: var(--first-color);
  }
  
  .skills_names {
    display: flex;
    align-items: center;
  }
  
  .skills_bar {
    position: absolute;
    left: 0;
    bottom: 0;
    background-color: var(--first-color);
    height: .25rem;
    border-radius: .5rem;
    z-index: var(--z-back);
  }
  
  .skills_html {
    width: 95%;
  }
  
  .skills_css {
    width: 85%;
  }
  
  .skills_js {
    width: 65%;
  }
  
  .skills_ux {
    width: 85%;
  }
  
  .skills_img {
    border-radius: .5rem;
  }
</style>
