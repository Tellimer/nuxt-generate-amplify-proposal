<template>
  <ProfessionalExperiences />
</template>

<script>
export default {
  data() {
    var name = "Tellimer Engineering Experiment";
    var pageName = "Timeline";
    return {
      title: name + " | " + pageName,
    };
  },
  head() {
    return {
      title: this.title,
    };
  },
};
</script>
