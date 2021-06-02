<template>
  <div class="Faq" id="Faq">
    <h2 class="Title"> FREQUENTLY ASKED QUESTIONS</h2>

    <div class="row Answers">
      <div class="col-md-6">
        <h3 class="Question">What is JavaScript Conference Armenia?</h3>
        <p class="Answer">
          JS Conf Armenia is a big IT event that brings together a huge number of IT
          professionals to attend talks, workshops, participate in
          competitions, get informed about open positions at sponsor IT companies and more.
        </p>

        <h3 class="Question">Who are the speakers?</h3>
        <p class="Answer">
          To learn more about our speakers, please,
          <a href="#Speakers">click here</a>.
        </p>

        <h3 class="Question">How to become a speaker?</h3>
        <p class="Answer">
          You can submit your topic <a href="bit.ly/speakJS2021">here</a>. DEADLINE: June 15.
        </p>

        <!-- <h3 class="Question">What are the talk topics?</h3>
        <p class="Answer">
          To see the talk sessions timetable and topics, please
          <a href="#Schedule">click here</a>.
        </p> -->

        <h3 class="Question">What is the conference language?</h3>
        <p class="Answer">
          The conference will be held mainly in Armenian but there are also
          English talks included in the program. 
        </p>

        <h3 class="Question">When is it going to take place?</h3>
        <p class="Answer">
          The conference will take place from 9:00 to 18:00 on July 17, 2021.
        </p>

        <h3 class="Question">Where is it going to be held?</h3>
        <p class="Answer">
          JSConfAM21 will be held at
          <a href="https://goo.gl/maps/HmDBXyu3G9z" target="_blank">American University of Armenia</a>
          (40 Marshal Baghramyan Ave, Yerevan)․
        </p>


      </div>
      <div class="col-md-6">
        <h3 class="Question">How to participate?</h3>
        <p class="Answer">
          The tickets will be on sale in idram app really soon. Stay tuned.
        </p>

        <h3 class="Question">How much is the entry-ticket?</h3>
        <p class="Answer">
          5000AMD (tax included).
        </p>

        <!-- <h3 class="Question">When is the deadline for registration?</h3>
        <p class="Answer">
          There is no deadline but the sooner you register the more
          interesting it will be for you as a participant as you will
          have the chance to take part in the preconference activities.
        </p> -->

        <h3 class="Question">Who are behind the JS Conference Armenia? </h3>
        <p class="Answer">
          To see the JS Conference Armenia team, please,
          <a href="#Team">click here</a>.
        </p>

        <h3 class="Question">How can I help the team?</h3>
        <p class="Answer">
          Oh, thank you for your kindness. This year we are not accepting volunteer applications but share the word about the conf that will be appreciated. 
        </p>

        <h3 class="Question">Who supports JS Conf Armenia?</h3>
        <p class="Answer">
          To learn about our sponsors and partners, please,
          <a href="#Sponsors">click here</a>.
        </p>

        <h3 class="Question">How to become a sponsor?</h3>
        <p class="Answer">
          To request more info on JSConfAM21 sponsorship, <a href="http://bit.ly/supportJSConfAM21">click here</a>. DEADLINE: June 7.
        </p>

      </div>
    </div>

  </div>
</template>

<script>
export default {

};
</script>

<style scoped lang="scss">
.Faq {
  display: flex;
  align-items: center;
  justify-content: flex-end;
  flex-direction: column;
  padding: 100px 0;
}

a {
  color: #4bb463;
  font-weight: bold;
}


.Title {
  text-transform: uppercase;
  text-align: center;
  margin-bottom: 50px;
  color: #198dbf;
}

.Question {
  color: #333;
}

.Answer {
  margin-bottom: 1.5em;
}

.Answers {
  width: 65%;
}

@media (max-width: 768px) {
  .Faq {
    padding: 50px 0 20px;
  }

  .Answers {
    width: 100%;
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
