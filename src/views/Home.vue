<template>
  <figure class="md:flex rounded-xl p-8 md:p-0">
    <img
      class="w-24 h-24 object-cover md:rounded-md md:w-48 md:h-auto rounded-full mx-auto"
      src="@/assets/imgs/leifnaknek.jpg"
      alt=""
      width="1000"
      height="1411" />
    <div class="pt-6 md:p-8 text-center md:text-left space-y-4">
      <div>
        <p class="text-lg font-medium text-light-primary dark:text-dark-primary">
          I am a student at UNC Charlotte graduating in Fall of 2022. I am majoring in Human Computer Interaction
          and will graduate with a B.A. in Computer Science. I am not that good at coding, so I used bootstrap to
          make myself a portfolio showing some of my work over the years at UNCC. In the summers I work in rural 
          Alaska to help manage a fishing fleet. 
        </p>
      </div>
      <div class="font-medium">
        <div class="text-sky-blue">Leif Andersen</div>
        <div class="text-light-primary dark:text-dark-primary">Office, OBI Seafoods - Nakenk, AK</div>
      </div>
    </div>
  </figure>
</template>

<script>
export default {
  name: "Home",
};
</script>
