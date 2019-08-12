<template>
  <div class="row">
    <div class="columns">
      <div class="column">
        <div class="field is-grouped">
          <p class="control">
            <a class="button is-rounded is-small check-button">
              <span class="icon is-small"></span>
            </a>
          </p>
          <p class="control is-expanded"></p>
          <p class="control">
            <a class="button is-danger is-small">
              <span class="icon is-small">
                <i class="fa fa-trash"></i>
              </span>
            </a>
          </p>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "todo-list",
  data() {
    return {

    };
  }
};
</script>
<style scoped>
.button {
  border-radius: 500px;
}

.checked {
  text-decoration: line-through;
}
</style>
