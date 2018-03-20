<template>
  <div>
    <h1>Trade or View Your Portfolio
        <h6>You may Save or Load Your Data</h6>
    </h1>
    <hr>
    <p>Your Funds: {{ funds }}</p>
  </div>
</template>

<script>
export default {
    computed: {
        funds() {
            return this.$store.getters.funds;
        }
    }
}
</script>

<style>

</style>
