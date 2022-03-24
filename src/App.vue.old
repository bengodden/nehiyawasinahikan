<template>
  <v-app>
    <v-app-bar app color="primary" dark>
      <div class="d-flex align-center"></div>

      <v-spacer></v-spacer>
      <router-link to="/">
        <v-btn href="" target="_blank" text>
          <span class="mr-2">Home</span>
        </v-btn>
      </router-link>

      <router-link to="/about">
        <v-btn href="" target="_blank" text>
          <span class="mr-2">About</span>
          <v-icon>mdi-open-in-new</v-icon>
        </v-btn>
      </router-link>
    </v-app-bar>

    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
// import { quillEditor } from "vue-quill-editor";

export default {
  data() {
    return {
      name: "app",
      content: "<h2>Example</h2>",
      editorOption: {},
    };
  },
  components: {
    // quillEditor,
  },
};
</script>
