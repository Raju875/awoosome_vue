<template>
  <div class="row">
    <div class="card col-2" v-for="info in infos" :key="info.name">
      <div class="card-title">
        <h3 class="title">{{ info.name }}</h3>
      </div>
      <div class="card-body">
        <li>{{ info.age }}</li>
        <li>{{ info.occupation }}</li>
        <li>{{ info.phone }}</li>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      infos: [
        {
          name: "Ali Azgar Rana",
          age: 30,
          occupation: "Businessman",
          phone: "017",
        },
        {
          name: "Mohammad Al Amin Raju Dottry",
          age: 29,
          occupation: "Software Engineer",
          phone: "016",
        },
        {
          name: "Ariful Islam Raj",
          age: 19,
          occupation: "Student",
          phone: "018",
        },
        {
          name: "Ali Azgar Rana",
          age: 30,
          occupation: "Businessman",
          phone: "017",
        },
        {
          name: "Al Amin Raju",
          age: 29,
          occupation: "Software Engineer",
          phone: "016",
        },
        {
          name: "Ariful Islam Raj",
          age: 19,
          occupation: "Student",
          phone: "018",
        },
        {
          name: "Ali Azgar Rana",
          age: 30,
          occupation: "Businessman",
          phone: "017",
        },
        {
          name: "Al Amin Raju",
          age: 29,
          occupation: "Software Engineer",
          phone: "016",
        },
        {
          name: "Ariful Islam Raj",
          age: 19,
          occupation: "Student",
          phone: "018",
        },
        {
          name: "Ali Azgar Rana",
          age: 30,
          occupation: "Businessman",
          phone: "017",
        },
        {
          name: "Al Amin Raju",
          age: 29,
          occupation: "Software Engineer",
          phone: "016",
        },
        {
          name: "Ariful Islam Raj",
          age: 19,
          occupation: "Student",
          phone: "018",
        },
        {
          name: "Ali Azgar Rana",
          age: 30,
          occupation: "Businessman",
          phone: "017",
        },
        {
          name: "Al Amin Raju",
          age: 29,
          occupation: "Software Engineer",
          phone: "016",
        },
        {
          name: "Ariful Islam Raj",
          age: 19,
          occupation: "Student",
          phone: "018",
        },
        {
          name: "Ali Azgar Rana",
          age: 30,
          occupation: "Businessman",
          phone: "017",
        },
        {
          name: "Al Amin Raju",
          age: 29,
          occupation: "Software Engineer",
          phone: "016",
        },
        {
          name: "Ariful Islam Raj",
          age: 19,
          occupation: "Student",
          phone: "018",
        },
      ],
    };
  },
};
</script>

<style scoped>
.card {
  border: 1px solid black;
  display: inline-block;
  border-radius: 8px;
  margin: 5px;
}
.title {
  margin: 0px;
  padding: 5px;
}
.card-title {
  /* display: inline-block; */
  background: #c10fed;
  border-top-left-radius: 5px;
  border-top-right-radius: 5px;
  max-width: 222px;
  max-height: 32px;
  overflow-x: hidden;
}
.card-body {
  background: #eac4f1;
  text-align: left;
  padding: 2px 10px;
  list-style: none;
  border-bottom-left-radius: 5px;
  border-bottom-right-radius: 5px;
  max-width: 202px;
  max-height: 55px;
  /* overflow: auto; */
  overflow-y: hidden;
}

/* grid system start */
.row::after {
  content: "";
  clear: both;
  display: table;
}

[class*="col-"] {
  float: left;
  padding: 15px;
  border: 1px solid red;
}

.col-1 {
  width: 8.33%;
}
.col-2 {
  width: 16.66%;
}
.col-3 {
  width: 25%;
}
.col-4 {
  width: 33.33%;
}
.col-5 {
  width: 41.66%;
}
.col-6 {
  width: 50%;
}
.col-7 {
  width: 58.33%;
}
.col-8 {
  width: 66.66%;
}
.col-9 {
  width: 75%;
}
.col-10 {
  width: 83.33%;
}
.col-11 {
  width: 91.66%;
}
.col-12 {
  width: 100%;
}
/* grid system end */
</style>
