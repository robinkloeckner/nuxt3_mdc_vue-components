<script setup>
const md = `
# Welcome to docs4.dev

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolorum eum exercitationem harum in iste magni perferendis quo ratione voluptatem voluptatum!

::ad{cssClass="info"}
<div>Some extra text from the Markdown content.</div>
::

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquam at blanditiis commodi doloribus facere necessitatibus nemo quo quos totam vero?
`
</script>

<template>
  <div>
    <MDC :value="md" />
  </div>
</template>

