<template>
  <div class="home container-fluid">
    <div class="row" id="the-row">
      <div class="col">
        <div class="d-flex justify-content-center">
          <img
            src="https://cdn2.sportngin.com/attachments/logo_graphic/2db4-118290742/logo-bug-small_medium.png"
            id="logo"
          />
        </div>
        <div class="d-flex flex-column align-items-center">
          <h3>Coming Soon!</h3>
          <p id="dates">Friday, July 31st & Saturday, August 1st</p>
          <p>Stay tuned for 2020 reunion details.</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "home"
};
</script>

<style scoped>
.container-fluid {
  height: 100%;
  background-color: maroon;
}
p,
h3 {
  color: white;
}
#dates {
  margin-bottom: 5px;
}
#logo {
  width: 23vh;
}
#the-row {
  height: 100%;
  align-content: center;
}
</style>
