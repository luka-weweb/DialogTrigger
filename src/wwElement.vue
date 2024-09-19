<script>
export default {
  props: {
    content: { type: Object, required: true },
    wwFrontState: { type: Object, required: true },
    wwEditorState: { type: Object, required: true },
  },
  c,
};
</script>

<template>
  <wwLayout path="slot" />
</template>
