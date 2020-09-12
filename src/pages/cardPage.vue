<template>
  <div id="pageRoute">
    <div class="container">
      <b-row>
        <b-col>
          <card
            status="completed"
            imgurl="https://github.com/rajeshjaga/Front-End-mentor-Challenges/blob/master/src/assets/challenge1.jpg?raw=true"
          />
        </b-col>
        <b-col>
          <card
            status="completed"
            imgurl="https://github.com/rajeshjaga/Front-End-mentor-Challenges/blob/master/src/assets/challenge2.jpg?raw=true"
          />
        </b-col>
        <b-col>
          <card
            status="completed"
            imgurl="https://github.com/rajeshjaga/Front-End-mentor-Challenges/blob/master/src/assets/challenge3.jpg?raw=true"
          />
        </b-col>
        <b-col>
          <card
            status="completed"
            imgurl="https://github.com/rajeshjaga/Front-End-mentor-Challenges/blob/master/src/assets/challenge4.jpg?raw=true"
          />
        </b-col>
      </b-row>
    </div>
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
<style lang="scss" scoped>
</style>