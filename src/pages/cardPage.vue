<template>
  <div id="pageRoute">
    <b-container>
      <b-row class="container">
        <b-col lg="4" md>
          <card
            netlify="https://sleepy-benz-d43853.netlify.app/"
            github="https://github.com/rajeshjaga/Frontend-Mentor-Article-preview-component"
            status="completed"
            imgurl="https://github.com/rajeshjaga/Front-End-mentor-Challenges/blob/master/src/assets/challenge1.jpg?raw=true"
            cardTitle="Article Preview "
          />
        </b-col>
        <b-col lg="4">
          <card
            netlify="https://quirky-curran-5b4f2e.netlify.app/"
            github="https://github.com/rajeshjaga/fylo-data-storage-component"
            status="completed"
            imgurl="https://github.com/rajeshjaga/Front-End-mentor-Challenges/blob/master/src/assets/challenge2.jpg?raw=true"
            cardTitle="Fylo Data Storage"
          />
        </b-col>
        <b-col lg="4">
          <card
            github="https://github.com/rajeshjaga/coding-bootcamp-testimonials-slider"
            netlify="https://trusting-noether-bb56d8.netlify.app/"
            status="completed"
            imgurl="https://github.com/rajeshjaga/Front-End-mentor-Challenges/blob/master/src/assets/challenge3.jpg?raw=true"
            cardTitle="Coding Bootcamp Testimonials Slider"
          />
        </b-col>
        <b-col lg="4">
          <card
            netlify="https://xenodochial-albattani-054c20.netlify.app/"
            github="https://github.com/rajeshjaga/four-card-feature-section"
            status="completed"
            imgurl="https://github.com/rajeshjaga/Front-End-mentor-Challenges/blob/master/src/assets/challenge4.jpg?raw=true"
            cardTitle="Four card feature section"
          />
        </b-col>
        <b-col lg="4">
          <card
            github="https://github.com/rajeshjaga/base-apparel-coming-soon"
            netlify="https://admiring-noyce-0b9a06.netlify.app/"
            status="completed"
            imgurl="https://github.com/rajeshjaga/Front-End-mentor-Challenges/blob/master/src/assets/challenge5.jpg?raw=true"
            cardTitle="Base Apparel coming soon page"
          />
        </b-col>
        <b-col lg="4">
          <card
            github="https://github.com/rajeshjaga/intro-component-with-signup-form"
            netlify="https://vibrant-bell-389ca5.netlify.app/"
            status="completed"
            imgurl="https://github.com/rajeshjaga/Front-End-mentor-Challenges/blob/master/src/assets/challenge6.jpg?raw=true"
            cardTitle=" Intro component with sign up form"
          />
        </b-col>
        <b-col lg="4">
          <card
            github="https://github.com/rajeshjaga/single-price-grid-component"
            netlify="https://youthful-archimedes-b4a295.netlify.app/"
            status="completed"
            imgurl="https://github.com/rajeshjaga/Front-End-mentor-Challenges/blob/master/src/assets/challenge7.jpg?raw=true"
            cardTitle="Single Price Grid Component"
          />
        </b-col>
        <b-col lg="4">
          <card
            netlify="https://gifted-tesla-6c0cea.netlify.app/"
            github="https://github.com/rajeshjaga/ping-coming-soon-page"
            status="completed"
            imgurl="https://github.com/rajeshjaga/Front-End-mentor-Challenges/blob/master/src/assets/challenge8.jpg?raw=true"
            cardTitle="Ping coming soon page"
          />
        </b-col>
        <b-col lg="4">
          <card
            netlify="https://gracious-carson-611454.netlify.app/"
            github="https://github.com/rajeshjaga/huddle-landing-page-with-single-introductory-section"
            status="completed"
            imgurl="https://github.com/rajeshjaga/Front-End-mentor-Challenges/blob/master/src/assets/challenge9.jpg?raw=true"
            cardTitle="Huddle landing page "
          />
        </b-col>
        <b-col lg="4">
          <card
            netlify="https://cranky-lalande-3405f8.netlify.app/"
            github="https://github.com/rajeshjaga/Huddle-landing-page-with-alternating-feature-blocks"
            status="completed"
            imgurl="https://github.com/rajeshjaga/Front-End-mentor-Challenges/blob/master/src/assets/challenge12.jpg?raw=true"
            cardTitle="Huddle landing page"
          />
        </b-col>
        <b-col lg="4">
          <card
            netlify="https://laughing-kirch-c3c668.netlify.app/"
            github="https://github.com/rajeshjaga/fylo-landing-page-with-two-column-layout"
            status="completed"
            imgurl="https://github.com/rajeshjaga/Front-End-mentor-Challenges/blob/master/src/assets/challenge11.jpg?raw=true"
            cardTitle="Fylo landing page"
          />
        </b-col>
        <b-col lg="4">
          <card
            netlify="https://eloquent-heisenberg-0f2118.netlify.app/"
            github="https://github.com/rajeshjaga/social-media-dashboard-with-theme-switcher-master"
            status="completed"
            imgurl="https://github.com/rajeshjaga/Front-End-mentor-Challenges/blob/master/src/assets/challenge10.jpg?raw=true"
            cardTitle="Social media dashboard with theme switcher"
          />
        </b-col>
        <b-col lg="4">
          <card
            status="incomplete"
            imgurl="https://github.com/rajeshjaga/Front-End-mentor-Challenges/blob/master/src/assets/challenge13.jpg?raw=true"
            cardTitle="Insure landing page"
          />
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>
<script>
import card from "../components/cards";
export default {
  name: "pageRoute",
  components: {
    card,
  },
};
</script>
<style  >
.card {
  margin: 30px 10px;
}
.column {
  margin: 0 auto;
}
#pageRoute {
  margin-bottom: 50px;
}
</style>