<template>
<div>
  <UiTitle text="Links" />
  
  <head>

  <link href="https://fonts.googleapis.com/css?family=Raleway+Dots" rel="stylesheet" type="text/css">
  <link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet" type="text/css">

</head>
<section>
  <ul id="services">
    <h2>Leif's Socials</h2>
    <li>
      <div class="facebook">
        <a href="https://facebook.com/">
          <i class="fa fa-facebook" aria-hidden="true"></i>
        </a>
      </div>
      <span>Facebook</span>
    </li>
    <li>
      <div class="twitter">
        <a href="https://twitter.com">
          <i class="fa fa-twitter" aria-hidden="true"></i>
        </a>
      </div>
      <span>Twitter</span>
    </li>
    <li>
      <div class="youtube">
        <a href="https://www.youtube.com">
          <i class="fa fa-youtube" aria-hidden="true"></i>
        </a>
      </div>
      <span>YouTube</span>
    </li>
    <li>
      <div class="linkedin">
        <a href="https://www.linkedin.com/">
          <i class="fa fa-linkedin" aria-hidden="true"></i>
        </a>
      </div>
      <span>LinkedIn</span>
    </li>
    <li>
      <div class="instagram">
        <a href="https://www.instagram.com/layfand/">
          <i class="fa fa-instagram" aria-hidden="true"></i>
        </a>
      </div>
      <span>Instagram</span>
    </li>
    <li>
      <div class="github">
        <a href="https://github.com/LeifAndersenGH">
          <i class="fa fa-github" aria-hidden="true"></i>
        </a>
      </div>
      <span>Github</span>
    </li>
  </ul>
  
</section>

</div>
</template>


<style>
html, body {
  margin: 0;
  background-color: #77cc6d;
  font-family: 'Raleway Dots', sans-serif;
}

section #services {
  text-align: center;
  transform: translatez(0);
}
section #services h2 {
  margin: 80px 0px 40px;
  color: #fff;
  font-size: 2.4em;
  text-transform: uppercase;
  text-align: center;
}
section #services li {
  width: 120px;
  height: 140px;
  display: inline-block;
  margin: 20px;
  list-style: none;
}
section #services li div {
  width: 120px;
  height: 120px;
  color: #74d4b3;
  font-size: 3.4em;
  text-align: center;
  line-height: 120px;
  background-color: #fff;
  transition: all 0.5s ease;
}
section #services li a {
  color: #77cc6d;
}
section #services li div:hover {
  transform: rotate(360deg);
  border-radius: 100px;
}
section #services li span {
  width: 120px;
  height: 20px;
  display: block;
  padding: 15px 0px;
  color: #fff;
  text-transform: uppercase;
  font-size: 1.2em;
  text-align: center;
}
.credits a {
  display: block;
  text-align: center;
  color: #74d4b3;
  text-decoration: none;
  font-size: 24px;
  margin-top: 50px;
  background: white;
  padding: 20px;
  max-width: 300px;
}
</style>

<script>
import UiTitle from "@/components/ui/UiTitle";

export default {
  name: "Links",
  components: { UiTitle },
};
</script>
