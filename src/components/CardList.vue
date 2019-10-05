<template>
  <section class="card-list">
    <div class="card">
      <img
        src="https://images.unsplash.com/photo-1558981001-792f6c0d5068?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=700&q=60"
        alt="bike"
        class="card-img"
      />
      <div class="card-info">
        <h2 class="card-title">Card Title</h2>
        <p class="card-text">{{myData}}</p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  props: {
    myData: String
  }
};
</script>

<style scoped>
.card-list {
  width: 80vw;
  margin: 0 auto;
}

.card {
  width: 250px;
  height: auto;
  box-shadow: 0 0 3px rgba(51, 51, 51, 0.3);
}

.card .card-img {
  width: 100%;
  margin-bottom: 10px;
}

.card .card-info {
  padding: 10px;
}

.card-info .card-title,
.card-text {
  margin-bottom: 10px;
}
</style>