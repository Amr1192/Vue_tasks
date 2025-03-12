<template>
  <div class="container my-2 border border-2 border-secondary p-1">
    <!-- header -->
    <div class="row my-1">
      <div class="col-12">
        <headercomponent
        :data="{
            name: 'Amr',
            branch: 'ITI Menofia',
            track: 'OS',
            gov: 'Menofia',
          }"
        />
      </div>
    </div>

    <div class="row m-2">
      <div class="col-3">
        <linkscomponent />
      </div>
      <div class="col-8 offset-1">
        <bodycomponent />
      </div>
    </div>

    <div class="row my-1">
      <div class="col-12">
        <footercomponent />
      </div>
    </div>
  </div>
</template>

<script>
import headercomponent from "./components/headercomponent.vue";
import footercomponent from "./components/footercomponent.vue";
import linkscomponent from "./components/linkscomponent.vue";
import bodycomponent from "./components/bodycomponent.vue";
export default {
  data: () => ({}),
  methods: {},

  components: {
    headercomponent,
    linkscomponent,
    bodycomponent,
    footercomponent,
  },
};
</script>

<style></style>
