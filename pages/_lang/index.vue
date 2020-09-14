<template>
  <div class="Content">
    <div class="container">
      <h1 class="Content__Title">
        {{ $t('home.title') }}
      </h1>
      <p>{{ $t('home.introduction') }}</p>
      <p>{{ $t('test-i18n') }} / {{ testI18n }}</p>
    </div>
  </div>
</template>

<script>
export default {
  head () {
    return { title: this.$t('home.title') }
  },
  data () {
    return {
      testI18n: this.$t('test-i18n'),
    }
  }
}
</script>
