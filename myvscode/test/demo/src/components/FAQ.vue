<template>
    <main class="faq">
        <h1>Frenquently Asked Questions</h1>

        <div class="error" v-if="error">
            can't load the questions
        </div>
    </main>
</template>

<script>
export default {
  name: 'faq',
  data () {
    return {
      questions: [],
      error: null
    }
  }
}
</script>
