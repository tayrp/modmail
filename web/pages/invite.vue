<template>
  <div>
    <Heading title="Redirecting..." />
  </div>
</template>

<script>
export default {
  head: {
    title: 'Invite',
  },
  mounted() {
    window.location.href =
      'https://discord.com/oauth2/authorize?client_id=1460499761160519741&permissions=268823640&response_type=code&redirect_uri=https%3A%2F%2Fcatfax.valerie.lol%2Fwelcome&scope=bot+applications.commands'
  },
}
</script>
