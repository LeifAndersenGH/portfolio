<template>
<div>
  <UiTitle text="Projects" />
    <div>
      <div class="container mx-auto mt-4">

        <div class="row">
          <div class="col-md-4">
            <div class="card" style="width: 18rem;">
              <img src="@/assets/imgs/inflation.png" class="card-img-top" alt="...">
              <div class="card-body">
                <h5 class="card-title">Inflation Data</h5>
                <h6 class="card-subtitle mb-2 text-muted">Seaborn Visualization</h6>
                <p class="card-text">First project using Seaborn to visualize inflation data</p>
                <p> ㅤ </p>
                <a href="https://github.com/LeifAndersenGH/Inflation-Visualization.git" class="btn mr-2"><i class="fas fa-link"></i> Visit Site</a>
                <a href="https://github.com/LeifAndersenGH/Inflation-Visualization.git" class="btn"><i class="fab fa-github"></i> Github</a>
              </div>
            </div>
          </div>

          <div class="col-md-4">
            <div class="card" style="width: 18rem;">
              <img src="@/assets/imgs/knn.png" class="card-img-top" alt="...">
              <div class="card-body">
                <h5 class="card-title">Predicting Ski Resort Closures</h5>
                <h6 class="card-subtitle mb-2 text-muted">KNN Algorithm</h6>
                <p class="card-text">Using KNN to classify if ski resort weather will cause closure</p>
                <p> ㅤ </p>
                <a href="https://github.com/LeifAndersenGH/Predicting-Ski-Resort-Closures.git" class="btn mr-2"><i class="fas fa-link"></i> Visit Site</a>
                <a href="https://github.com/LeifAndersenGH/Predicting-Ski-Resort-Closures.git" class="btn"><i class="fab fa-github"></i> Github</a>
              </div>
            </div>
          </div>

          <div class="col-md-4">
            <div class="card" style="width: 18rem;">
              <img src="@/assets/imgs/wata.png" class="card-img-top" alt="...">
              <div class="card-body">
                <h5 class="card-title">Automatic Plant Waterer</h5>
                <h6 class="card-subtitle mb-2 text-muted">Web Server</h6>
                <p class="card-text">A front end display of rasberry pi data using sensors to detect soil moisture for a plant</p>
                <p> ㅤ </p>
                <a href="https://github.com/LeifAndersenGH/RPIServerWebApp" class="btn mr-2"><i class="fas fa-link"></i> Visit Site</a>
                <a href="https://github.com/LeifAndersenGH/RPIServerWebApp" class="btn"><i class="fab fa-github"></i> Github</a>
              </div>
            </div>
          </div> 
        </div>

      </div>
  </div>
</div>
</template>

<script>
import UiTitle from "@/components/ui/UiTitle";

export default {
  name: "Projects",
  components: { UiTitle },
};
</script>

<style>
:root {
  --gradient: linear-gradient(to left top, #DD2476 10%, #FF512F 90%) !important;
}

body {
  background: #111 !important;
}

.card {
  background: #222;
  border: 1px solid #dd2476;
  color: rgba(250, 250, 250, 0.8);
  margin-bottom: 2rem;
}

.btn {
  border: 5px solid;
  border-image-slice: 1;
  background: var(--gradient) !important;
  -webkit-background-clip: text !important;
  -webkit-text-fill-color: transparent !important;
  border-image-source:  var(--gradient) !important; 
  text-decoration: none;
  transition: all .4s ease;
}

.btn:hover, .btn:focus {
      background: var(--gradient) !important;
  -webkit-background-clip: none !important;
  -webkit-text-fill-color: #fff !important;
  border: 5px solid #fff !important; 
  box-shadow: #222 1px 0 10px;
  text-decoration: underline;
}
</style>
