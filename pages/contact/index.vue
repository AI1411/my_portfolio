<template>
  <div class="columns is-mobile">
    <div class="column is-three-fifths is-offset-one-fifth">
      <div class="field">
        <label class="label">お名前</label>
        <div class="control">
          <input class="input is-medium" type="text">
        </div>
      </div>
      <div class="field">
        <label class="label">メールアドレス</label>
        <div class="control">
          <input class="input is-medium" type="text">
        </div>
      </div>
      <div class="field">
        <label class="label">メッセージ</label>
        <div class="control">
          <textarea class="textarea is-medium"></textarea>
        </div>
      </div>
      <div class="control">
        <button type="submit" class="button is-link is-fullwidth has-text-weight-medium is-medium">送信する
        </button>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: "index"
  }
</script>

<style scoped>

</style>
