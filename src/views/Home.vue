<template>
  <div class="home container-fluid">
    <div class="row">
      <div class="col-12">
        <ol class="challenges mx-1">
          <li>
            <p>(2/24/2020 || Javascript)</p>
            <p>Write a function that returns true if all characters in a string are identical and false otherwise.</p>
            <img src="../assets/solutions/1.png" alt />
          </li>
          <li>
            <p>(2/24/2020 || Javascript)</p>
            <p>Create a function that accepts an array and returns the last item in the array.</p>
            <img src="../assets/solutions/second.png" alt />
          </li>
          <li>
            <p>(2/24/2020 || Javascript)</p>
            <p>Create a function that returns true if an integer is evenly divisible by 5, and false otherwise.</p>
            <img src="../assets/solutions/third.png" alt />
          </li>
        </ol>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home"
};
</script>

<style>
.challenges {
  display: flex;
  flex-direction: row;
  height: 90vh;
  overflow-y: scroll;
  width: 100vw;
  flex-wrap: wrap;
}
ol li {
  margin: 10pt;
  padding: 3pt;
  border: 1pt solid black;
}
</style>
