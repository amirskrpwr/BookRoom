<template>
  <div class="d-flex flex-column">
    <div class="d-flex aligns-items-center justify-content-center">
      <img src="../assets/images/order-completed.png" alt="empty cart" />
    </div>
    <br />
    <div class="d-flex justify-content-center">
      <h5>صورت حساب شما با موفقیت پرداخت شد.</h5>
      <h5>سفارش شما ظرف ۲۴ تا ۷۲ ساعت آینده به دست شما خواهد رسید.</h5>
    </div>
  </div>
</template>

<script>
export default {
  name: "Success",
  mounted() {
    document.title = "Success | BookRoom";
  },
};
</script>

<style></style>
