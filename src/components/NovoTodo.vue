<template>
  <div class="row">
    <div class="columns">
      <div class="column is-half is-offset-one-quarter">
        <div class="field is-grouped">
          <p class="control is-expanded">
            <input type="text" class="input is-primary has-text-centered" placeholder="Nova tarefa..."
            v-model="tarefa"
            >
          </p>
          <p class="control">
            <a class="button is-success add-button">
              <span class="icon is-small">
                <i class="fa fa-plus"></i>
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
  name: 'novo-todo',
  data() {
    return {
      tarefa: ''
    }
  }
}
</script>
<style scoped>
.input {
  border-top: 0;
  border-right: 0;
  border-left: 0;
  border-bottom-width: 2px;
  border-radius: 0;
  outline: none;
  box-shadow: none;
}

.input.is-primary:focus {
  box-shadow: none;
}

.add-button {
  border-radius: 500px;
}
</style>
