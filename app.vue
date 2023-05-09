<template lang="pug">
#QRCode
    img#QRCode__Img(src='@/images/image-qr-code.png')
    #QRCode__Box-Text
        h2#QRCode__Box-Text__Title  Improve your front-end skills by building projects.
        p#QRCode__Box-Text__Text Scan the QR code to visit Frontend Mentor and take your coding skills to the next level
</template>


<style lang="sass">
*
    box-sizing: border-box
    margin: 0
body 
    background: lightgrey
img
    width: 100%
#__nuxt 
    height: 100vh
    display: grid
    place-items: center
#QRCode
    --border: .75rem
    --padding: 1rem
    --gap: .9rem
    display: flex
    flex-direction: column
    gap: var(--gap)
    padding: var(--padding)
    background: white
    border-radius: var(--border)
    box-shadow: 12px 15px 17px -18px rgba(0,0,0,0.75)
    width: clamp(300px, calc(200px + 20%) ,450px) 
    margin: 0 auto
    &__Img
        border-radius: var(--border)
    &__Box-Text
        padding: var(--padding)
        display: grid
        text-align: center
        gap: var(--gap)
        &__Text
            font-size: 1.05rem
            color: grey


</style>