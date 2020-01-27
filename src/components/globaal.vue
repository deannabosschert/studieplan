<template>
  <div class="hello">
    <h1>Globaal</h1>
    <table class="table1">
      <thead>
        <tr>
          <th>Blok 3- MWD</th>
          <th>EC</th>
          <th>Blok 4- MWD</th>
          <th>EC</th>
          <th>Blok 1- Herkansingen</th>
          <th>EC</th>
          <th>Blok 2- Herkansingen</th>
          <th>EC</th>
          <th>Blok 3- Afstudeerstage</th>
          <th>EC</th>
          <th>Blok 4- Afstudeerproject</th>
          <th>EC</th>
        </tr>
        <tr>
          <td>Web Apps from Scratch</td>
          <td>3</td>
          <td>Real-time Web</td>
          <td>3</td>
          <td>PW-Vormgeving</td>
          <td>3</td>
          <td>DataVis<br /></td>
          <td>3</td>
          <td>Lange Stage<br /></td>
          <td>30</td>
          <td>Afstudeerproject</td>
          <td>30</td>
        </tr>
        <tr>
          <td>Project 1</td>
          <td>nvt</td>
          <td>Weekly Nerd</td>
          <td>3</td>
          <td>PW- Design Patterns</td>
          <td>3</td>
          <td>Research<br />for Data</td>
          <td>3</td>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
        </tr>
        <tr>
          <td>Project 2</td>
          <td>nvt</td>
          <td>Project 3</td>
          <td>nvt</td>
          <td>PW- Frontend</td>
          <td>3</td>
          <td>TechTrack</td>
          <td>3</td>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
        </tr>
        <tr>
          <td>Performance Matters</td>
          <td>3</td>
          <td>Meesterproef</td>
          <td>9</td>
          <td>PW- Project</td>
          <td>5</td>
          <td>Project Tech</td>
          <td>5</td>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
        </tr>
        <tr>
          <td>Browser<br />Technologies</td>
          <td>3</td>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
        </tr>
        <tr>
          <td><b>TOTAAL EC</b></td>
          <td><b>9</b></td>
          <td></td>
          <td><b>15</b></td>
          <td></td>
          <td><b>14</b></td>
          <td></td>
          <td><b>14</b></td>
          <td></td>
          <td><b>30</b></td>
          <td></td>
          <td><b>30</b></td>
        </tr>
      </thead>
      <tbody></tbody>
    </table>
  </div>
</template>

<script>
export default {
  name: "planA",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
.table1 {
  border: 1px ridge #ffffff;
  border-collapse: separate;
  border-spacing: 1px;
  padding: 9px;
}
.table1 th {
  border: 1px ridge #ffffff;
  padding: 9px;
  background: #c8a2c8;
}
.table1 td {
  border: 1px ridge #ffffff;
  text-align: center;
  padding: 9px;
  background: #f2e8f2;
}
</style>
