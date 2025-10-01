<template>
  <aside>
    <v-card theme="dark">
      <v-layout>
        <v-navigation-drawer permanent style="width: 300px">
          <template v-slot:prepend>
            <v-list-item
              lines="two"
              prepend-avatar=""
              title="PM Cloudify"
              subtitle="Maintained by Pouya Mohammadi"
            ></v-list-item>
          </template>

          <v-divider></v-divider>

          <v-list density="compact" nav>
            <v-list-item
              prepend-icon="mdi-home-city"
              title="Home"
              value="home"
              link
              to="/"
            ></v-list-item>
            <v-list-item
              prepend-icon="mdi-account"
              title="Projects"
              value="account"
              link
              to="/projects"
            ></v-list-item>
            <v-list-item
              prepend-icon="mdi-account-group-outline"
              title="PM Github"
              link
              target="_blank"
              href="https://github.com/pouyam79i"
              value="users"
            ></v-list-item>
          </v-list>
        </v-navigation-drawer>
      </v-layout>
    </v-card>
  </aside>
</template>

<script setup></script>

<style lang="scss" scoped></style>
