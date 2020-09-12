<template>
  <div id="card ">
    <div>
      <b-card
        v-if="status==`completed`"
        :img-src="imgurl"
        img-alt="Image"
        img-top
        tag="article"
        style="max-width: 20rem;"
        class="mb-2"
      >
        <b-card-title>{{cardTitle}}</b-card-title>
        <b-row>
          <b-button v-bind:href="link" size="sm" variant="primary float-right">live</b-button>
          <b-button v-bind:href="link" variant="primary float-right " size="sm">Code</b-button>
        </b-row>
      </b-card>
    </div>
    <div>
      <b-card
        v-if="status==`incomplete`"
        v-bind:img-src="imgurl"
        img-alt="Image"
        img-top
        tag="article"
        style="max-width: 20rem;"
        class="mb-2"
      >
        <b-card-title>{{cardTitle}}</b-card-title>
        <b-button v-bind:href="link" variant="primary">Coming Soon</b-button>
      </b-card>
    </div>
  </div>
</template>

<script>
export default {
  name: "card",
  props: ["imgurl", "status"],
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