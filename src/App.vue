<script setup>
  import navbar from './components/navbar.vue'
  import footerCompt from './components/footer.vue'
</script>

<template>
  <main class="banner pt-0 lg:pr-[150px] pr-10 sm:pr-[50px] lg:pb-[100px] pb-[0px] pl-10 sm:pl-[50px] lg:pl-[150px] "> 
    
    <header class="">
      <navbar></navbar>
    </header>

    <section class="mt-10 text-white flex sm:gap-10 gap-5 z-30 relative flex-col lg:flex-row">

      <section class="flex flex-col w-[100%] lg:w-[75%] mt-10 text-center lg:text-left">
          <div class="w-[100%] lg:w-[75%]">
            <h1 class="text-[2rem] font-bold">
              Soluciones digitales ágiles
            </h1>
            <h6 class="text-[1.2rem] font-medium">
              Llevá tu empresa al siguiente nivel con nuestros servicios.
            </h6>
            <p class="text-[1rem] font-normal mt-8">
              Como expertos en el campo, no solo proporcionamos soluciones de vanguardia en tecnologías de la información, sino que también le ofrecemos una guía personalizada a lo largo de todo el proceso.  Nos enfocamos en ayudar a mantener su negocio en la vanguardia, asegurándonos de que esté equipado para enfrentar los desafíos actuales y futuros con éxito
            </p>
            <div class="flex justify-center items-center flex-col sm:flex-row lg:justify-start pt-10 gap-4">
              <a href="https://wa.me/5493644845060" class="bg-black py-2.5 w-[150px] md:w-[200px] rounded-md text-center">¡Contactanos!</a>
            </div>
          </div>
      </section>
      
      <div class="lg:-ml-[82px] lg:-mt-0 -ml-[0px]">
        <img class="w-full lg:h-full h-[500px] object-contain" src="../public/img/iphone-screen.png" alt="">
      </div>
      
    </section>

    <div class="w-[100%] left-0 absolute bottom-0 hidden sm:block">
      <img class="w-full h-full" src="../public/img/applight-wave.svg" alt="">
    </div>
  </main>

  <section class="mt-[90px]" id="nosotros">
    <header class="flex justify-center flex-col items-center">
      <h3 class="font-bold text-[1.75rem]">
        Nosotros
        <span class="line"></span>
      </h3>
      <p class="text-[#818992] text-[18px]  w-[80%] text-center">
        Quebratech es una empresa con una visión empresarial sólida, caracterizada por su agilidad, creatividad y amplia experiencia tecnológica. Nosotros actuamos como socios en la evolución hacia las tecnologías del futuro, ofreciendo de manera constante servicios innovadores.
      </p>
    </header>

    <div class="items-center mt-[80px] div-grid" id="servicios">
      <article class="flex justify-center flex-col items-center text-center w-100">
        <div class="rounded-full rounded-bg text-[35px] text-white">
          <font-awesome-icon icon="headset" />
        </div>
        <div class="flex justify-center items-center flex-col">
          <h6 class="pt-3 pb-5 font-semibold text-[20px]">
            Soporte 24/7
          </h6>
          <p class="text-[#818992] text-[17px] w-[80%]">
            Asistencia ininterrumpida con nuestro servicio de soporte disponible las 24 horas, los 7 días de la semana, para resolver sus problemas en tiempo real.
          </p>
        </div>
      </article>
      <article class="flex justify-center flex-col items-center text-center w-100">
        <div class="rounded-full rounded-bg text-[35px] text-white">
          <font-awesome-icon icon="mobile-screen" />
        </div>
        <div class="flex justify-center items-center flex-col">
          <h6 class="pt-3 pb-5 font-semibold text-[20px]">
            Innovación
          </h6>
          <p class="text-[#818992] text-[17px] w-[80%]">
            Sumérjase en la era digital con nuestras soluciones innovadoras, impulsando la eficiencia y la vanguardia en su negocio.
          </p>
        </div>
      </article>
      <article class="flex justify-center flex-col items-center text-center w-100">
        <div class="rounded-full rounded-bg text-[35px] text-white">
          <font-awesome-icon icon="bolt" />
        </div>
        <div class="flex justify-center items-center flex-col">
          <h6 class="pt-3 pb-5 font-semibold text-[20px]">
            Agilidad Empresarial
          </h6>
          <p class="text-[#818992] text-[17px] w-[80%]">
            Optimice la agilidad de su negocio con nuestras soluciones diseñadas para adaptarse rápidamente a los cambios del mercado y las demandas del cliente.
          </p>
        </div>
      </article>
    </div>

    <div class="flex justify-center my-[90px]">
      <a href="https://wa.me/5493644845060" class="border-[#0000B7] hover:bg-[#0000B7] hover:text-white text-[#0000B7] border-2 py-2.5 px-10 text-xl rounded-md">¡Conoce más!</a>
    </div>


    <section class="section-banner h-[400px] flex justify-center items-center">
      <div class="z-30 text-center text-white relative text-4xl -mt-2">
        <h6 class="my-5 font-bold">
          ¿Qué esperas?
          <span class="line2"></span>
        </h6>
        <font-awesome-icon class="text-[50px]" icon="clock" />
      </div>
    </section>
  </section>

  <section id="asked">
    <header class="flex justify-center flex-col items-center mt-[100px]">
      <h3 class="font-bold text-[1.75rem] text-center">
        Frequently Asked Questions
        <span class="line"></span>
      </h3>
      <p class="text-[#818992] text-[18px]  w-[50%] text-center">
        Explore respuestas concisas a las preguntas más frecuentes sobre nuestras soluciones.
      </p>
    </header>

    <section class="flex flex-col md:flex-row gap-10 px-[50px] md:px-[120px] my-[100px]">
      <article class="flex flex-col flex-wrap gap-[50px] text-center sm:text-left">
        <div>
          <h6 class="text-[20px] py-2">¿Cuáles son las principales soluciones IT que ofrecen?</h6>
          <p class="text-[#818992]">Brindamos soluciones IT avanzadas para aplicaciones móviles en Android y iOS.</p>
        </div>
        <div>
          <h6 class="text-[20px] py-2">¿Cómo nos beneficia trabajar con ustedes?</h6>
          <p class="text-[#818992]">Colaborar con nosotros garantiza acceso a tecnologías de punta y asesoramiento experto para mantener su negocio competitivo.</p>
        </div>
        <div>
          <h6 class="text-[20px] py-2">¿Cuánto tiempo lleva implementar sus soluciones?</h6>
          <p class="text-[#818992]">El tiempo de implementación varía, pero nos esforzamos por lograr una integración eficiente en plazos razonables.</p>
        </div>
      </article>
      <article class="flex flex-col flex-wrap gap-[50px] text-center sm:text-left">
        <div>
          <h6 class="text-[20px] py-2">¿Qué medidas toman para proteger la privacidad de nuestros datos?</h6>
          <p class="text-[#818992]">Implementamos protocolos de seguridad robustos para garantizar la confidencialidad y la integridad de la información de nuestros clientes basados en normas ISO.</p>
        </div>
        <div>
          <h6 class="text-[20px] py-2">¿Ofrecen soporte técnico continuo?</h6>
          <p class="text-[#818992]">Sí, proporcionamos soporte técnico continuo para resolver cualquier problema y garantizar un funcionamiento sin problemas de nuestras soluciones.</p>
        </div>
        <div>
          <h6 class="text-[20px] py-2"> ¿Cómo nos mantienen actualizados sobre las últimas tendencias tecnológicas?</h6>
          <p class="text-[#818992]">Mantenemos a nuestros clientes informados mediante actualizaciones periódicas y capacitaciones para aprovechar al máximo las innovaciones tecnológicas relevantes.</p>
        </div>
      </article>
    </section>

  </section>

  <section class="bg-[#fafafa] border-t">

    <header class="flex justify-center flex-col items-center mt-[100px] mb-[50px]">
      <h3 class="font-bold text-[1.75rem] text-center">
        Clientes Satisfechos
        <span class="line"></span>
      </h3>
      <p class="text-[#818992] text-[18px]  w-[50%] text-center">
        Marcas que confían en nosotros
      </p>
    </header>

    <section class="flex flex-wrap gap-[100px] justify-center items-center pb-[100px]">
      <div class="w-[200px] h-100">
        <img width="100%" height="100%" src="../public/img/icono2.png" alt="">
      </div>
      <div class="w-[200px] h-100">
        <img width="100%" height="100%" src="../public/img/icono3.jpg" alt="">
      </div>
      <div class="w-[200px] h-100">
        <img width="100%" height="100%" src="../public/img/icono.svg" alt="">
      </div>
    </section>
    
  </section>
  
  <section class="section-footer h-[400px] flex justify-center items-center">
        <header class="flex justify-center flex-col items-center text-white z-30 relative">
          <h3 class="font-bold text-[1.75rem] text-center">
            ¡Potencia tu negocio!
          <span class="line2"></span>
          </h3>
          <p class="text-[18px] w-[80%] text-center leading-7">
            Descubra cómo hemos impulsado el crecimiento y el éxito de nuestros clientes.
          </p>
        </header>
  </section>
  <footer id="footer">
    <footerCompt></footerCompt>
  </footer>
