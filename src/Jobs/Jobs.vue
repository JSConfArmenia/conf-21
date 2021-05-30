<template>
  <div class="Job" id="Jobs">
    <h2 class="Title"> JOBS</h2>

    <div class="row Vacancies">
      <div class="col-md-4">
        <a href="https://www.simplytechnologies.net/career/frontend-developer">
            <h3 class="Vacancy">Senior Front-end Developer</h3>
            <p class="Company">Simply Technologies</p>
        </a>
        <a href="https://www.simplytechnologies.net/careers/javascript-developer">
            <h3 class="Vacancy">Full-Stack JS Developer</h3>
            <p class="Company">Simply Technologies</p>
        </a>
        <a href="https://hexact.io/career">
            <h3 class="Vacancy">Node.js Developer</h3>
            <p class="Company">Hexact, Inc.</p>
        </a>

        
      </div>
      <div class="col-md-4">    
        <a href="https://www.simplytechnologies.net/careers/angular">
            <h3 class="Vacancy">Mid+ Angular2+ Developer</h3>
            <p class="Company">Simply Technologies</p>
        </a>
        <a href="https://jobs.smartrecruiters.com/SuperAnnotate/743999742519834-senior-backend-software-engineer">
            <h3 class="Vacancy">Senior Backend Software Engineer</h3>
            <p class="Company">SuperAnnotate</p>
        </a>
        <a href="https://hexact.io/career">
            <h3 class="Vacancy">React.js Developer</h3>
            <p class="Company">Hexact, Inc.</p>
        </a>

      </div>
      <div class="col-md-4">    
        <a href="https://www.simplytechnologies.net/careers/react-native-developer">
            <h3 class="Vacancy">Mid React Native Developer</h3>
            <p class="Company">Simply Technologies</p>
        </a>
        <a href="https://www.linkedin.com/jobs/view/2533543354/?refId=rabGHr0icxYLCViR948gNg%3D%3D&trackingId=ji4zFY%2FNGhoj9RZGNALmVQ%3D%3D&trk=d_flagship3_company">
            <h3 class="Vacancy">Senior Front-end Software Engineer</h3>
            <p class="Company">MentorcliQ</p>
        </a>

      </div>
    </div>

  </div>
</template>

<script>
export default {

};
</script>

<style scoped lang="scss">
.Job {
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

.Vacancy {
  color: #333;
}

.Company {
  margin-bottom: 1.5em;
}

.Vacancies {
  width: 65%;
}

@media (max-width: 768px) {
  .Job {
    padding: 50px 0 20px;
  }

  .Vacancies {
    width: 100%;
  }

  .Title {
    font-size: 1.6em;
    margin-bottom: 20px;
  }

  .Vacancy {
    font-size: 1em;
  }
}
</style>
