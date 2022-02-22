<template>
<form name="contact" netlify>
  <input type="hidden" name="contact" value="contact" />
  <p>
    <label>Name <input type="text" name="name" /></label>
  </p>
  <p>
    <label>Email <input type="email" name="email" /></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>
