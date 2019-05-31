<style lang="sass" scoped>
.container--doc
  width: 30rem
  margin: 0 auto
  
  h1
    text-align: center
  img
    width: calc(100% - 2rem)
    border: solid 1rem #fafafa
    box-shadow: 0 0 10px -3px rgba(0,0,0,0.3)

.text--content__narrow
  text-align: justify
  line-height: 1.8rem
  padding-bottom: 1rem
.first-letter
  &::first-letter
    font-size: 5rem
    float: left
    padding: 0 .5rem 1rem 0
    margin-top: 1.8rem

</style>

<template lang="pug">
  #app
    .container--doc
      h1 Welcome to Parcel
      p.text--content__narrow.first-letter Rushing to implement that initial idea is a hard habit to kick. Sometimes time is the motivating factor because you just have to get something done. In other instances, your first concept just feels so right that you can’t possibly imagine something better coming to you. Before you know it Project_V1.ai is open, and you’re deep in layers of distressed textures and the newly released GT font. You’ve lost track of your intended message entirely. Guilty.
      p.text--content__narrow My first take on our chosen theme resulted in a chaotic collage of sorts. Images were distorted using basic Photoshop filters, and proposed event deliverables showed the speaker’s name scribbled in almost completely illegible handwriting. Throw a bunch of haphazard elements on a page and you get visual chaos, right? That was my first thought, but I was missing something.
      p.text--content__narrow Sure it looked cool, but I leapt to the making phase of the project so quickly that I hadn’t stopped to fully flesh out the underlying point of everything. Season two of Airbnb Design—Talks is all about people who find order and activate within chaos, and I left out the order. The end result of my first take felt expected. I invested so quickly in my first concept that when faced with the necessity of proposing additional concepts, I stumbled a bit.
      img(src='~/public/a.png')
</template>

<script>
// import HelloWorld from './components/HelloWorld';
import './main.sass'

export default {
  components: {
    // HelloWorld
  }
}
</script>