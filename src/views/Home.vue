<template>
  <div id="app">
    <vue-editor v-model="content"></vue-editor>
  </div>
</template>

<script>
// @ is an alias to /src
// import Editor from "@/components/Editor.vue";
// import { quillEditor } from "vue-quill-editor";
import { VueEditor } from "vue2-editor";

export default {
  name: "Home",
  components: {
    VueEditor,
  },
  data() {
    return {
      content: "<h1>masinahikē ōta</h1>",
    };
  },
};
</script>
