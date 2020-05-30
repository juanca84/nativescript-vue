<template>
    <Page>
        <ActionBar title="Hello world"/> -->
        <GridLayout columns="*" rows="*">
          <Image src="https://spartadev.com/resources/images/lazyraccoon.jpeg"></Image>  
        </GridLayout>
    </Page>
</template>

<script >
  export default {
    data() {
      return {
        msg: 'Hola Juanca! Bienvenido al futuro'
      }
    }
  }
</script>

<style scoped>
    ActionBar {
        background-color: #53ba82;
        color: #ffffff;
    }

    .message {
        vertical-align: center;
        text-align: center;
        font-size: 20;
        color: #333333;
    }
</style>
