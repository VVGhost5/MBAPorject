<template>
  <section>
    <head>
      <title>Кафедра МБА</title>
      <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.9.1/font/bootstrap-icons.css" integrity="sha384-xeJqLiuOvjUBq3iGOjvSQSIlwrpqjSHXpduPd6rQpuiM3f5/ijby8pCsnbu5S81n" crossorigin="anonymous">
      <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-Zenh87qX5JnK2Jl0vWa8Ck2rdkQ2Bzep5IDxbcnCeuOxjzrPF/et3URy9Bv1WTRi" crossorigin="anonymous">
      <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-OERcA2EqjJCMA+/3y+gxIOqMEjwtxJY7qPCqsdltbNJuaOe923+mo//f6V8Qbsw3" crossorigin="anonymous"></script>
    </head>
    <Header />
    <image-section />
    <Main />
    <contact-us />
    <Footer />
  </section>
</template>

<script>
import Header from '~/components/Header'
import Main from '~/components/Main'
import Footer from '~/components/Footer'
import ContactUs from '~/components/ContactUs'
import ImageSection from "@/components/ImageSection";

export default {
  name: 'IndexPage',
  components: {
    Header, Footer, Main, ContactUs, ImageSection
  }
}
</script>
