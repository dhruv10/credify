<template>
  <div class="home">
    <div id="geetings">
      <div class="greeting-div">
        <div class="columns is-mobile">
          <div class="column has-text-weight-bold">
            Hi,
            <span class="username">Machu</span>
          </div>
          <div class="add-money-btn column has-text-right">
            <a href="/deposit" class="add-money-link">+ Add Funds</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "home",
  components: {}
};
</script>

<style scoped>
.greeting-div,
.services {
  margin-top: 10%;
}
.columns {
  margin-left: -0.75rem;
  margin-right: -0.75rem;
  margin-top: -0.75rem;
  display: flex;
  justify-content: space-between;
}
.columns:last-child {
  margin-bottom: -0.75rem;
}
.column {
  display: block;
  flex-basis: 0;
  flex-grow: 1;
  flex-shrink: 1;
  padding: 0.75rem;
}
.has-text-weight-bold {
  font-weight: 700 !important;
}
.add-money-btn {
    font-style: normal;
    font-weight: 700;
    font-size: 14px;
    line-height: 19px;
    text-align: center;
    color: #007bff;
}
.add-money-link[data-v-00f45f4e] {
    padding: 5px 10px;
    border: 1px solid #007bff;
    border-radius: 50px;
    background: #f1f0f0;
}
.add-money-btn a[data-v-00f45f4e] {
    color: #007bff;
}
a[data-v-00f45f4e] {
    color: #007bff;
    cursor: pointer;
    text-decoration: none;
}
</style>

