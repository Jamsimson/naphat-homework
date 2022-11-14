<template>
  <q-layout view="hHh lpR fFf">
    <q-header elevated class="bg-primer text-white">
      <q-toolbar>
        <q-toolbar-title>
          <q-avatar> </q-avatar>
          TodoList
        </q-toolbar-title>
      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>
