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
          <li>
            <p>(2/24/2020 || Javascript)</p>
            <p>Create a function that returns true when num1 is equal to num2; otherwise return false.</p>
            <img src="../assets/solutions/fourth.png" alt />
          </li>
          <li>
            <p>(2/24/2020 || Javascript)</p>
            <p>Create a function that takes height and width and finds the perimeter of a rectangle.</p>
            <img src="../assets/solutions/fifth.png" alt />
          </li>
          <li>
            <p>(2/25/2020 || Javascript)</p>
            <p>Create a function that takes a number as an argument and returns "even" for even numbers and "odd" for odd numbers.</p>
            <img src="../assets/solutions/sixth.png" alt />
          </li>
          <li>
            <p>(2/25/2020 || Javascript)</p>
            <p>Create a function that returns the number of frames shown in a given number of minutes for a certain FPS.</p>
            <img src="../assets/solutions/seventh.png" alt />
          </li>
          <li>
            <p>(2/25/2020 || Javascript)</p>
            <p>Create a function that takes a string (a random name). If the last character of the name is an "n", return true, otherwise return false.</p>
            <p>**str.endsWith(charToSearchFor)**</p>
            <img src="../assets/solutions/eighth.png" alt />
          </li>
          <li>
            <p>(2/25/2020 || Javascript)</p>
            <p>Create a function that takes in three arguments (prob, prize, pay) and returns true if prob * prize > pay; otherwise return false.</p>
            <img src="../assets/solutions/ninth.png" alt />
          </li>
          <li>
            <p>(2/25/2020 || Javascript)</p>
            <p>Given two strings, firstName and lastName, return a single string in the format "last, first".</p>
            <img src="../assets/solutions/tenth.png" alt />
          </li>
          <li>
            <p>(2/25/2020 || Javascript)</p>
            <p>Create a function that takes an object argument sizes (contains width, length, height keys) and returns the volume of the box.</p>
            <img src="../assets/solutions/eleventh.png" alt />
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
