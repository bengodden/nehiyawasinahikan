<template>
  <v-container>
    var options = { debug: 'info', modules: { toolbar: '#toolbar' },
    placeholder: 'Compose an epic...', readOnly: true, theme: 'snow' }; var
    editor = new Quill('#editor', options);
  </v-container>
</template>

<script>
export default {
  name: "HelloWorld",

  data: () => ({}),
};
</script>
