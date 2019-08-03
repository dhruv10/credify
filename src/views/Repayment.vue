<template>
  <div id="take-loan">
    <div id="geetings">
      <div class="greeting-div">
        <div class="columns is-mobile">
          <div class="column has-text-weight-bold">
            Take
            <span class="username">Loan</span>
          </div>
        </div>
      </div>
    </div>

    <div class="padding">
      <div class="balance-card card-one has-text-centered balance-card">
        <div class="columns-new">
          <div class="column">
            <span class="large">50.0</span>
          </div>
        </div>
        <div class="columns-new">
          <div class="column">
            <span class="balance-coin">Tenure:</span>
            <span class="balance-amount-new">6 months</span>
          </div>
        </div>
        <div class="columns-new">
          <div class="column">
            <span class="balance-coin">EMIs:</span>
            <span class="balance-amount-new">6</span>
          </div>
        </div>
        <div class="columns-new">
          <div class="column">
            <span class="balance-coin">Total Interest @24%:</span>
            <span class="balance-amount-new">122</span>
          </div>
        </div>
      </div>
    </div>

    <div class="padding">
      <a class="button is-link">Request Loan</a>
      <!-- <div class="fa-3x" style="display: block;">
        <i class="fas fa-circle-notch fa-spin"></i>
      </div>-->
    </div>
  </div>
</template>

<script>
export default {
  name: "repayment"
};
</script>

<style scoped>
.large {
  font-size: 50px;
}
.balance-amount-new {
  font-size: 18px;
}
.columns-new {
  margin-left: -0.75rem;
  margin-right: -0.75rem;
  margin-top: -0.25rem;
  display: flex;
  justify-content: flex-start;
}
</style>

