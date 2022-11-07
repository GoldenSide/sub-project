<!---*
* @description 
* @fileName home.vue
* @author 叶金龙
* @date 2022/11/07 17:12:54
*--->
<template>
  <div></div>
</template>

<script lang="ts">
import { defineComponent, reactive, toRefs, SetupContext, ref } from "vue";
interface Data {}
export default defineComponent({
  name: "",
  props: {},
  components: {},
  setup(props, ctx: SetupContext) {
    const data: Data = reactive<Data>({});
    return {
      ...toRefs(data),
    };
  },
});
</script>

<style scoped lang="scss"></style>
