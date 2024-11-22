<template>
  <div>
    <button @click="callBrian" class="call-button">
      Call Brian
    </button>
    <button @click="gotoLink" class="call-button">
      Map
    </button>
  </div>
</template>

<script>
export default {
  methods: {
    callBrian() {
      // Redirect to the Google Meet link
      window.location.href = "https://meet.google.com/stw-saxz-wja";
    },
    gotoLink() {
      // Google maps url
      window.location.href = "https://maps.app.goo.gl/re3gBsjxXuTSjfQ4A";
    },
  },
};
</script>

<style>
.call-button {
  margin: 10px;
  background-color: #4285f4; /* Google blue */
  color: white;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  font-size: 16px;
  cursor: pointer;
  transition: background-color 0.3s;
}

.call-button:hover {
  background-color: #3367d6;
}
</style>