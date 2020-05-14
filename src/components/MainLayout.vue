<template>
  <div>
    <AppHeader />

    <!-- тут будет размещаться контент -->
    <slot></slot>

    <AppFooter />
  </div>
</template>

<script>
import AppHeader from "@/components/AppHeader";
import AppFooter from "@/components/AppFooter";

export default {
  components: {
    AppHeader,
    AppFooter
  }
}
</script>