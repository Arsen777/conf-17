<template>
  <section class="Faq" id="Faq">
    <div class="Container">

      <h2 class="Title">frequently asked questions</h2>

      <div class="row">
        <div class="col-md-6">
          <h3 class="Question">What is JavaScript Conference Armenia?</h3>
          <p class="Answer">
            JS Conference is a big IT event that brings together a huge number of IT
            professionals to attend talks, workshops, participate in
            competitions, get informed about open positions at sponsor IT companies and more.
          </p>

          <h3 class="Question">Who are the speakers?</h3>
          <p class="Answer">
            To learn more about our speakers, please,
            <a href="#Speakers" v-smooth-scroll="navConfig">click here</a>.
          </p>

          <h3 class="Question">What are the talk topics?</h3>
          <p class="Answer">
            To see the talk sessions timetable and topics, please
            <a href="#Schedule" v-smooth-scroll="navConfig">click here</a>.
          </p>

          <h3 class="Question">What is the conference language?</h3>
          <p class="Answer">
            The conference will be held mainly in Armenian but there are also
            English talks included in the program.
          </p>

          <h3 class="Question">When is it going to take place?</h3>
          <p class="Answer">
            The conference will take place from 10:00 to 18:00 on December 9, 2017.
          </p>

          <h3 class="Question">Where is it going to be held?</h3>
          <p class="Answer">
            JavaScript Cօnference Yerevan will be held at the B Building of
            <a href="https://goo.gl/maps/HmDBXyu3G9z" target="_blank">American University of Armenia</a>
            (40 Marshal Baghramyan Ave, Yerevan)․
          </p>

          <h3 class="Question">How to participate?</h3>
          <p class="Answer">
            The entry of JS Conference Yerevan 2017 is invitation-only so
            please make sure to request your invite
            <a href="https://goo.gl/forms/QWQzhSb7HqNn2Hem2" target="_blank">here</a>.
          </p>

        </div>
        <div class="col-md-6">

          <h3 class="Question">How much is the entry-ticket?</h3>
          <p class="Answer">
            The event entry is free of charge.
          </p>

          <h3 class="Question">When is the deadline for registration?</h3>
          <p class="Answer">
            There is no deadline but the sooner you register the more interesting it will be for you as a
            participant as you will have the chance to take part in the preconference activities.
          </p>

          <h3 class="Question">Who are behind the JS Conference Armenia? </h3>
          <p class="Answer">
            To see the JS Conference Armenia team, please,
            <a href="#Team" v-smooth-scroll="navConfig">click here</a>.
          </p>

          <h3 class="Question">How can I help the team?</h3>
          <p class="Answer">
            Oh, thank you for your kindness.
            To help us make the JavaScript Conference Armenia happen please <a href="https://goo.gl/cwwyiz" target="_blank">apply here</a>
            to become a JS Conf ninja volunteer!
          </p>

          <h3 class="Question">Who supports JS Conference Armenia?</h3>
          <p class="Answer">
            To learn about our sponsors and partners, please,
            <a href="#Sponsors" v-smooth-scroll="navConfig">click here</a>.
          </p>

          <h3 class="Question">Will I get a certificate of participation?</h3>
          <p class="Answer">
            Your certificate of participation in JS Conference is going to be
            your larger network in IT, updated knowledge,
            nice little gifts and good memories. Do you still need that piece of paper?
          </p>

        </div>
      </div>

    </div>
  </section>
</template>

<script>
export default {
  data: () => ({
    navConfig: {
      duration: 1000,
      offset: -66,
    },
  }),
};
</script>

<style scoped>

.Faq {
  padding: 60px 0;
  background-color: #f5f5f5;
}

a {
  color: #4bb463;
  font-weight: bold;
}


.Title {
  text-transform: uppercase;
  text-align: center;
  margin-bottom: 50px;
  color: #92278f;
}

.Question {
  color: #333;
}

.Answer {
  margin-bottom: 1.5em;
}

@media (max-width: 768px) {

  .Faq {
    padding: 30px 0;
    background-color: #f5f5f5;
  }

  .Title {
    font-size: 1.6em;
    margin-bottom: 20px;
  }

  .Question {
    font-size: 1em;
  }

}


</style>
