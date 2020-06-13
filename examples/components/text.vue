<template>
  <div class="hello">
    <Button type="primary">
      测试文档
    </Button>
  
  </div>
</template>

<script>
import { Button } from 'element-ui'
import 'element-ui/lib/theme-chalk/button.css'
export default {
  name: 'Text',
  components: { Button },
  props: {
    message: {
      type: String,
      default: ''
    }
  }
}
</script>
