<template>
  <div id="card ">
    <div>
      <b-card
        v-if="status==`completed`"
        :img-src="imgurl"
        img-alt="Image"
        img-top
        tag="article"
        style="max-width: 20rem; filter:drop-shadow(0 5px 10px rgba(0,0,0,0.2))"
        class="mb-2"
      >
        <b-card-title>{{cardTitle}}</b-card-title>
        <b-row>
          <b-col>
            <b-button v-bind:href="netlify" size="sm" variant="primary float-center">live</b-button>
          </b-col>
          <b-col>
            <b-button v-bind:href="github" variant="primary float-center " size="sm">Code</b-button>
          </b-col>
        </b-row>
      </b-card>
    </div>
    <div>
      <b-card
        v-if="status==`incomplete`"
        v-bind:img-src="imgurl"
        img-alt="Image"
        img-top
        style="filter:grayscale(1) "
        tag="article"
        class="mb-2"
      >
        <b-card-title>{{cardTitle}}</b-card-title>
        <b-card-text>Coming Soon</b-card-text>
        <b-button v-bind:href="link" variant="primary" disabled>Coming Soon</b-button>
      </b-card>
    </div>
  </div>
</template>

<script>
export default {
  name: "card",
  props: ["imgurl", "status", "github", "netify"],
};
</script>
<style  scoped>
b-button {
  display: block;
  margin: 0 10px;
}
.right-one {
  display: inline-block;
  margin-left: 10px;
}
</style>