<template>
  <Button type="primary">
    主要按钮
  </Button>

  <router-view />
</template>

<script>
import { Button } from 'vant'

export default {
  components: {
    Button
  }
}
</script>
