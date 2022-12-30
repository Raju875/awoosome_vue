<template>
  <div>
    <li v-for="info in infos" :key="info.name">
      <ol>
        {{
          info.name
        }}
      </ol>
      <ol>
        {{
          info.age
        }}
      </ol>
      <ol>
        {{
          info.occupation
        }}
      </ol>
      <ol>
        {{
          info.phone
        }}
      </ol>
    </li>
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
