<template>
  <div class="image-upload-wrapper">
    <h4>Image: (recommended 450x600px)</h4>
    <input type="file" />
    <img class="preview-image" />
    <div class="image_buttons">
      <div>
        <button>
          <img src="@/assets/icons/top.svg" alt="image top selector" />
        </button>
        <button>
          <img src="@/assets/icons/middle.svg" alt="image middle selector" />
        </button>
        <button>
          <img src="@/assets/icons/bottom.svg" alt="image bottom selector" />
        </button>
      </div>
      <button class="remove_btn">remove</button>
    </div>
  </div>
</template>

<style scoped>
.image-upload-wrapper {
  text-align: left;
}

.image_buttons {
  display: flex;
  justify-content: space-between;
}

.image_buttons img {
  width: 30px;
}

h4 {
  font-weight: 300;
  margin: 10px 0;
}

input[type='file'] {
  margin: 0 0 10px 0;
}

button {
  margin-right: 5px;
}

.remove_btn {
  color: rgb(208, 90, 90);
}

.remove_btn:hover {
  color: rgb(123, 44, 44);
}
</style>
