<script>
  
</script>

<div class="main">
 <div class="content">

   <div class="name">
   <h1>Gagan</h1>
   </div>

   <div class="sabout">
    <h2>Code enthusiast & student</h2>
   </div>

   <div class="about">
   <p>Hiya! I'm a high school coder, sharpening my coding skills in Python🐍 and SvelteKit⚡</p>
   </div>

   <div class="projects">
   <h3>+projects</h3>


   <div class="QR-Gen">
    <h4><a href="https://github.com/Goofydoodle/QR-Gen" target="_blank">•QR-Gen</a></h4> 
   </div>
  
   <div class="QR-Gen-desc">
    <p>QR-Gen is a QR code generator made with Python.</p>
   </div>


  </div>


   <div class="contact">
   <h3>+contact</h3>
    <div class="github">
        <p>Github: <a href="https://github.com/Goofydoodle" target="_blank" class="git">@Goofydoodle</a></p>
    </div>
    <div class="email">
        <p>Email:<a href="mailto:contact@gaganuk.tech">contact@gaganuk.tech</a>
    </div>
</div>
</div>

</div>
<style>

.main{

  text-align: center;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;

}

.content {
            max-width: 600px;
            text-align: left; 
        }


 a {
  background-image: linear-gradient(
    to right,
    #54b3d6,
    #54b3d6 50%,
    #F97300 50%
  );
  background-size: 200% 100%;
  background-position: -100%;
  display: inline-block;
  padding: 5px 0;
  position: relative;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  
  transition: all 0.3s ease-in-out;
 }

 a:before{
  content: '';
  background: #54b3d6;
  display: block;
  position: absolute;
  bottom: -3px;
  left: 0;
  width: 0;
  height: 3px;
  transition: all 0.3s ease-in-out;
}

 a:hover {
 background-position: 0;
 }

 a:hover::before{
  width: 100%;
 }

    @media only screen and (max-width: 600px) {
  .name, .sabout, .about, .projects, .QR-Gen, .QR-Gen-desc, .contact, .github, .email {
    position: relative;
    text-align: left;
    justify-content: center;
    align-items: center;
    top: 0;
    right: 0;
    left: 0;
  }

  .name {
    top: 50px; 
    right: 0;
  }

  .sabout {
    top: 30px; 
    right: 0;
  }

  .about {
    top: 20px; 
    right: 0;
    font-size: 14px; 
  }

  .projects {
    top: 20px; 
    right: 0;
    font-size: 18px; 
  }

  .QR-Gen, .QR-Gen-desc {
    top: -10px; 
    right: 0;
    font-size: 14px; 
  }

  .contact {
    top: 10px; 
    right: 0;
    left: 0;
    font-size: 18px; 
  }

  .github, .email {
    top: -10px; 
    right: 0;
    left: 0;
    font-size: 12px; 
  }
}

</style>   