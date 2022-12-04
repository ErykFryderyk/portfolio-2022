<template>
  <button class="primary-btn">
    <slot></slot>
  </button>
</template>

<script>
export default {
  name: "PrimaryButton",
  props: {
    textButton: String,
  }
};
</script>

<style>
.primary-btn {
  border: none;
  background-color: #46a2ca;
  border-radius: 50px;
  color: white;
  font-size: 16px;
  text-transform: uppercase;
  font-weight: bold;
  padding: 12px 30px;
  -webkit-box-shadow: 3px 3px 24px 0px rgba(200, 200, 200, 1);
  -moz-box-shadow: 3px 3px 24px 0px rgba(200, 200, 200, 1);
  box-shadow: 3px 3px 10px 0px rgba(200, 200, 200, 1);
  cursor: pointer;
  letter-spacing: 1px;
}
</style>
