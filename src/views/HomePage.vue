<template>
     
    <ion-content :fullscreen="true" id="main-content">
      <div id="container">
        <strong>Fitness</strong>
        <h1>made Simple</h1>
        <p>The best personal trainer app to help you get (and stay) in the best shape of your life </p>
        <ion-button>let's Get Fit </ion-button>
        <ion-item>
          <iframe 
          width="100%" 
          height="315"
          src="https://www.youtube.com/embed/tgbNymZ7vqY?controls=0"
          >
          </iframe>
        </ion-item>
        <ion-item>
            <ion-img src="https://img.freepik.com/free-psd/full-screen-smartphone-mockup-design_53876-65968.jpg?w=826&t=st=1659091565~exp=1659092165~hmac=ab39b6e5de69418d8cc9d446081d4b6c301155902f1e1c977d0b933086d4302e"/>
        </ion-item>
          <h1>Your Daily Workout App</h1>
          <p>Whether your goal is:</p>
      <ion-list>
        <ion-item>
          <p>Weight Loss</p>
        </ion-item>
        <ion-item>
          <p>
            Muscle Gain
          </p>
        </ion-item>
        <ion-item>
          <p>
            Improved Flexibility
          </p>
        </ion-item>
        <ion-item>
          <p>
            increased Mobility
          </p>
        </ion-item>
        
        <ion-item>
          <p>
            Injury Prevention
          </p>
        </ion-item>
        
        <ion-item>
          <p>
            Or to Simply Ton
          </p>
        </ion-item>
      </ion-list>
      
      <ionItem>
        <p>
          Sworkit can help. We’re one of the top fitness apps for iPhone, Android, or web users. Our workout plans are designed to help you reach your fitness goals faster and simpler.

But don’t just take our word for it. Check out the amazing transformations and testimonials from members of our SworkTeam below.
        </p>
      </ionItem>

    
        <h1>Features</h1>
        <h3>consistent</h3>
        <p>We believe fitness isn’t just something you do, it should be who you are and part of a lifestyle you enjoy. Our workout program is designed to help you make fitness a habit. With Sworkit, you can get in shape and stay in shape for life.</p>
        <h1>Convenient</h1>
        <p>
          No gym? No Equipment? No Time? No problem. We make it simple to workout at home or on the go. You choose the time - from 1 minute to 90 minutes - and we provide the variety, including strength training, stretching, cardio, yoga, and more.
        </p>
        <h1>Results</h1>
        <p>Sworkit has delivered life-changing results for thousands of people. Let us do it for you. Need personalized help? Get one-on-one guidance from certified fitness trainers with our Ask a Trainer program.</p>
  
      <ion-item>
          <ion-img src="https://img.freepik.com/free-psd/full-screen-smartphone-mockup-design_53876-65968.jpg?w=826&t=st=1659091565~exp=1659092165~hmac=ab39b6e5de69418d8cc9d446081d4b6c301155902f1e1c977d0b933086d4302e"/>
      </ion-item>

      <h1>Simply Work It</h1>
      <p>Sworkit means to simply work it. Your body was built to move daily and we’ve designed an innovative experience that makes it easy, enjoyable, and, yes, simple, to do just that.</p>
      

      <ion-list>
        <ion-item>
          <p>
            Variety: More than 500 unique workouts and over 900 exercises
          </p>
        </ion-item>
        <ion-item>
          <p>
Personalized: You choose the time you have to workout
          </p>
        </ion-item>
        <ion-item>
           <p>
            Easy: Recommended workout plans based on your goals
           </p>
        </ion-item>
        <ion-item>
          <p>
            Customizable: Create and save your own custom workouts
          </p>
        </ion-item>
        <ion-item>
             <p>
              Support: Certified trainers to answer your fitness and nutrition questions
             </p>
        </ion-item>
      </ion-list>

      </div>
      <footer-page></footer-page>
    </ion-content>
  
</template>

<script lang="ts">
import {
  IonContent,
  
  IonItem,
  IonImg,
  IonList
 } from '@ionic/vue';
import FooterPage from './FooterPage.vue';
export default {
  name: 'HomePage',
  components: {
    IonContent,
    IonItem,
    IonImg,
    IonList,
    FooterPage
}
};
</script>

<style scoped>







</style>