</template>

<style>
.div-grid{
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 400px));
  justify-content: center;
  gap: 80px;
}
.rounded-bg{
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100px;
  height: 100px;
  background: #0000B7;
}
.banner{
    background: #0000B7;
    background: linear-gradient(to left, #7a60ff, #0000B7);
    position: relative;
}
.banner::before {
    content: "";
    display: block;
    position: absolute;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    background: url('../public/img/pattern.png');
    z-index: 2;
}

.line2,
.line{
    height: 2px;
    width: 50px;
    background: #0000B7;
    display: block;
    margin: 10px auto 20px;
}
.line2{
  background: #FFFF;
}
.line2::after,
.line::after{
    content: "";
    position: absolute;
    left: 50%;
    width: 150px;
    height: 2px;
    border-bottom: 2px dashed rgb(0, 0, 183);
    margin-left: -75px;
}
.line2::after{
  border-bottom: 2px dashed #FFFF;
}
.section-footer,
.section-banner{
  background-image: url('../public/img/video1.jpg');
  background-position: 100%;
  background-attachment: fixed ;
  position: relative;
}
.section-footer{
  background-image: url('../public/img/video2.jpg');
}
.section-footer::before,
.section-banner::before{
  content: '';
  left: 0;
  bottom: 0;
  position: absolute;
  background: rgba(0, 0, 183, .6);
  z-index: 6;
  height: 100%;
  width: 100%;

}





</style>
