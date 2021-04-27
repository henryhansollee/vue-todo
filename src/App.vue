<template>
  <v-app>
    <v-card
      max-width="475"
      class="mx-auto"
    >
      <v-toolbar
        color="teal"
        dark
      >
        <v-toolbar-title>vue-todo</v-toolbar-title>
      </v-toolbar>

      <v-list
        two-line
        subheader
      >
        <v-list-item>
          <v-list-item-content>
            <v-list-item-title>Profile photo</v-list-item-title>
            <v-list-item-subtitle>Change your Google+ profile photo</v-list-item-subtitle>
          </v-list-item-content>
        </v-list-item>
      </v-list>

      <v-divider></v-divider>

      <v-list
        subheader
        two-line
        flat
      >
        <v-list-item-group
          v-model="settings"
          multiple
        >
          <v-list-item>
            <template v-slot:default="{ active, }">
              <v-list-item-action>
                <v-checkbox
                  :input-value="active"
                  color="primary"
                ></v-checkbox>
              </v-list-item-action>
              <v-list-item-content>
                <v-list-item-title>Notifications</v-list-item-title>
              </v-list-item-content>
            </template>
          </v-list-item>
        </v-list-item-group>
      </v-list>
    </v-card>
  </v-app>
</template>

<script>
export default {
  name: 'App',
  data: () => ({
    settings: [],
  }),
};
</script>
