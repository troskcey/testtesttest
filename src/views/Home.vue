<template>
  <!-- в шаблон вкладываем контент, он будет вместо тега slot в компоненте MainLayout.vue -->
  <main-layout>
    <div>
      <div>
        <div>
          <!-- какой то разный контент -->
        </div>
      </div>
    </div>
  </main-layout>
</template>

<script>
import MainLayout from "@/components/MainLayout";

export default {
  components: {
    MainLayout
  }
}
</script>