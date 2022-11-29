<template>
  <div id="contact-us" class="container">
    <!--Section: Contact v.2-->
    <section class="mb-4">

      <!--Section heading-->
      <h2 class="h1-responsive font-weight-bold text-center my-4">Напишіть нам</h2>
      <!--Section description-->
      <p class="text-center w-responsive mx-auto mb-5">У вас є які-небудь питання? Напишіть нам, і ми з радістю надамо інформацію, що вас цікавить.</p>

      <div class="row">

        <!--Grid column-->
        <div class="col-md-9 mb-md-0 mb-5">
          <form id="contact-form" name="contact-form" action="mailto:v.shvets@vntu.edu.ua" method="POST">

            <!--Grid row-->
            <div class="row">

              <!--Grid column-->
              <div class="col-md-6">
                <div class="md-form mb-0">
                  <input type="text" id="name" name="name" class="form-control">
                  <label for="name" class="">Імʼя</label>
                </div>
              </div>
              <!--Grid column-->

              <!--Grid column-->
              <div class="col-md-6">
                <div class="md-form mb-0">
                  <input type="text" id="email" name="email" class="form-control">
                  <label for="email" class="">Пошта</label>
                </div>
              </div>
              <!--Grid column-->

            </div>
            <!--Grid row-->

            <!--Grid row-->
            <div class="row">
              <div class="col-md-12">
                <div class="md-form mb-0">
                  <input type="text" id="subject" name="subject" class="form-control">
                  <label for="subject" class="">Тема</label>
                </div>
              </div>
            </div>
            <!--Grid row-->

            <!--Grid row-->
            <div class="row">

              <!--Grid column-->
              <div class="col-md-12">

                <div class="md-form">
                  <textarea type="text" id="message" name="message" rows="2" class="form-control md-textarea"></textarea>
                  <label for="message">Повідомлення</label>
                </div>

              </div>
            </div>
            <!--Grid row-->

          </form>

          <div class="text-center text-md-left">
            <a class="btn btn-primary" onclick="document.getElementById('contact-form').submit();">Відправити</a>
          </div>
          <div class="status"></div>
        </div>
        <!--Grid column-->

        <!--Grid column-->
        <div class="col-md-3 text-center">
          <ul class="list-unstyled mb-0">
            <li><i class="fas fa-map-marker-alt fa-2x"></i>
              <p>Вул.Політехнічна (колишня воїнів-Інтернаціоналістів), 7, Вінниця, Вінницька область, 21000</p>
            </li>

            <li><i class="fas fa-phone mt-4 fa-2x"></i>
              <p>+380682160760</p>
            </li>

            <li><i class="fas fa-envelope mt-4 fa-2x"></i>
              <p>v.shvets@vntu.edu.ua</p>
            </li>
          </ul>
        </div>
        <!--Grid column-->

      </div>

    </section>
    <!--Section: Contact v.2-->
  </div>
</template>

<script>
export default {
  name: "contact-us"
}
</script>

<style scoped>

</style>
