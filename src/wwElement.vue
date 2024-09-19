<script>
export default {
  props: {
    content: { type: Object, required: true },
    wwFrontState: { type: Object, required: true },
    wwEditorState: { type: Object, required: true },
    randomProp: { type: String, required: false },
  },
};
</script>

<template>
  <wwLayout path="slot" />
</template>
