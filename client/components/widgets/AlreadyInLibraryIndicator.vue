<template>
  <ui-tooltip v-if="alreadyInLibrary" :text="$strings.LabelAlreadyInYourLibrary" direction="top">
    <span class="material-icons ml-1" style="font-size: 0.8rem">check_circle</span>
  </ui-tooltip>
</template>

<script>
export default {
  props: {
    alreadyInLibrary: Boolean
  },
  data() {
    return {}
  },
  computed: {},
  methods: {},
  mounted() {}
}
</script>
