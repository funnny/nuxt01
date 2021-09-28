<template>
  <section class="section">
    <div class="columns is-mobile">
      <card title="Free" icon="github"> Open source on <a href="https://github.com/buefy/buefy"> GitHub </a> </card>

      <card title="Responsive" icon="cellphone-link"> <b class="has-text-grey"> Every </b> component is responsive </card>

      <card title="Modern" icon="alert-decagram"> Built with <a href="https://vuejs.org/"> Vue.js </a> and <a href="http://bulma.io/"> Bulma </a> </card>

      <card title="Lightweight" icon="arrange-bring-to-front"> No other internal dependency </card>
    </div>
  </section>
</template>

<script>
import { Vue, Component } from 'vue-property-decorator'
import Card from '~/components/Card'

@Component({
  components: {
    Card,
  },
})
export default class extends Vue {
  created() {
    console.log('created!!!')
  }
}
</script>
